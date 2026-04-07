# Analisis de Misiones Espaciales (1957 - 2022)
## Descripción
El presente proyecto analiza misiones espaciales para estudiar costos, resultados y evolución del sector.
Fue desarrollado en el marco de un curso de análisis de datos, incorporando exploración y conclusiones propias.
La industria aeroespacial representa uno de los mayores referentes en materia de eficiencia y gestión del riesgo, es por ello, que he seleccionado un dataset que documenta las misiones espaciales desde el inicio de la carrera espacial hasta la actualidad.

El objetivo es analizar la evolución del sector espacial a lo largo del tiempo, enfocandose en tres pilares clave:

1.  ¿Se ha vuelto el acceso al espacio más económico con el desarrollo de nuevas tecnologías?
2.  ¿Existe una relacion entre el presupuesto invertido y el resultado de la misión?
3. ¿Existe un cambio en la estructura del sector espacial en términos de participación pública y privada?
## Dataset
*   Link: https://mavenanalytics.io/data-playground/space-missions
## Glorasio: 
* **Company**: Compañía responsable
* **Location**: Ubicación del despegue
* **Date**: Fecha del despegue
* **Time**: Hora del despegue (UTC)
* **Rocket**: Nombre del cohete utilizado
* **Mission**: Nombre de la misión.
* **RocketStatus**: Estado del cohete a Agosto de 2022 (Activo/Inactivo)
* **Price**: Costo del cohete en millones de dolares
* **MissionStatus**: Estado de la mision (Éxito, Fracaso, Fracaso parcial, Fracaso en el pre-lanzamiento)

## Tecnologías:
*   Python (pandas, nunpy, plotly)
*   Jupyter Notebook
*   Microsoft Power BI

## Resultados
### Conclusión del proceso de análisis
Durante el desarrollo del trabajo se avanzó desde una exploración inicial del dataset hacia un análisis más estructurado, combinando limpieza y formateo de datos combinando visualizaciones para responder las preguntas planteadas.
Algunos de los desafíos que se presentaron:

* Valores faltantes en la columna Price
* Formatos inconsistentes en datos numéricos
* Existencia de outliers que distorsionaban métricas

Como se abordaron estos desafíos:
*   Limpieza y filtrado de datos
*   Uso de métricas más adecuadas como la mediana
* Análisis segmentado por características para explotar mejor la información.
### Conclusión general del tema abordado:
El análisis permitió confirmar que el acceso al espacio se ha vuelto más accesible en términos económicos y más abierto a la participacion del sector, generando un entorno más competitivo frente a las grandes agencias gubernamentales. Sin embargo, el éxito sigue siendo un desafío que no depende únicamente del nivel de inversión.
##Autor
*    Tobias Martinez - [Linkedin] www.linkedin.com/in/tobiasmartinez
