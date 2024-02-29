# Proyecto de Análisis de Series de Tiempo y Predicción con ARIMA

Este proyecto fue desarrollado como parte de la materia de Estadística Actuarial en la Universidad de Buenos Aires. La primera parte del trabajo consiste es realizar un análisis de series de tiempo utilizando el modelo ARIMA (Autoregressive Integrated Moving Average) y llevar a cabo predicciones sobre los datos estudiados. La segunda parte es simulación.

## Contenido

1. **Introducción**
    El presente trabajo práctico constituye el cierre del curso de Estadística Actuarial. La finalidad
    es articular los conceptos teóricos estudiados en las clases con una aplicación práctica
    mediante a utilización del lenguaje de programación utilizado en el curso.
    A lo largo del curso, se han abordado diferentes temas referidos al análisis de los datos,
    su manejo y su explotación. El presente trabajo práctico buscará combinar las capacidades
    aprendidas por los estudiantes en lo que respecta a programación y aquellas capacidades
    analíticas, lógicas y resolutivas; con el objetivo último de generar un marco de trabajo que
    permita una comprensión más abarcativa de los temas de la materia.
   
2. **Estructura del Proyecto**
    a) Series Temporales: El trabajo deberá presentarse en formato de informe y deberá
    incluir los resultados obtenidos, las conclusiones y las limitaciones del análisis realizado.
    El informe deberá estar escrito en no más de tres carillas de Word y deberá incluir los
    gráficos. Además, se deberá incluir el código utilizado en el archivo .ipynb.
    b) Simulación: Se deberá entregar el archivo del notebook en el que se realizó el trabajo
    de forma que pueda ser ejecutado de forma simple por el equipo docente. Debe

3. **Análisis de Series de Tiempo**
    Usted es un Analista Cuantitativo de Inversiones que necesita saber el precio del petróleo
    en el próximo año, utilizando el índice Brent desde el año 2015, para saber si es conveniente
    o no la inversión en acciones de empresas petroleras. Para ello, decide hacer la predicción
    a futuro utilizando solamente la serie temporal del índice Brent y sus conocimientos en
    estadística aplicada.
    El objetivo de este trabajo práctico es realizar un análisis de la serie temporal del índice
    Brent y desarrollar un modelo ARIMA que permita realizar predicciones precisas del comportamiento
    futuro de la serie bajo los siguientes lineamientos:
    a) Búsqueda y selección de la serie temporal: Se deberá seleccionar la serie temporal de
    alguna base de datos pública (Banco Mundial, Yahoo Finance), cargarla en Python,
    limpiar el dataset en caso de ser necesario, y correr las funciones de estadística descriptiva
    de Pandas para comenzar a tener una comprensión de los datos seleccionados.
    b) Análisis de la serie temporal: Se deberá realizar un análisis exhaustivo de la serie
    temporal seleccionada, incluyendo:
    • Exploración gráfica: Se deberán desarrollar gráficos de la serie temporal que
    permitan identificar patrones y tendencias en la serie, así como también identificar
    la presencia de posibles valores atípicos o cambios estructurales en la serie.
    • Verificación de estacionariedad y estacionalidad: Se deberá verificar la estacionariedad
    y estacionalidad de la serie. Todos los test vistos en clase deben ser aplicados
    para el estudio certero de la serie (Jarque-Bera, Durbin-Watson, Dickey Fuller)
    junto con sus respectivas conclusiones.
    • Funciones de autocorrelación y autocorrelación parcial: Se deberán desarrollar
    gráficos de la función de autocorrelación y autocorrelación parcial para la serie
    temporal del índice Brent. Estos gráficos permitirán identificar posibles modelos
    ARIMA que expliquen la variabilidad en la serie.
    c) Selección del modelo: Se deberá seleccionar un modelo ARMA o ARIMA que mejor se
    ajuste a la serie temporal, utilizando criterios de información como el AIC o el BIC y el
    estudio realizado previamente. Se deberá justificar la elección del modelo seleccionado
    y describir sus propiedades. También se deben enumerar las limitaciones que tiene el
    dado los resultados obtenidos en su estudio.
    d) Predicciones con el modelo seleccionado: Utilizando el modelo seleccionado, se deberán
    realizar predicciones del comportamiento de la serie temporal en un horizonte temporal
    futuro de un año. Se deberá evaluar la precisión de las predicciones mediante métricas
    como el error cuadrático medio o el error absoluto medio.
    e) Presentación de resultados: El trabajo deberá presentarse en formato de informe y
    deberá incluir los resultados obtenidos, las conclusiones y las limitaciones del análisis
   
4. **Modelo ARIMA**
    A. Definición:
    ARIMA, que significa "Autoregressive Integrated Moving Average", es un modelo estadístico utilizado para analizar y predecir series de tiempo.
    B. Componentes:

    Auto-regresivo (AR): Representa la relación lineal entre la observación actual y las observaciones pasadas con un término de error.
    Media móvil (MA): Involucra el término de error actual y los términos de error pasados para modelar la relación entre la observación actual y los errores pasados.
    Diferenciación Integrada (I): Refleja el número de diferenciaciones necesarias para hacer estacionaria la serie de tiempo, es decir, para eliminar tendencias y estacionalidades.
    C. Orden del Modelo:

    ARIMA se denota como ARIMA(p, d, q), donde:
    p: Orden del componente AR.
    d: Orden de diferenciación.
    q: Orden del componente MA.
    D. Identificación de Parámetros:

    Determinar los valores óptimos de p, d, y q mediante análisis visual de la serie temporal, funciones de autocorrelación (ACF) y autocorrelación parcial (PACF), y pruebas estadísticas.
    E. Proceso de Construcción del Modelo:

    Preprocesamiento: Diferenciación para hacer estacionaria la serie de tiempo.
    Identificación y Estimación: Seleccionar los valores de p, d, y q.
    Ajuste del Modelo: Aplicar el modelo ARIMA a los datos.
    Diagnóstico: Evaluar la calidad del ajuste mediante pruebas estadísticas y análisis de residuos.
    F. Pronóstico:

    Utilizar el modelo ARIMA ajustado para realizar predicciones futuras basadas en la tendencia y la variabilidad capturadas por los componentes AR e MA.
    G. Aplicaciones:

    ARIMA se utiliza en diversas áreas como finanzas, economía, climatología, entre otras, para prever patrones y tendencias en series temporales.
    H. Consideraciones:

    La calidad del modelo ARIMA depende de la correcta identificación de los parámetros y la estacionarización de la serie de tiempo.
    I. Herramientas y Bibliotecas:

    En Python, bibliotecas como statsmodels se utilizan para implementar y ajustar modelos ARIMA a datos de series temporales.
    J. Limitaciones:

    ARIMA asume que la serie temporal es estacionaria y puede no funcionar eficazmente en datos no estacionarios sin adecuada diferenciación.
    Esta descripción proporciona una visión general del modelo ARIMA, su estructura y su aplicación en el análisis y pronóstico de series temporales.
     
5. **Simulación en Python**
 Leer consignas en PDF

