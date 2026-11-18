# Capítulo 5 · Conclusiones y recomendaciones

Este capítulo recoge la interpretación del autor a partir de la revisión documental y del diseño del Modelo de Ciberseguridad Adaptativo (MCA). El estudio formula una propuesta y deja su validación en terreno como línea de investigación.

## 5.1 Síntesis de hallazgos y cumplimiento de objetivos

La revisión documental identificó restricciones de personal y presupuesto y priorizó brechas en inventario y gestión de vulnerabilidades. A partir de esos antecedentes, el estudio adoptó el **Tier 1 (Parcial)** como punto de partida inferido y el **Tier 2 (Informado por el Riesgo)** como objetivo. La pertinencia de ese punto de partida debe comprobarse con evidencia de cada municipio. La tesis justifica una adopción gradual por el esfuerzo documental y operativo que puede exigir una implementación más amplia de otros marcos.

| Objetivo específico | Resultado del trabajo |
| --- | --- |
| Caracterizar las brechas | Se documentaron las restricciones de capacidad y se formuló un diagnóstico de referencia. |
| Priorizar controles técnicos | Se seleccionaron salvaguardas CIS IG1 para orientar la adopción inicial. |
| Estructurar el modelo y su gobernanza | Se definieron las fases del MCA y una matriz RACI para asignar funciones a roles municipales existentes. |
| Definir cómo medir y sostener la adopción | Se propusieron indicadores y una hoja de ruta gradual para revisar el avance. |

El objetivo general se concretó en el diseño del modelo y de su guía de adopción.

## 5.2 Impacto potencial en municipalidades de categorías 3 y 4

- **Operación y costos.** Las herramientas abiertas pueden reducir gastos de licencias. La formación, la infraestructura y el mantenimiento siguen formando parte del costo de adopción.
- **Gobernanza y trazabilidad.** La matriz RACI, los procedimientos y los indicadores permiten registrar quién actúa, qué se ejecutó y qué evidencia existe para el control interno.
- **Cultura institucional.** La asignación de funciones a cargos facilita la transferencia de responsabilidades cuando cambia el personal. El seguimiento de los indicadores ayuda a sostener la mejora continua.

La reducción de la exposición a incidentes y la viabilidad de la adopción son efectos esperados que deberán evaluarse en terreno.

## 5.3 Recomendaciones para la adopción e integración normativa

1. Usar la hoja de ruta y revisar sus indicadores al menos una vez al año.
2. Formalizar la política y las responsabilidades mediante la autoridad municipal competente. Revisar la aplicabilidad de las obligaciones y los procedimientos de reporte para el municipio.
3. Priorizar formación y capacidad de mantenimiento al seleccionar herramientas.
4. Levantar el inventario de equipos y software (CIS 1 y 2) para orientar la gestión de vulnerabilidades y parches (CIS 7).
5. Proteger los respaldos y practicar la restauración de datos críticos. La tesis propone pruebas trimestrales como medida de continuidad. Consulta el alcance de [CIS 11 e IG1](controles-cis.md).
6. Mantener un programa de concientización (CIS 14) y medir su cobertura. La tesis propone ejercicios de concientización sobre phishing.

## 5.4 Líneas futuras de investigación

- **Piloto municipal.** Aplicar el MCA durante 6 a 12 meses y comparar la cobertura de inventario, los tiempos de aplicación de parches y la evidencia documental con una línea base.
- **Automatización defensiva.** Evaluar la consolidación de inventarios, registros y hallazgos en un tablero que reduzca el trabajo manual y permita medir el esfuerzo operativo.
- **Transferencia a otros servicios.** Estudiar la adaptación a salud primaria y educación municipal, considerando la criticidad de sus servicios y sus recursos disponibles.

## 5.5 Herramientas de código abierto para operar el modelo

| Área | Herramientas mencionadas en la tesis |
| --- | --- |
| Registro y monitoreo de seguridad (CIS 8) | Wazuh. |
| Evaluación de vulnerabilidades (CIS 7) | OpenVAS / Greenbone Community Edition, según el alcance descrito en la [correspondencia CIS](controles-cis.md). |
| Inventario de activos (CIS 1 y 2) | GLPI para gestión de activos y NetBox para inventario de infraestructura de red y direccionamiento. |
| Segmentación y conectividad | pfSense. |
| Gestión de credenciales | KeePassXC. |
| Ofimática | LibreOffice. |
| Comunicación y coordinación | Mattermost, Jitsi Meet o Zulip, según el flujo de trabajo. |
| Gestión de tickets | GLPI. |
| Material de concientización (CIS 14) | Sitio interno de capacitación con Jekyll o Hugo. |

El catálogo documenta las opciones consideradas en el estudio. La selección para un municipio depende de su infraestructura, capacidad de soporte y costos de operación.

## 5.6 Conclusión técnica

El principal aporte técnico es vincular, en un ciclo de mejora, el diagnóstico de activos y riesgos, la asignación de responsabilidades, la ejecución de salvaguardas y el seguimiento de resultados. La combinación de NIST CSF y CIS IG1 permite orientar la adopción incremental. La viabilidad y la eficacia del ciclo dependen de que cada municipio pueda asignar tiempo, mantener evidencias y probar su capacidad de recuperación.

## 5.7 Conclusión general

El MCA ofrece una ruta para fortalecer la resiliencia municipal y proteger los servicios y datos de la ciudadanía en el contexto chileno. La investigación propone que municipios con recursos acotados pueden avanzar mediante prioridades de riesgo, responsabilidades claras y mejoras que puedan sostener. Un piloto permitirá evaluar qué partes del modelo son transferibles y qué ajustes requiere cada contexto.

Base documental: capítulo 5 del proyecto de título. La [metodología](metodologia.md), el [modelo](modelo-e-implementacion.md) y el [glosario](glosario.md) amplían los conceptos de este capítulo.
