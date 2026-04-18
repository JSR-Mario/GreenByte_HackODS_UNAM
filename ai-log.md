# AI Log — Equipo GreenByte
**HackODS UNAM 2026 · ODS 13**

---

## Herramientas utilizadas

- Claude (claude.ai) — Anthropic
- GitHub Copilot (VS Code)

---

## Filosofía de uso

Decidimos usar herramientas de IA exclusivamente para tareas de aceleración técnica: generación de código boilerplate, depuración de errores de GEE, y revisión crítica de narrativa. Todas las decisiones científicas —selección de variables, diseño del índice de multi-estrés, interpretación de hotspots, elección de ventana temporal armonizada 2019–2024 por la discontinuidad OMI→S5P— fueron tomadas y justificadas por el equipo.

**Criterio de delegación:** Si la decisión requiere conocimiento del contexto climático mexicano o criterio analítico sobre los ODS, la tomamos nosotros. Si la tarea es mecánica o de sintaxis, la delegamos con revisión.

---

## Registro de uso

### 2026-04-06 | Claude | Estructura del repositorio
- **Tarea:** Generar la estructura base del repositorio de GitHub conforme a los requisitos del Módulo A de la rúbrica HackODS (README, LICENSE CC BY-SA, ai-log.md, carpetas datos/scripts/dashboard).
- **Prompt:** Análisis de los notebooks de extracción y EDA para extraer fuentes, variables y metadatos reales del proyecto.
- **Resultado:** README.md con tabla de metadatos completa, LICENSE CC BY-SA 4.0, ai-log.md con plantilla oficial, estructura de carpetas.
- **Decisión del equipo:** Aceptamos la estructura base. Revisamos y validamos que todos los metadatos (fuentes, fechas, licencias, variables) corresponden exactamente al pipeline real del proyecto. La pregunta central y la descripción narrativa fueron escritas por el equipo; Claude organizó el formato.

---

<!-- 
INSTRUCCIONES PARA EL EQUIPO:
Cada vez que usen IA durante el hackathon, agreguen una entrada siguiendo este formato:

### YYYY-MM-DD | Herramienta | Tarea breve
- **Tarea:** Descripción de qué problema tenían y qué le pidieron a la IA.
- **Prompt:** El prompt exacto o una descripción reproducible de él.
- **Resultado:** Qué les dio la IA.
- **Decisión del equipo:** Por qué aceptaron, rechazaron o modificaron la salida. 
  Incluyan qué conocimiento propio aplicaron al evaluar el resultado.

Si NO usaron IA en alguna decisión importante, pueden documentarlo también:
### Decisiones sin IA
- Selección de las 26 variables del dataset → revisión de literatura ODS 13 + criterio del equipo
- Diseño del índice multi-estrés → discusión interna sobre qué captura mejor el colapso ecosistémico compuesto
- Interpretación de hotspots en CDMX y Texas → conocimiento regional del equipo
-->
