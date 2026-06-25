# Análisis y Predicción del Mundial FIFA 2026

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar las 48 selecciones clasificadas al Mundial FIFA 2026 y desarrollar un modelo de predicción para identificar los principales candidatos al título.

El dashboard fue desarrollado en Power BI utilizando información histórica de los mundiales, rankings FIFA, distribución de grupos y datos de las selecciones clasificadas. El propósito es transformar los datos en información útil que permita identificar tendencias, comparar equipos y estimar los favoritos para ganar el torneo.

---

## Objetivo de Negocio

Responder a la siguiente pregunta:

¿Qué selecciones tienen mayores probabilidades de ganar el Mundial FIFA 2026?

Para responder esta pregunta se construyó un modelo de puntuación basado en diferentes variables relacionadas con el desempeño histórico y el nivel competitivo de cada selección.

---

## Conjunto de Datos

El proyecto utiliza tres tablas principales:

### WC_all_Editions

Contiene información histórica de las Copas del Mundo disputadas entre 1930 y 2022.

Principales variables:

- Año del torneo
- País anfitrión
- Campeón
- Subcampeón
- Tercer y cuarto puesto
- Número de equipos participantes
- Número de partidos disputados
- Total de goles anotados
- Promedio de goles por partido
- Asistencia total
- Máximo goleador
- Ciudad de la final
- Indicador de victoria del anfitrión

### WC_2026_Teams

Contiene información de las 48 selecciones clasificadas al Mundial 2026.

Principales variables:

- Selección
- Grupo
- Confederación
- Ranking FIFA
- Director técnico
- Mejor resultado histórico en mundiales
- Indicador de debut en la Copa del Mundo

### WC_2026_Fixtures

Contiene el calendario oficial de partidos del Mundial 2026.

Principales variables:

- Equipos participantes
- Grupo
- Fase del torneo
- Estadio
- Ciudad
- País sede
- Fecha del encuentro

---

## Herramientas Utilizadas

- Power BI
- DAX
- Modelado de Datos
- Transformación de Datos
- Visualización de Datos
- Análisis Exploratorio de Datos

---

## Estructura del Dashboard

### Página 1: Panorama General de las Selecciones

Objetivo:

Presentar una visión general de las selecciones clasificadas al Mundial 2026.

Indicadores principales:

- Total de selecciones clasificadas
- Ranking FIFA promedio
- Confederaciones representadas
- Equipos debutantes

Visualizaciones:

- Equipos por confederación
- Ranking promedio por confederación
- Ranking FIFA por selección

### Página 2: Fortaleza de Grupos y Camino al Mundial

Objetivo:

Comparar la competitividad de los grupos y determinar cuáles presentan mayor dificultad.

Indicadores principales:

- Índice de Fortaleza
- Historial Mundialista
- Equipos Top 20 del Ranking FIFA
- Campeones del Mundo por grupo

Visualizaciones:

- Ranking de fortaleza por grupo
- Ranking FIFA promedio por grupo
- Historial mundialista por grupo
- Comparación entre grupos

### Página 3: Historia y Tendencias de los Mundiales

Objetivo:

Analizar la evolución histórica de la Copa Mundial de la FIFA.

Indicadores principales:

- Total de mundiales disputados
- Total de goles anotados
- Promedio histórico de goles por partido

Visualizaciones:

- Evolución de goles por partido
- Campeones históricos
- Éxito de los países anfitriones

### Página 4: Predicción del Campeón Mundial 2026

Objetivo:

Identificar las selecciones con mayores probabilidades de ganar el torneo mediante un modelo de puntuación.

Variables consideradas:

- Ranking FIFA
- Historial Mundialista
- Condición de campeón histórico
- Fortaleza de la confederación

Visualizaciones:

- Top 10 favoritos al título
- Comparación de puntuación por confederación
- Tabla de clasificación del modelo predictivo

---

## Metodología

Para estimar los candidatos al título se desarrolló un modelo de puntuación que combina diferentes factores asociados al rendimiento competitivo de una selección.

Variables utilizadas:

- Ranking FIFA
- Historial en Copas del Mundo
- Títulos mundiales obtenidos
- Fortaleza de la confederación

La combinación de estas variables permitió construir una puntuación comparativa para clasificar a las selecciones según su potencial competitivo.

---

## Principales Hallazgos

- UEFA concentra la mayor cantidad de selecciones clasificadas y varios de los principales candidatos al título.
- Los grupos más competitivos combinan selecciones con alto ranking FIFA y amplio historial mundialista.
- Brasil continúa siendo la selección más exitosa en la historia de los mundiales.
- La condición de anfitrión puede representar una ventaja competitiva, aunque no garantiza la obtención del título.
- Francia, España y Argentina aparecen entre los principales candidatos según el modelo de predicción desarrollado.

---

## Habilidades Demostradas

- Modelado de datos
- Transformación y limpieza de datos
- Creación de métricas con DAX
- Diseño de dashboards interactivos
- Análisis exploratorio de datos
- Storytelling con datos
- Generación de indicadores de negocio
- Construcción de modelos de puntuación

---

## Autor

Andrés Barrera

Proyecto de portafolio desarrollado en Power BI.
