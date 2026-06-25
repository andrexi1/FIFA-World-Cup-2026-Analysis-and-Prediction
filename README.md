Análisis y Predicción del Mundial FIFA 2026
Descripción del Proyecto

Este proyecto tiene como objetivo analizar las 48 selecciones clasificadas al Mundial FIFA 2026 y desarrollar un modelo de predicción para identificar los principales candidatos al título.

A través de Power BI se construyó un dashboard interactivo que combina información histórica de los mundiales, rankings FIFA, distribución de grupos y características de las selecciones participantes para generar hallazgos y apoyar la toma de decisiones basada en datos.

Objetivo de Negocio

Responder a la siguiente pregunta:

¿Qué selecciones tienen mayores probabilidades de ganar el Mundial FIFA 2026?

Para ello se desarrolló un modelo de puntuación basado en diferentes variables relacionadas con el rendimiento histórico y el nivel competitivo de cada selección.

Conjunto de Datos

El proyecto utiliza tres tablas principales:

1. Editions

Contiene información histórica de todas las Copas del Mundo disputadas entre 1930 y 2022.

Principales variables:

Año
País anfitrión
Campeón
Subcampeón
Cantidad de equipos
Cantidad de partidos
Goles anotados
Asistencia
Máximo goleador
Indicador de victoria del anfitrión
2. WC_2026_Teams

Información de las 48 selecciones clasificadas al Mundial 2026.

Principales variables:

Selección
Grupo
Confederación
Ranking FIFA
Director técnico
Mejor resultado histórico
Debut en Copa del Mundo
3. WC_2026_Fixtures

Calendario oficial de partidos del Mundial 2026.

Principales variables:

Equipos participantes
Grupo
Fase del torneo
Estadio
Ciudad
País sede
Fecha del encuentro
Herramientas Utilizadas
Power BI
DAX
Modelado de Datos
Visualización de Datos
Análisis Exploratorio de Datos (EDA)
Estructura del Dashboard
Página 1: Panorama General de las Selecciones

Objetivo:

Analizar la distribución de las selecciones clasificadas.

Indicadores principales:

Total de equipos clasificados
Ranking FIFA promedio
Número de confederaciones representadas
Equipos debutantes

Visualizaciones:

Equipos por confederación
Ranking promedio por confederación
Ranking FIFA por selección
Página 2: Fortaleza de Grupos y Camino al Mundial

Objetivo:

Identificar los grupos más competitivos del torneo.

Indicadores principales:

Índice de Fortaleza
Historial Mundialista
Equipos Top 20 FIFA
Campeones del Mundo por grupo

Visualizaciones:

Fortaleza de grupos
Ranking promedio por grupo
Historial por grupo
Matriz comparativa de grupos
Página 3: Historia y Tendencias de los Mundiales

Objetivo:

Analizar patrones históricos de la Copa del Mundo.

Indicadores principales:

Total de mundiales disputados
Total de goles anotados
Promedio histórico de goles por partido

Visualizaciones:

Evolución de goles por partido
Campeones históricos
Éxito de los países anfitriones
Página 4: Predicción del Campeón Mundial 2026

Objetivo:

Estimar los equipos con mayores probabilidades de ganar el torneo.

Variables consideradas:

Ranking FIFA
Historial Mundialista
Condición de campeón histórico
Fortaleza de la confederación

Visualizaciones:

Top 10 favoritos al título
Comparación por confederación
Tabla de clasificación del modelo predictivo
Metodología de Predicción

Se desarrolló un modelo de puntuación basado en múltiples factores:

Ranking FIFA
Historial en Copas del Mundo
Títulos mundiales obtenidos
Fortaleza de la confederación

La combinación de estas variables permitió construir un ranking explicable y transparente para comparar el potencial competitivo de cada selección.

Principales Hallazgos
UEFA concentra la mayor cantidad de selecciones clasificadas y varios de los principales candidatos al título.
Los grupos más fuertes combinan selecciones con alto ranking FIFA y amplio historial mundialista.
Brasil continúa siendo la selección más exitosa en la historia de los mundiales.
La ventaja de local influye en el rendimiento, pero no garantiza la obtención del título.
Francia, España y Argentina aparecen como los principales candidatos según el modelo de predicción desarrollado.
Autor

Andrés Barrera
