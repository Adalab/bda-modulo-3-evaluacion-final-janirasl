



Este proyecto tiene como objetivo analizar el comportamiento de los clientes de un programa de fidelización, identificando patrones relevantes en sus reservas de vuelos, características demográficas y uso del sistema de puntos.
En el repositorio se encuentran una carpeta de files donde se encuentran los archivos csv,otra carpeta src donde se encuentran documentos .py y 3 jupiters en los que va cada fase ordenada.

El análisis se ha dividido en varias fases: limpieza de datos, análisis exploratorio y visualización.


 Limpieza de datos

Durante esta fase se realizaron las siguientes acciones:
	•	Eliminación de duplicados
	•	Tratamiento de valores nulos
	•	Corrección de valores negativos en la variable Salary
	•	Imputación de valores faltantes según criterios razonados
	•	Eliminación de columnas redundantes (como Country)

⸻

 Análisis exploratorio

 Variables numéricas
	•	Se analizaron medidas estadísticas (media, mediana, desviación)
	•	Se detectaron outliers, especialmente en la variable Salary
	•	Se identificaron distribuciones sesgadas en algunas variables

 Variables categóricas
	•	Predomina el nivel educativo Bachelor
	•	Mayor proporción de clientes casados
	•	Distribución de género equilibrada
	•	La tarjeta más frecuente es Star

⸻

 Correlaciones
	•	Fuerte relación entre Distance y Points Accumulated
	•	Relación positiva entre número de vuelos y puntos
	•	Variables como Salary y CLV no muestran correlaciones significativas

⸻

 Visualizaciones clave
	•	Evolución de vuelos reservados por mes (estacionalidad)
	•	Distribución de clientes por provincia
	•	Relación entre distancia y puntos acumulados
	•	Salario promedio por nivel educativo
	•	Distribución por estado civil y género
	•	Tipos de tarjeta de fidelidad

⸻

 Bonus: Educación vs vuelos

El análisis muestra que el número de vuelos reservados es muy similar entre los distintos niveles educativos, por lo que no se observa una relación clara entre educación y frecuencia de viaje.

⸻

 Conclusiones
	•	Los clientes se concentran en determinadas provincias
	•	La tarjeta Star es la más utilizada
	•	No hay diferencias relevantes en reservas según nivel educativo, género o estado civil
	•	Existe cierta estacionalidad en las reservas
	•	Factores como la actividad de vuelo y la fidelización tienen mayor impacto que variables demográficas

⸻

 Tecnologías utilizadas
	•	Python
	•	Pandas
	•	Seaborn
	•	Matplotlib
    •	CARPETA SRC con funciones y clases propias para visualizacion y analisis.

⸻

