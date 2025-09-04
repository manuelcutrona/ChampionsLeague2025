El Legado de los Gigantes del Fútbol: Del Pasado al Sorteo de Hoy

Descripción

Este proyecto es un informe interactivo en Power BI que analiza el rendimiento histórico de los clubes en la UEFA Champions League, con especial atención a los equipos presentes en el sorteo de 2024. La idea fue transformar un conjunto de datos incompleto y disperso en una visión clara, fiable y visualmente atractiva que permita responder a las preguntas más habituales sobre la competición.

Dataset y preparación

La parte más exigente del proyecto no fue la visualización, sino la preparación de los datos. Ante la falta de un dataset oficial y completo, realicé una consolidación manual que combinó registros históricos hasta 2023 con la información más reciente (2024 y 2025). Esto implicó un proceso minucioso de limpieza y verificación.

Primero, integré datos de diferentes fuentes y corregí inconsistencias en los nombres de clubes para homogeneizar formatos (FC, AC, United, etc.). Después, construí nuevas métricas que enriquecen el análisis: el cálculo de Points (3 por victoria, 1 por empate) y la Efficiency (%) como ratio de puntos obtenidos sobre puntos posibles. A partir de ahí, elaboré la clasificación histórica basada en puntos.

La validación de cifras fue una etapa crítica: revisé títulos, partidos y goles, corrigiendo errores significativos mediante comprobación cruzada con fuentes externas. El resultado final es un dataset coherente, sin duplicaciones ni registros malformados, preparado para un análisis detallado. Todo este trabajo fue realizado de forma manual, sin scraping ni automatización, lo que asegura la máxima fidelidad y atención al detalle.

Visualizaciones en Power BI

El dashboard se organiza en dos páginas principales.

La primera ofrece una visión global: un gráfico de participación histórica por clubes, otro que muestra títulos por país, un KPI que destaca al club más eficiente y un mapa que refleja la distribución geográfica de los equipos. Incluye también slicers interactivos para filtrar por país o club y la posibilidad de acceder a un drill through hacia una ficha detallada de cada club.

La segunda página está dedicada precisamente a ese detalle. Aquí se pueden ver los goles a favor y en contra, el desglose de resultados (victorias, empates y derrotas), la eficiencia, los puntos acumulados y otros indicadores clave. Todo con un diseño limpio y personalizado que facilita la exploración.

Preguntas respondidas

Gracias a este análisis, el informe permite responder de forma clara a cuestiones clave como:

¿Qué clubes dominan la historia de la Champions League?

¿Qué países han levantado más títulos a lo largo de los años?
- ¿Quiénes llegan al sorteo de 2025 con más experiencia y logros?

 Notas
Este proyecto implicó una carga importante de limpieza y consolidación de datos. La información no se tomó directamente de una única fuente, sino que fue recopilada, cruzada y validada manualmente para asegurar coherencia y exactitud.
