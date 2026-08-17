# Borrador de modelo de proceso – Equipo SinfoníaSoft

**Integrantes que participaron:**
-	Jhon Willian Mayta Arotaype
-	Luis Alejandro Chino León
-	Rody Jossep Chuquimamani Apaza
-	Cristhian Brandonlyn Alejo Castillo

**Proyecto:** Sistema web para la gestión de alquiler de escenarios y equipos de sonido para eventos  
**Empresa:** Sonido Activo Canaza  
**Curso:** Ingeniería de Software I

---

## 1. Resumen de proceso y gestión de software

El proceso de ingeniería de software comprende el conjunto de actividades organizadas que permiten desarrollar y mantener un sistema de software. Define cómo se realiza el trabajo, qué actividades debe cumplir el equipo y cómo se orienta el desarrollo hacia un producto que satisfaga las necesidades de los usuarios.

La gestión de la ingeniería de software incluye la planificación, organización, estimación, seguimiento y control de las actividades del proyecto. Permite coordinar al equipo, administrar recursos, controlar el avance e identificar riesgos. Una buena gestión facilita la toma de decisiones ante cambios o problemas durante el desarrollo.

En nuestro caso, estos conceptos se aplican al desarrollo de un sistema web para **Sonido Activo Canaza**, empresa dedicada al alquiler de escenarios y equipos de sonido para eventos. El sistema gestionará clientes, escenarios, equipos, disponibilidad y reservas. Por ello es necesario organizar las actividades del equipo, definir funcionalidades prioritarias y realizar un seguimiento constante del avance.

---

## 2. Comparación de modelos de proceso

### 2.1 Modelo en cascada
Organiza el desarrollo en etapas secuenciales (requisitos → diseño → implementación → pruebas → entrega).  
**Ventaja:** estructura clara y planificación definida desde el inicio.  
**Desventaja:** poca flexibilidad ante cambios de requisitos.  
Para nuestro proyecto resultaría rígido, porque es probable que aparezcan nuevas necesidades relacionadas con reservas, disponibilidad o gestión de eventos durante el desarrollo.

### 2.2 Modelo incremental
Desarrolla el sistema por partes o incrementos, cada uno con nuevas funcionalidades.  
**Ventaja:** permite entregar versiones funcionales de forma progresiva.  
**Desventaja:** requiere buena planificación de la integración entre incrementos.  
Es viable para nuestro sistema (por ejemplo: primero clientes y equipos, luego disponibilidad y finalmente reservas), pero ofrece menos estructura de roles y eventos que el enfoque ágil.

### 2.3 Modelo ágil
Desarrolla el software de forma iterativa e incremental, con entregas frecuentes y adaptación continua de los requisitos. El equipo colabora estrechamente y revisa el avance de manera constante.  
Es especialmente adecuado cuando los requisitos no están completamente definidos o pueden cambiar.

---

## 3. Modelo de proceso elegido

**Ágil (Scrum)**

---

## 4. Justificación de la elección

Elegimos el modelo ágil porque el proyecto presenta características que se benefician de la flexibilidad y de las entregas frecuentes:

- Los requisitos aún no están completamente definidos y es esperable que evolucionen conforme se realicen reuniones con la empresa y se revisen los avances.
- El sistema debe gestionar varios módulos (clientes, escenarios, equipos de sonido, disponibilidad y reservas) que pueden construirse e integrarse de forma progresiva.
- Contamos con aproximadamente 14 semanas. Los sprints cortos permiten entregar valor temprano y recibir retroalimentación del docente y de la empresa.
- El equipo está formado por 4 integrantes con algo de experiencia, tamaño ideal para un Scrum Team.
- La naturaleza del negocio (alquiler de escenarios y equipos para eventos) implica cambios frecuentes de disponibilidad y necesidades, por lo que un enfoque adaptable es más conveniente que uno secuencial rígido.

Comparado con cascada e incremental, el enfoque ágil nos da mejor capacidad de respuesta al cambio y una estructura clara de roles, eventos y artefactos (Product Backlog, Sprint Backlog, Incremento, etc.).

---

## 5. Riesgos y limitaciones del enfoque ágil

1. **Cambios frecuentes en los requisitos**  
   Las solicitudes constantes de la empresa pueden alterar la planificación.  
   *Mitigación:* priorizar el Product Backlog y definir objetivos claros por sprint.

2. **Falta de coordinación o disciplina del equipo**  
   Scrum exige comunicación constante y respeto a los eventos. Si no se mantiene la disciplina, se generan retrasos o trabajo duplicado.  
   *Mitigación:* establecer Daily Scrum y Definition of Done claras desde el inicio.

3. **Disponibilidad limitada de los usuarios de la empresa**  
   Si los responsables de Sonido Activo Canaza no pueden revisar los avances con frecuencia, se puede detectar tarde la necesidad de cambios.  
   *Mitigación:* programar revisiones periódicas y validar con el docente cuando no sea posible con el cliente.

---

## 6. Aplicación inicial del proceso al proyecto

Organización tentativo por etapas / sprints:

**Primera etapa**
- Registro y gestión de clientes
- Registro de escenarios
- Registro de equipos de sonido

**Segunda etapa**
- Consulta de disponibilidad de escenarios y equipos
- Gestión de fechas de eventos
- Actualización del estado de los recursos

**Tercera etapa**
- Registro de solicitudes y reservas
- Gestión del estado de las reservas
- Generación de información de los servicios contratados

**Cuarta etapa**
- Pruebas del sistema
- Corrección de errores
- Mejoras según la retroalimentación recibida

---

## 7. Conclusión

Después de comparar los modelos cascada, incremental y ágil, el equipo considera que el **modelo ágil** es el más adecuado para el desarrollo del sistema de Sonido Activo Canaza. Permite desarrollar las funcionalidades de forma progresiva, incorporar retroalimentación y adaptarse a los cambios de requisitos, lo que facilita construir un producto más alineado con las necesidades reales de la empresa.

---

## 8. Referencias

- Washizaki, H. (Ed.). (2024). *Guide to the SWEBOK, Version 4.0*. IEEE Computer Society.
- Sommerville, I. (2016). *Ingeniería de software* (10.ª ed., cap. 2). Pearson.
- Schwaber, K., & Sutherland, J. *La Guía de Scrum* (versión vigente).
