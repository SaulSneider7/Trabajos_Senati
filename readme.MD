# Ejercicio Práctico: Análisis de Datos de Empleados con Pandas
Eres un analista de datos en una empresa y te han entregado un archivo CSV llamado empleados.csv con información sobre los empleados. Este archivo contiene más de 50 registros y varias columnas con datos relevantes como edad, salario, departamento, desempeño, entre otros. Tu tarea es analizar estos datos utilizando Pandas para responder preguntas clave sobre los empleados y su rendimiento.

## Cargar y explorar los datos
- Carga el archivo CSV empleados.csv en un DataFrame de Pandas.
- Muestra los primeros 10 registros del DataFrame para conocer la estructura de los datos.
- Obtén un resumen estadístico de las columnas numéricas (mínimos, máximos, promedios, etc.).

## Filtrar y analizar información clave
- Filtra y muestra los empleados cuyo salario sea mayor a 5000.
- Crea una nueva columna llamada Alto_Desempeño que indique True si el empleado tiene una Evaluación de Desempeño superior a 4, de lo contrario, debe ser False.
- Elimina la columna Bono_Anual del DataFrame, ya que la empresa ha decidido no utilizar esta información.
- Calcula el total de salarios por cada departamento y muestra los resultados.

## Encontrar empleados específicos
- Encuentra al empleado más joven de la empresa y muestra sus datos completos.
- Encuentra al empleado con más años de experiencia en la empresa y muestra sus datos completos.

## Manejo de valores nulos y exportación
- Si hay valores faltantes en la columna Proyectos_Completados, reemplázalos con el promedio de esa columna.
- Guarda el DataFrame modificado en un nuevo archivo CSV llamado empleados_modificado.csv.