# Datos Historicos de Presas en Mexico

Datos obtenidos del Sistema de Información Hidrológica de la Comisión Nacional del Agua (CONAGUA) de Mexico (https://sih.conagua.gob.mx).

## Metodologia

Los datos fueron descargados de `ftp://sih.conagua.gob.mx` y luego un script fue usado para generar un archivo (.csv) para cada dimension. Las credenciales para la conexion FTP pueden ser obtenidas de https://sih.conagua.gob.mx

Archivo                                 | Descripción
----------------------------------------|-----------------
elevacion.csv                           | Elevacion(msnm)
almacenamiento.csv                      | Almacenamiento(hm³)
area.csv                                | Area(ha)
extracciones_por_obra_de_toma.csv       | Extracciones por Obra de Toma(m³/s)
extracciones_por_vertedor.csv           | Extracciones por Vertedor(m³/s)
evaporacion.csv                         | Evaporación(mm)
precipitacion.csv                       | Precipitación(mm)
