# Borrador de modelo de proceso – Equipo SinfoníaSoft

**Integrantes que participaron:**
- Jhon Willian Mayta Arotaype
- Luis Alejandro Chino León
- Rody Jossep Chuquimamani Apaza
- Cristhian Brandonlyn Alejo Castillo

## Modelo de proceso elegido

Ágil (Scrum)

## Justificación

Nuestro proyecto consiste en el desarrollo de un sistema de software para una empresa dedicada a la organización y gestión de orquestas musicales. Al inicio del trabajo los requisitos aún no están completamente definidos y es esperable que evolucionen conforme avancemos y recibamos retroalimentación del docente y, de ser posible, de la empresa o cliente real.

Elegimos un enfoque ágil basado en Scrum por las siguientes razones:

1. **Requisitos inciertos**: Al no contar todavía con una especificación estable, un modelo en cascada resultaría demasiado rígido. Scrum nos permite descubrir y refinar los requisitos de forma iterativa a lo largo de los sprints.
2. **Entregas parciales de valor**: Contamos con aproximadamente 14 semanas. Con sprints de 2 semanas podemos entregar incrementos funcionales (por ejemplo: gestión de músicos y repertorio en un primer sprint, programación de ensayos y eventos en el siguiente, control de asistencia y reportes posteriormente).
3. **Tamaño del equipo**: Somos 4 integrantes con algo de experiencia previa. Este tamaño es ideal para conformar un Scrum Team.
4. **Feedback frecuente**: Presentaremos avances al profesor y, si se concreta, también a la empresa. Scrum está diseñado para incorporar feedback de forma continua.
5. **Naturaleza del dominio**: Un sistema para orquestas involucra roles, eventos, calendario, disponibilidad de músicos y cambios frecuentes. Un enfoque ágil permite adaptarse mejor a estos cambios que un modelo secuencial.

Comparamos brevemente las otras opciones:
- **Cascada**: Solo sería adecuada si los requisitos estuvieran completamente definidos y estables desde el inicio, lo cual no es nuestro caso.
- **Incremental clásico**: También es viable, pero Scrum nos aporta una estructura más clara de roles, eventos y artefactos que facilita la organización del equipo y el seguimiento del progreso.

## Riesgos o limitaciones del enfoque elegido

1. **Dependencia de la disciplina del equipo**: Scrum requiere que se respeten los eventos (Daily Scrum, Sprint Planning, Review y Retrospective). Si el equipo no mantiene la disciplina, el proceso se degrada y se pierde el beneficio de la inspección y adaptación.

2. **Posible acumulación de deuda técnica**: Al priorizar la entrega de valor en cada sprint, existe el riesgo de postergar la calidad del código o la arquitectura. Debemos ser cuidadosos con la Definition of Done e incluir tareas de refactorización y control de deuda técnica en el backlog.

3. **Disponibilidad limitada del “cliente”**: En un entorno académico el feedback del profesor (o de un eventual cliente de la empresa de orquestas) no siempre será tan frecuente como en un proyecto real. Esto puede afectar la priorización del Product Backlog si no logramos reuniones regulares de refinamiento.

## Referencias

- Washizaki, H. (Ed.). (2024). *Guide to the SWEBOK, Version 4.0*. IEEE Computer Society.
- Sommerville, I. (2016). *Ingeniería de software* (10.ª ed., cap. 2). Pearson.
- Schwaber, K., & Sutherland, J. *La Guía de Scrum* (versión 2020).
