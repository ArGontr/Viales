#### Contexto

Esta aplicación surge como una primera aproximación a los incidentes de tránsito. 
Fue creada debido al morbo que representa el hecho de que en la nueva administración subiera el número de incidentes con al menos un lesionado; y al parecer, también el número de decesos por incidentes de tránsito, aunque esta última cifra no puede
ser contemplada en esta app (aún).

#### Notas metodológicas: 

Estos datos deben interpretarse con cautela. Los hechos se refieren a incidentes de tránsito y no al número de personas involucaradas.
Las categorías de lesionado fueron construidas por mi con base a la variable "incidente_c4" y en buena medida, se adivinó qué inciedentes tenían o no lesionados, ya que no existe un diccionario ofical de correspondncias. En esa medida, los incidentes marcados como "Con lesionado" deben leerse como cifras mínimas, ya que muchos incidentes por su categorización no son explícitos sobre la existencia de lesionados. Como ejemplo, de la categoría 
"Detención ciudadana-Accidente automoilistico" no  puede desprenderse si hay lesionados o no, de ahí que fuera agrupada como "Sin estatus lesionado".

Se utilizaron como proxy del momento de ocurrencia las variables llamadas "fecha_creación" y "hora_creación", Aunque en realidad son fechas posteriores en un rango de entre unos munutos y un par de horas. No obstante, ofrecen la mejor aproximación disponible a la ocurrencia del evento.


#### Contacto

Este es un proyecto que pretende cambiar y adaptarse para poder visualizar las tendencias de la ocurrencia de estos incidentes de la mejor manera. 
Son bienvenidas sugerencias. Pueden contactarme en [twitter](https://twitter.com/Ar_GonTr)

También pueden checar un proyecto que estoy iniciando de tutoriales, y donde posteriormente subiré el código que creó esta app [en mi página en wix:](https://tcargon.wixsite.com/website)


#### Créditos

Esta aplicación debe mucho al ya célebre [shiny superZIP example.](http://shiny.rstudio.com/gallery/superzip-example.html) y a una impresionante pero menos conocida aplicación que muestra [tendencias electorales en Reino Unido](https://cultureofinsight.shinyapps.io/dotmap/).
Un agradecimiento especial a los bebés R, que hicieron valiosas sugerencias y corrección de estilo.
