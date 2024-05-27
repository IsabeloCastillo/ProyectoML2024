# ProyectoML2024

**Descripción del Proyecto**

Este proyecto tiene como objetivo analizar las estadísticas de jugadores de fútbol mediante técnicas de machine learning para detectar anomalías, predecir rendimientos futuros, y realizar análisis exploratorios de los datos.

![Descripción de la imagen](imagen_portada.png)

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar las estadísticas de jugadores de fútbol mediante técnicas de machine learning para detectar anomalías, predecir rendimientos futuros, y realizar análisis exploratorios de los datos.

### Pasos Realizados:

#### Carga y Preprocesamiento de Datos

1. Importación de las bibliotecas necesarias.
2. Carga de los datos desde un archivo CSV.
3. Imputación de valores faltantes y conversión de datos categóricos a numéricos.

#### Análisis Exploratorio de Datos (EDA)

1. Visualización de la distribución de variables clave.
2. Análisis de la correlación entre diferentes características.

#### Detección de Anomalías

1. Implementación de un modelo de Isolation Forest para identificar jugadores cuyas estadísticas no siguen el patrón común.
2. Visualización interactiva de los resultados para identificar jugadores excepcionales o aquellos que podrían necesitar atención especial.

#### Predicción de Rendimiento

1. Uso de un modelo de regresión lineal para predecir el rendimiento futuro de los jugadores basado en sus características actuales.
2. Evaluación del modelo mediante métricas de error cuadrático medio (MSE) y coeficiente de determinación (R²).

#### Análisis de Clusters

1. Implementación del algoritmo K-Means para agrupar jugadores con características similares.
2. Reducción de dimensionalidad mediante PCA y visualización interactiva de los clusters.

### Resultados y Visualizaciones:

#### Score vs Potencial con Anomalías

Este gráfico de dispersión muestra la relación entre el score y el potencial de los jugadores. Los puntos amarillos representan anomalías detectadas por el modelo de Isolation Forest.

#### Detección de Anomalías con PCA

Gráfico de componentes principales (PCA) para visualización de anomalías detectadas.

#### Altura vs Peso con Anomalías

Relación entre la altura y el peso de los jugadores, destacando las anomalías en amarillo.

#### Salario vs Valor con Anomalías

Análisis de la relación entre el salario y el valor de mercado de los jugadores, con anomalías destacadas.

#### Agilidad vs Fuerza con Anomalías

Gráfico de dispersión mostrando la relación entre la agilidad y la fuerza, con puntos anómalos resaltados.

### Conclusiones:

- La detección de anomalías permitió identificar jugadores excepcionales y aquellos que pueden necesitar atención adicional.
- Los modelos predictivos mostraron una alta precisión, sugiriendo que las características actuales pueden predecir efectivamente el rendimiento futuro.
- Los análisis de clusters proporcionaron una comprensión más profunda de los grupos de jugadores con características similares.

### Futuras Mejoras:

- Implementar técnicas adicionales de machine learning para mejorar la precisión de las predicciones.
- Integrar datos adicionales como lesiones, rendimiento en partidos específicos, etc.
- Realizar análisis de series temporales para evaluar el progreso de los jugadores a lo largo del tiempo.

Este proyecto proporciona una base sólida para el análisis avanzado de datos de jugadores de fútbol, ofreciendo herramientas valiosas para scouts, entrenadores y analistas deportivos.

## Descripción de las Columnas

| Columna              | Descripción                                                          |
|----------------------|----------------------------------------------------------------------|
| id_jugador           | Identificador único del jugador                                      |
| nombre               | Nombre del jugador                                                   |
| edad                 | Edad del jugador                                                     |
| score                | Calificación actual del jugador                                      |
| potencial            | Calificación máxima potencial del jugador                            |
| equipo               | Nombre del equipo del jugador                                        |
| contrato             | Duración del contrato del jugador                                    |
| altura               | Altura del jugador en centímetros                                    |
| peso                 | Peso del jugador en kilogramos                                       |
| pie_bueno            | Pie dominante del jugador                                            |
| general              | Calificación general del jugador                                     |
| puesto               | Posición principal del jugador en el campo                           |
| prog                 | Progreso del jugador                                                 |
| comienzo             | Año en que el jugador comenzó su carrera profesional                 |
| valor                | Valor de mercado del jugador en euros                                |
| salario              | Salario del jugador en euros por semana                              |
| clausula             | Cláusula de rescisión del jugador en euros                           |
| centros              | Habilidad del jugador para realizar centros                          |
| definicion           | Habilidad del jugador para definir frente al arco                    |
| precision_cabeza     | Habilidad del jugador en cabeceo                                     |
| pases_cortos         | Habilidad del jugador en pases cortos                                |
| voleas               | Habilidad del jugador en voleas                                      |
| tecnica              | Habilidad técnica general del jugador                                |
| regates              | Habilidad del jugador para regatear                                  |
| efecto               | Habilidad del jugador para darle efecto al balón                     |
| precision_faltas     | Habilidad del jugador en tiros libres                                |
| pases_largos         | Habilidad del jugador en pases largos                                |
| control_balon        | Habilidad del jugador para controlar el balón                        |
| movimiento           | Habilidad de movimiento del jugador                                  |
| aceleracion          | Habilidad del jugador para acelerar                                  |
| velocidad            | Velocidad del jugador                                                |
| agilidad             | Agilidad del jugador                                                 |
| reflejos             | Reflejos del jugador                                                 |
| equilibrio           | Equilibrio del jugador                                               |
| potencia             | Potencia del jugador                                                 |
| salto                | Habilidad del jugador para saltar                                    |
| resistencia          | Resistencia física del jugador                                       |
| fuerza               | Fuerza física del jugador                                            |
| tiros_lejanos        | Habilidad del jugador para realizar tiros lejanos                    |
| mentalidad           | Fortaleza mental del jugador                                         |
| agresividad          | Agresividad del jugador en el campo                                  |
| intercepciones       | Habilidad del jugador para interceptar el balón                      |
| vision               | Visión de juego del jugador                                          |
| penaltis             | Habilidad del jugador para lanzar penaltis                           |
| compostura           | Compostura del jugador bajo presión                                  |
| total_defensa        | Calificación total en habilidades defensivas                         |
| conciencia_defensiva | Conciencia defensiva del jugador                                     |
| robos                | Habilidad del jugador para robar el balón                            |
| entrada_agresiva     | Habilidad del jugador en entradas agresivas                          |
| total_portero        | Calificación total en habilidades de portero                         |
| estirada             | Habilidad del portero en estiradas                                   |
| paradas              | Habilidad del portero para realizar paradas                          |
| saques               | Habilidad del portero en saques                                      |
| colocacion           | Colocación del portero                                               |
| reflejos_portero     | Reflejos del portero                                                 |
| pie_malo             | Habilidad del jugador con el pie no dominante                        |
| filigranas           | Habilidad del jugador para realizar filigranas                       |
| rendimiento_ofensivo | Calificación del rendimiento ofensivo del jugador                    |
| ritmo                | Ritmo de juego del jugador                                           |
| tiros                | Habilidad del jugador para realizar tiros                            |
| pase                 | Habilidad del jugador en pases                                       |
| regates_reflejos     | Habilidad del jugador para regatear rápidamente                      |
| defensa_ritmo        | Calificación del ritmo defensivo del jugador                         |
| fisico               | Calificación física general del jugador                              |
| anomaly              | Indicador de si el jugador es una anomalía detectada (1 para sí, 0 para no) |
