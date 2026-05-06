# analisis-resultados-paes
Automatización del análisis de resultados PAES de 10 cursos con Python — detección de brechas y estudiantes en riesgo,
# Análisis de Resultados PAES

¿Qué problema resuelve?

En colegios con múltiples cursos de 3° y 4° medio, el seguimiento de resultados PAES se hacía manualmente en Excel — un proceso que tomaba días de trabajo por cada ensayo. Este proyecto lo automatiza completamente: desde la carga de archivos hasta la generación de alertas críticas, en menos de 30 minutos.

¿Qué hace?

- Carga y consolida resultados de múltiples ensayos PAES desde archivos Excel
- Anonimiza datos sensibles de estudiantes (nombres, apellidos, RUT)
- Genera un reporte estadístico por ensayo con todos los cursos
- Hace seguimiento individual entre ensayos (E1 → E2 → E3)
- Detecta automáticamente estudiantes en riesgo: variaciones de ±50 puntos
- Exporta todo a Excel organizado por curso, con alertas separadas por curso

Herramientas

- Python 3
- Pandas
- openpyxl
- Jupyter Notebook

Estructura del output

- Una hoja por ensayo con resumen estadístico de los 10 cursos
- Hoja de seguimiento individual E1-E2-E3
- Una hoja de alertas por curso (primero subidas, luego bajadas)
