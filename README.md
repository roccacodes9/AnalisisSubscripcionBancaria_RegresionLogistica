Análisis de Regresión Logística de Datos Bancarios
Contenido

Este repositorio contiene un script en Python que realiza un análisis de regresión logística utilizando datos bancarios. El análisis se centra en predecir si un cliente responderá positivamente a una oferta basándose en la duración de la interacción con el cliente.
Requisitos

    Python 3.x
    Pandas
    Statsmodels
    Seaborn
    Matplotlib (para visualización, aunque no se utiliza en este script)

Detalles

El script realiza las siguientes acciones:

    Carga un conjunto de datos bancarios desde un archivo CSV.
    Elimina la columna de índice que viene con los datos.
    Mapea los valores 'yes' a 1 y 'no' a 0 en la columna 'y' que indica si el cliente respondió positivamente.
    Selecciona la duración como variable independiente y 'y' como variable dependiente.
    Ajusta un modelo de regresión logística utilizando el método de Máxima Verosimilitud.
    Imprime un resumen de los resultados del modelo, incluyendo el coeficiente de la duración y la constante.

Resultado

El script proporciona un análisis detallado de la relación entre la duración de la interacción con el cliente y la probabilidad de que el cliente responda positivamente a una oferta. Los resultados incluyen el coeficiente de la duración y la constante del modelo de regresión logística, así como estadísticas de ajuste del modelo. Esto permite una comprensión más profunda de cómo la duración de la interacción afecta las respuestas de los clientes en el contexto bancario.
