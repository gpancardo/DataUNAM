# DATA UNAM 🎓🇲🇽📚
![alt text](Biblioteca_central_de_la_UNAM.jpg "Biblioteca central de la UNAM")
__"Biblioteca central de la UNAM" | Gomnrz | [Wikimedia, mayo 2025](https://commons.wikimedia.org/wiki/File:Biblioteca_central_de_la_UNAM.jpg) |  Creative Commons Attribution 4.0 International__

## Objetivo 🎯
**Preparar un dataset proveniente de __[Data Mexico - Vizbuilder](https://www.economia.gob.mx/datamexico/es/vizbuilder)__ sobre la Universidad Nacional Autónoma de México para un dashboard en Looker Studio.**

## [Dataset resultante ✈️](https://github.com/gpancardo/DataUNAM/blob/main/unamLimpio.csv) 

## Paso a paso 🚦
1. **Descargar la información desde Vizbuilder con consulta personalizada (se puede reemplazar por llamada a API con cambios a limpieza.ipynb).**
2. **Importar dataset como dataframe con pandas:** El archivo se abre como dataframe y se revisan los encabezados para estar seguros de que no hayan habido cambios mayores en las etiquetas de columna o en la estructura de las entradas.
3. **Descartar columnas innecesarias:** Algunas columnas del archivo como los identificadores (excepto de área) no son relevantes para el dashboard. Vamos a descartar esas columnas para reducir dataset.
4. **Sustituir ubicaciones por siglas:** Las ubicaciones (facultades, campi, institutos, etc.) tienen nombres largos que pueden ser difíciles de leer en el dashboard. Hay ubicaciones duplicadas que se asignan a las mismas siglas en el nuevo dataset.
5. **Simplificar títulos:** Los nombres de título incluyen el grado o son programas derivados. El dataset resultante tiene nombres más cortos para que el dashboard sea legible.
6. **Guardar dataframe modificado como archivo CSV.**
7. **Importar en Looker Studio.**

## Resultados 📊
### Reporte  - pendiente
### Dashboard - pendiente

## Fuentes 📖