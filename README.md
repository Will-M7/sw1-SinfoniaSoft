# MilkCollect - Sistema Móvil de Acopio de Leche

> Gestión eficiente, registro fuera de línea y control integral del acopio de leche para productores y centros de recolección.

## Problema que resuelve
En el ámbito agropecuario regional, la recolección de leche suele registrarse de forma manual mediante planillas de papel, lo que genera errores de cálculo en montos a pagar, pérdida de información histórica y demoras en el control de calidad. Además, la conectividad a internet en las zonas rurales de acopio es inestable o nula, lo que dificulta la adopción de sistemas centralizados tradicionales.

## Público objetivo
- **Productores ganaderos / lecheros:** Desean transparencia en el registro de litros entregados, pruebas de calidad y fechas de pago.
- **Centros de acopio y acopiadores:** Requieren agilizar el registro diario en campo, calcular importes automáticamente y generar reportes consolidados sin depender de una conexión continua a internet.

## Funcionalidades previstas
- **Gestión de productores:** Registro, edición y consulta del padrón de productores lecheros.
- **Registro de entregas:** Captura de litros entregados, fecha, hora y parámetros de control de calidad (grasa, densidad, acidez).
- **Cálculo de importes y pagos:** Determinación de montos a pagar según tarifa/calidad y registro de liquidaciones.
- **Sincronización Offline-first:** Registro de datos en almacenamiento local y sincronización automática al detectar conexión a red.
- **Consultas y reportes:** Historial de entregas por productor y reportes resumidos por rangos de fecha.

## Entidad principal del CRUD
**Entidad:** `EntregaLeche`
- `idEntrega`: String (UUID)
- `idProductor`: String
- `fechaHora`: LocalDateTime
- `cantidadLitros`: Double
- `precioPorLitro`: Double
- `montoTotal`: Double
- `estadoControlCalidad`: String (Aprobado/Observado/Rechazado)
- `estadoPago`: String (Pendiente/Pagado)

## Capacidad nativa prevista
- **Conectividad Bluetooth / Impresión térmica:** Generación e impresión nativa de comprobantes de recepción en ticketera portátil al momento del acopio en campo.
- **Ubicación GPS:** Registro automático de las coordenadas geográficas del punto de recolección.

## Equipo de Desarrollo

| Integrante | Código | Rol (Semana 1) |
|---|---|---|
| Jhon Willian Mayta Arotaype | 202413545 | Coordinador(a) |
| Cristhian Brandonlyn Alejo Castillo | 202410802 | Dev. de Lógica y Datos |
| Rody Jossep Chuquimamani Apaza | 202320265 | Dev. de UI |
| Luis Alejandro Chino León | *(Pendiente)* | QA y Documentación |

## Tecnologías
- **Framework:** Kotlin Multiplatform (KMP)
- **UI:** Compose Multiplatform
- **Plataformas objetivo:** Android / Desktop
- **Patrón de Arquitectura:** Clean Architecture + MVVM
- **Almacenamiento local:** SQLDelight / Room KMP (Enfoque Offline-first)
