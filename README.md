# PI3-Data-Analyst-Matias-Naranjo-Harper

Proyecto Individual 3
En este trabajo se realizó el análisis de un dataset que posee todos los accidentes aéreos registrados en la historia.
Se comenzó por la realización de un proceso de ETL en Python utilizando principalmente la herramienta Pandas para la normalización y su posterior carga a una base de datos de MySQL.
Además de la información aportada al trabajo se agregaron los datos históricos de las acciones de las dos empresas de aviones comerciales que lideran el mercado, Boeing Co y Airbus Group SE
Una vez procesados los datos se analizaron para poder encontrar conclusiones que serán presentadas de manera oral, junto con un dashboard específico creado en PowerBI.
Diccionario de datos que se encuentran en el trabajo, según las tablas de la base de datos:
TablaAccidentes:
 - fecha: Fecha en que ocurre el accidente
 - Hora: Hora del accidente
 - Ruta Accidente: lugar donde ocurrió el accidente
 - Ruta vuelo: recorrido que debía realizar la aviación
 - origen: 
 - destino: destino final del vuelo
 - escalas: la cantidad de escalas intermedias entre el origen y el destino
 - Operador: entidad encargada del vuelo
 - Avión: modelo de la aeronave
 - registro: registro de la aeronave
 - all_aboard: la totalidad de personas la aeronave
 - Pasajeros a Bordo: 
 - crew_aboard: Tripulación a bordo
 - cantidad de fallecidos: cantidad total de fallecidos
 - passenger_fatalities: cantidad de pasajeros fallecidos
 - crew_fatalities: cantidad de tripulantes fallecidos
 - ground: cantidad de personas fallecidas en tierra por la caída de la aeronave
 - reporte: descripción del accidente
 
Boeing Co histórico: y Airbus histórico.
 - Fecha:
 - Último: precio en el que cerró la acción en el registro anterior
 - Apertura: precio al comenzar el registro
 - Máximo: precio máximo en esa ventana temporal
 - Mínimo: precio mínimo en esa ventana temporal
 - Vol.: Volúmenes de dólares que se movieron
 - % var: variación del precio máximo en comparación con la medición pasada

