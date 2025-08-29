#  El Legado de los Gigantes del Fútbol: Del Pasado al Sorteo de Hoy

**Autor**: Manuel  
**Herramienta**: Power BI  
**Proyecto de la serie**: *Respondiendo dudas con datos*

##  Descripción

Informe interactivo que explora el rendimiento histórico de los clubes en la UEFA Champions League, con foco en los equipos presentes en el sorteo de 2024.

##  Dataset

Este proyecto requirió una limpieza y consolidación intensiva, realizada manualmente por el autor debido a la falta de recursos automáticos o datasets completos. El proceso incluyó:

- Integración de datos históricos hasta 2023 con datos recientes (2024 y 2025) de forma manual.
- Revisión y corrección de nombres de clubes (homogeneización de formatos: FC, AC, United, etc.).
- Cálculo de nuevas métricas:
  - `Points` = Wins × 3 + Draws × 1
  - `Efficiency (%)` = Points / (Played × 3)
- Creación de la clasificación histórica basada en puntos.
- Validación de cifras erróneas, especialmente en títulos, partidos y goles.
- Comprobación cruzada con fuentes externas para corregir inconsistencias graves.
- Trabajo exhaustivo de combinación de tablas sin errores de duplicación o malformación.

 Este proceso fue realizado íntegramente **por el autor**, sin automatización ni scraping, garantizando máxima fidelidad y detalle.

##  Visualizaciones (Power BI)

### Página 1 – Visión general
- Gráfico: Participación histórica por clubes.
- Gráfico: Títulos por país.
- KPI: Club más eficiente.
- Mapa: Distribución geográfica.
- Slicers por país y club.
- Drill Through a ficha de club.

### Página 2 – Detalle por club (Drill Through)
- Goles a favor / en contra.
- Resultados (W/D/L).
- Eficiencia.
- Total de puntos.
- Diseño limpio y personalizado.

## 🔍 Preguntas respondidas
- ¿Qué clubes dominan la historia de la Champions?
- ¿Qué países han ganado más títulos?
- ¿Quiénes llegan al sorteo de 2025 con más experiencia y logros?

## 📎 Notas
Este proyecto implicó una carga importante de limpieza y consolidación de datos. La información no se tomó directamente de una única fuente, sino que fue recopilada, cruzada y validada manualmente para asegurar coherencia y exactitud.
