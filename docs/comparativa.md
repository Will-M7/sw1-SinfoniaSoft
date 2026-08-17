# Cuadro Comparativo de Frameworks Multiplataforma Móviles

**Autores:** Equipo de Desarrollo DAM  
**Fecha:** Semana 1 - Semestre 2025-II  

---

## 1. Tabla Comparativa

| Dimensión | Kotlin Multiplatform (KMP) | Flutter | React Native |
|---|---|---|---|
| **1. Lenguaje y Curva de Aprendizaje** | Kotlin. Curva suave/media para desarrolladores Android/Java; excelente diseño del lenguaje (JetBrains, 2025). | Dart. Curva media/baja; sintaxis clara pero requiere aprender un lenguaje poco usado fuera de Flutter (Google, 2025). | JavaScript / TypeScript. Curva muy baja para desarrolladores web (Meta, 2025). |
| **2. Estrategia de UI** | Compartida u opcionalmente nativa (Jetpack Compose / Compose Multiplatform). Mantiene componentes nativos (JetBrains, 2025). | Motor gráfico propio (Impeller/Skia) que dibuja píxel por píxel la interfaz (Google, 2025). | Puente (Bridge/Fabric) que renderiza componentes nativos del sistema operativo (Meta, 2025). |
| **3. Reutilización de Código** | Lógica de negocio 100% compartida (Ktor, SQLDelight); UI totalmente compartida o adaptada por plataforma (JetBrains, 2025). | Código de UI y lógica 100% compartido entre plataformas (Google, 2025). | Código de UI y lógica compartido (~80-90%), requiriendo módulos nativos para casos complejos (Meta, 2025). |
| **4. Rendimiento y Resultado Técnico** | Alto rendimiento. Compila a bytecode JVM en Android y a binarios nativos (LLVM) en iOS/Desktop (JetBrains, 2025). | Alto rendimiento. Compila a código máquina nativo (AOT/JIT) (Google, 2025). | Rendimiento medio/alto; interaccionado mediante subprocesos y arquitectura de hilos (Meta, 2025). |
| **5. Ecosistema y Madurez** | En rápida expansión. KMP Alcanzó estabilidad en 2023; creciente adopción empresarial (JetBrains, 2025). | Muy maduro. Amplia variedad de paquetes en pub.dev y comunidad sólida (Google, 2025). | Extremadamente maduro. Gran ecosistema sustentado por npm y la comunidad web (Meta, 2025). |
| **6. Respaldo y Casos de Uso** | Respaldo por JetBrains y Google. Usado por Netflix, VMware, Cash App, McDonald's (JetBrains, 2025). | Respaldo por Google. Usado por BMW, Google Pay, Alibaba, eBay (Google, 2025). | Respaldo por Meta (Facebook). Usado por Instagram, Shopify, Discord, Coinbase (Meta, 2025). |
| **7. Entorno desde Windows** | Permite desarrollo, compilación y pruebas completas para Android y Desktop sin restricciones (JetBrains, 2025). | Permite desarrollo y pruebas para Android, Web y Windows Desktop (Google, 2025). | Permite desarrollo para Android y Web sin inconvenientes (Meta, 2025). |

---

## 2. Conclusión del Equipo y Justificación de Selección

Tras evaluar las tres tecnologías, nuestro equipo concluye que cada framework atiende necesidades específicas del mercado: **Flutter** es óptimo para la rápida creación de prototipos y aplicaciones donde el diseño visual unificado en múltiples plataformas es primordial; **React Native** es idóneo para empresas con equipos de desarrollo orientados a la web que buscan reducir costos de transición.

Para el desarrollo del **Sistema de Acopio de Leche (MilkCollect)**, la elección de **Kotlin Multiplatform (KMP)** se justifica técnicamente por las siguientes razones:

1. **Arquitectura limpia y separación de responsabilidades:** KMP permite compartir estrictamente la lógica de negocio, reglas de cálculo y persistencia local sin forzar abstracciones en la capa de interfaz de usuario.
2. **Capacidad Offline-first sólida:** La integración con librerías del ecosistema de Kotlin (como SQLDelight y Ktor) facilita la sincronización de datos y el almacenamiento SQLite nativo en zonas rurales sin señal.
3. **Desempeño y compatibilidad nativa:** Al compilar a binarios nativos en cada plataforma objetivo, KMP no sufre por capas intermedias de traducción ni puentes de ejecución, lo que asegura un uso óptimo del hardware en dispositivos móviles Android.

---

## 3. Referencias (Formato APA 7)

- Google. (2025). *Flutter documentation*. https://docs.flutter.dev/
- JetBrains. (2025). *Kotlin Multiplatform documentation*. https://kotlinlang.org/docs/multiplatform.html
- Meta. (2025). *React Native documentation*. https://reactnative.dev/docs/getting-started
