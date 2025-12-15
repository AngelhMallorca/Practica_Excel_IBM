# Practica_Excel_IBM
Practica_Excel_dashboard_caso_IBM

Objetivo
El objetivo de la Practica es analizar la rotación de empleados en la Multinacional IBM a lo largo de un periodo de un año

Origen de los datos
La práctica usa datos obtenidos de la siguiente Base de datos de Kaggle;
https://www.kaggle.com/code/vincentlugat/ibm-attrition-analysis-and-prediction/notebook

EDA

-El archivo original de nombre "WA_Fn-UseC_-HR-Employee-Attrition" se descargó en formato CSV

-A continuación, los datos se cargaron en el documento de Excel “IBM attrition”, el cual cuenta con 37 columnas y 1,470 filas en la pestaña “Raw data”

-Como parte del EDA se confirmó que en la base de datos no había valores duplicados, y todas las columnas tenían el formato adecuado, “numérico”, “texto” etc. 

-Con el fin de facilitar el análisis cuantitativo, algunas columnas que estaban en formato texto "Job satisfaction", "Overtime worked" fuerpm transformadas a formato numérico sustituyendo categorías, “low”, “médium” por números “1”, “2” etc.

-A modo exploratorio, dada el alto número de variables a analizar, lleve a cabo un Análisis de regresión múltiple con el fin de poder medir el grado de relación de distintas variables el nivel de rotación, los resultados se pueden encontrar en la pestaña "Multiple regression analysis"

-Finalmente se creo la pestaña “Analisys sheet”, donde se han construido múltiples tablas dinámicas, 13, con el fin de poder- analizar la relación entre las distintas variables y la rotación de empleados. 

Conclusiones

-Con el fin de ilustrar los resultados de los análisis se a creado la pestaña “Dashboard”  

-El análisis de Rotación de empleados muestra dos “clusters” diferenciados de tipologías de empleados con una rotación más alta que la media que se sitúa en un 16%

Por una parte, están los empleados en roles “Junior” con una rotación del 25% las características de dicho grupo son;

	-Menos de 4 años trabajados en la empresa
	
	-Rangos de salarios más bajos, menores a 3k brutos/mes
    
	-Puestos Junior como “Sales Executive”, “Laboratory Technitian”

Por otra parte, están los empleados en roles “Super Senior” con una rotación del 24% las características de dicho grupo son;

	-Mas de 30-35 años trabajados en la empresa
	
	-Rangos de salarios top,por encima de 10k brutos/mes
  
    -Puestos directivos como “Manufactoring Director”, “Research Director”

Se puede concluir que la rotación afecta de manera más elevada a empleados en los dos extremos de la organización, por una parte, a los “Junior” que tras un periodo menor a cuatro años salen de la organización buscando oportunidades en otras empresas Y a los “Super Senior” que tras décadas en la empresa salen bien a Jubilarse o a asumir otros retos directivos en otras empresas. 

