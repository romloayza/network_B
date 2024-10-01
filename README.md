# Análisis de Redes de Empresas Contratistas en Municipalidades Distritales de Lima Departamental

Este proyecto tiene como objetivo analizar las relaciones entre empresas contratistas que han obtenido obras públicas en los distintos distritos de Lima departamental. A través de la creación de una matriz, se mide la frecuencia con la que diferentes empresas coincidieron al ganar licitaciones en los mismos distritos.

## Datos
Los datos se han extraído del portal de SEACE (Sistema Electrónico de Contrataciones del Estado), donde se encuentran los registros públicos de todas las contrataciones adjudicadas por las municipalidades distritales de Lima.

- 🔗https://prod2.seace.gob.pe/seacebus-uiwd-pub/buscadorPublico/buscadorPublico.xhtml

## Metodología
1. **Extracción de datos:** Los datos se obtienen del portal SEACE mediante consultas públicas.
2. **Procesamiento de datos:** Se crea una matriz de coincidencias en la cual las celdas o intersecciones representan la frecuencia con la que dos empresas diferentes ganaron una licitación en el mismo distrito.
3. **Visualización de redes:** Se generan visualizaciones que muestran las interconexiones entre empresas en base a su actividad conjunta en los distritos.

## Resultados
https://romloayza.github.io/network_B/

### Interpretación
Se encontraron 444 empresas contratistas, en donde se encontraron 21 componentes de nodos, que se conectan entre sí, pero no con otros componentes. Respecto al componente más grande, está compuesto por 390 nodos. Sin embargo, hay presencia de 3 nodos aislados. Entre las empresas más influyentes o las que tienen una mayor centralidad, se encuentran Espinar S.A.C., COPER, etc. 
