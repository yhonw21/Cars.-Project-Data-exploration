# proyecto_platzi

1.Measures of central tendency
El código de Python muestra el cálculo de dos medidas de tendencia central para una columna llamada "price_usd" en un dataframe llamado "df". La primera medida es la media, que se puede calcular usando el método ".mean()". La segunda medida es la mediana, que se puede calcular usando el método ".median()".
El resultado de la media es 6639.971021255613 y la mediana es 4800.0. Ambas medidas brindan información sobre el valor central de los datos en la columna "price_usd". La media es una medida de tendencia central que representa el valor promedio de los datos y la mediana es la medida que divide los datos en dos partes iguales, con la mitad de los valores por debajo de ella y la otra mitad por encima.
Además, se genera un histograma para visualizar la distribución de los valores en la columna "price_usd". El histograma se crea usando el método ".plot.hist (bins = 20)" y se especifica un número de 20 divisiones o "bins". El histograma muestra la frecuencia de los valores en diferentes intervalos y es útil para entender la distribución de los datos.


1.1. import library seaborn / 1.2. group by engine_type / 1.3. individual analysis of the audi q7 model

El siguiente código importa la librería "seaborn" como "sns". Luego, se utiliza la función "displot" de seaborn para crear dos gráficos de distribución.
El primer gráfico es un gráfico de distribución univariado, que muestra la distribución de los valores de la columna "price_usd". Además, se utiliza la opción "hue" para diferenciar los valores según la columna "manufacturer_name".
El segundo gráfico es similar al primero, pero utiliza la opción "multiple = 'stack'" para apilar las distribuciones de los valores según la columna "engine_type".
El siguiente comando de código utiliza el método ".groupby" para agrupar los datos según la columna "engine_type" y calcular la cantidad de valores en cada grupo usando el método "count".
El último comando crea una nueva dataframe llamada "Q7_df" que contiene solo los registros donde el "manufacturer_name" es "Audi" y el "model_name" es "Q7". Luego, se utiliza la función "histplot" de seaborn para crear un histograma que muestra la distribución de los valores de la columna "price_usd" para los registros en "Q7_df". Además, se utiliza la opción "hue" para diferenciar los valores según la columna "year_produced".
En resumen, el código crea gráficos para visualizar la distribución de los valores de una o más columnas, y utiliza la función "groupby" para agrupar y contar los valores de una columna.




