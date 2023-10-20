#  Data analytics

Este proyecto se llevó a cabo con el rol de Analista de Datos desde SoyHenry para la Organización de Aviación Civil Internacional (OACI),

con el objetivo principal de realizar un análisis de datos exhaustivo para investigar los accidentes ocurridos desde principios del siglo XX 

en el ámbito de la aviación.

#  Tecnologías utilizadas

Se utilizó Jupyter Notebook con las librerías Seaborn y Matplotlib para explorar visualmente los datos [Haz clic aquí para ver el archivo](https://github.com/lorenrave/Data_analytics_project_/blob/main/EDA.ipynb).

Donde se generaron gráficos, histogramas y visualizaciones pertinentes para entender mejor la distribución y las tendencias en los datos.

También se crearon Visualizaciones Interactivas en Power BI para proporcionar una vista más dinámica y accesible de los resultados.

[Para poder ver el Dashboard realizado con Power BI haz clic en este enlace](https://github.com/lorenrave/Data_analytics_project_/blob/main/accidentes_analytics.pbix)

## Procesamiento de los datos: ETL


-Importación del dataset de AccidentesAviones.

-Reasignación de nombres de columna y modificación para la prolijidad.

-Transformación de fecha y hora al formato correspondiente.

-Modificación de los campos donde había valores '?' por NaN.

-Búsqueda de valores faltantes.


## Análisis:


-Identificamos variables categóricas y cuantitativas y las analizamos.

-Ouliers: Se identificó un caso excepcional en el que más de 600 pasajeros estuvieron involucrados en una colisión entre dos aviones grandes. 

Además, se identificaron dos eventos extraordinarios en los que más de 2700 personas murieron en tierra, que correspondieron a los atentados

en las Torres Gemelas de Nueva York en 2001. Dado que estos casos excepcionales reflejaban situaciones de la vida real, 

no se tomaron medidas adicionales en relación con los outliers.
          
-Los meses con más cantidad de fallecidos fueron Diciembre y Enero.

-Se evaluó la cantidad de accidentes por año siendo la más alta 1946 y en 1989 comienza a decaer significativamente la cantidad de accidentes aéreos.

-La cantidad de fallecidos en accidentes aéreos frecuenta entre 1, 2 y 3 víctimas ya que la mayoría de accidentes fueron de vuelos de prueba/entrenamiento.

-Se realizó el ranking de aerolineas con mas mortalidad y se identificaron cambios a traves del tiempo ya que reforzaron sus medidas de seguridad.

-Se identificó la relación entre fallecidos y sobrevivientes y como resultado, hubo más fallecidos que sobrevivientes.


 ## Conclusiones:
 
![Imagen sobre el dashboard](https://github.com/lorenrave/Data_analytics_project_/blob/main/data/Dashboard.analytics.jpg)


 
  A lo largo de los años, hemos observado una marcada disminución en la frecuencia de accidentes aéreos, 
  
  lo cuál se ha visto reflejado especialmente en el año 2017. Esto se debe, en gran parte, a los avances tecnológicos en la industria de la aviación.
  
  De hecho, el año 2017 se destacó como el más seguro en la historia de la aviación, tanto en términos del número de accidentes como en la cantidad de víctimas,
  
  consolidando así la idea de que viajar en avión es cada vez más seguro.
  
  También se puede concluir que a medida que aumenta el número de pasajeros, la incidencia de muertes tiende a disminuir. A partir de este análisis, podemos afirmar 
  
  que el viaje en avión se ha vuelto más seguro en la actualidad.
