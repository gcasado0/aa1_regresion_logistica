"En la sección  "Análisis y decisión sobre datos faltantes" explicar en base a que criterio se eliminan las clumnas por tener un 11% de datos faltantes, y porque no se imputaron. Explicar"

- Solo eliminamos las columnas con un % de faltantes mayor o cercano al 40% dado que una imputacion por la media o mediana, alteraria la distribucion original, agregando ruido o sesgo al modelo.

Respecto de Evaporation', 'Sunshine', 'Cloud3pm', 'Cloud9am' se puede ver que hay localidades que no tienen ese dato en absoluto y otras que si lo tienen pero en forma parcial.


"Aclarar que las columnas 'Date', 'Location', 'Latitud', 'Longitud' solo sirven para el EDA y no para el entrenamiento. Porque no se explica porque se eliminan para el modelo."

De la columan Date nos quedamos con el Mes
De la columna Location nos quedamos con la Region

Para seguir investigando:

Se podria inputar la mediana por localidad o por tiempo 