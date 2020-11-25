 TP---Properati v 0.17 (Actualemnte: graficando los scores de los modelos)(Idea: replicar con Statsmodels)

 Análisis de un DataFrame de datos de propiedades inmobiliarias argentinas del 2003 para predecir el Precio(USD)/m^2 de la propiedad.
 
 En la primer parte se utilizan expresiones regulares para llenar valores faltantes y luego se eliminan outliers. 

 En la segunda parte se utilizan modelos de regresiones lineales con y sin regularización de Scikit-Learn: (LassoCV,RidgeCV,ElasticNet,LinearRegression) para predecir el Precio(USD)/m^2 de la propiedad.
 
 Se grafica información estadística usando Seaborn, Matplotlib y YellowBrick.

