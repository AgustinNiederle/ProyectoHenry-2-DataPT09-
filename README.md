## Proyecto Individual II (Data PartTime 09) - Agustín Niederle

 El objetivo del proyecto desarrollado es entender el funcionamiento de la tecnología de internet en Argentina, sobre todo banda ancha (velocidades de descarga de al menos 768 Kbps y velocidades de carga de al menos 200 Kbps), para así poder asesorar a una empresa interesada en ingrezar al país.

 El análisis del servicios de telecomunicaciones en Argentinan donde se registran más de 60 millones de conexiones a internet, realizado con los datos obternidos de ENACOM durante un período de casi 10 años (desde 2014 al primer trimestre de 2024). Esto permite identificar tendencias y realidades del sector a nivel nacional. Si bien el análisis se enfoca en el acceso a internet, también se toma en cuenta al resto de los servicios de comunicación.

### Detalles de archivos entregados:

    Primero se recomienda leer este archivo, el README del repositorio.
    
    También encontramos un notebook de Jupyter Notebook llamado EDA. 
    Se anexa una carpeta con las imágenes más relevantes de dicho EDA. 
    
    Finalmente, el Dashboard que se usará en la reunión final para compartir los insights y las recomendaciones a las que se llegaron. 

### Reporte del EDA:

    En el notebook EDA, se encuentra el primer análisis explratorio realizado a los datos descargados de ENACOM (www.datosmundial.com) por sugerencia la entidad interesada.
    Prieramente, se puede ver el proceso de sepración de las distintas hojas del archivo de Excel descargado, en los diferentes dataframes que se usan para realizar el análisis exploratorio de los datos usando las librerías de python: Pandas, Numpy, Matplotlib, Seaborn y Prophet.
    
    En la primera etapa de exploración, se realiza una verficicación de los datos; se revisan los nulos, los posibles outliers y valores repetidos. 
    En la segunda etapa, se utilizaron diferentes tipos de gráficos, con el objetivo de entender la situación de la tecnología en las Provincias de Argentina a lo largo de los últimos diez años.

    Hay tecnologías como Dial Up o Wireless que ya casi no tiene presencia dentro de las tecnologías usadas. Esto podría deberse a su baja velocidad y a la aparición de Fibra Óptica, que tiene una clara tendencia de crecimiento en los años posteriores a 2017.

    Por último, pensando específicamente en recomendar acciones para instalar Banda Ancha, se analizan particularmente las tecnologías Cablemodem y Fibra óptica, para así entender la proyección de la tecnología, las oportunidades que podrían ofrecer. Finalmente se usa un modelo de Machile Learning para predecir la demanda de las mismas en el próximo año. 


### Reporte de análisis en base al dashboard:

    Según lo observado en el EDA, y por la fuente XX (o por casos similares) podemos anticipar que la tecnología Cablemodem migrará por Fibra óptica al menos parcialmente. Esto permite tener en cuenta a los posibles usuarios actuales de Cablemodem, además de los de Fibra óptica, y proyectar capturar esa porción de la población que aún no ha accedido a esta tecnología en provincias como XX, XX y xx, sin contar que con una camapaña adecuada, parte de los usuarios de Fibra óptica podrías migrar a la empresa si ofrece comodidad en el proceso y mejores beneficios.

### Análisis y funcionalidad de los KPIs sugeridos.

    KPI solicitado: "Acceso por cada 100 hogares" de varios años (diferenciados por trimestres). El KPI busca controlar el objetivo de  aumento en un 2% del acceso al servicio de internet por trimestre, cada 100 hogares, por provincia. 

    KPI 1: Este KPI compara el acceso a internet entre diferentes provincias o regiones. Sirve para plantear un aumento en la conectividad por parte de la población de todo el país, no solo de la región cercana a Capital Federal. El valor de referencia para los próximos años será la actualidad de Buenos Aires, con el 92% de conexión por Habitantes en 2024. 

    KPI 2: Plantear un aumento del 20% en el servicio de Fibra óptica cada año, o de un 5% por trimestre.

### Insights:
    
    Queda en evidencia una desigualdad en oportunidad de acceso a tecnología y sus beneficios por parte del interior del Pais. Esto podría deberse a falta de infraestructura o de inversiones hasta la fecha. Puede recomendarse invertir en las ciudades con menos accesos, no solo para llegar a esa porción de la población que aun no ha accedido.

    Tanto cablemodem como Fibra óptica tienen un ascenso muy marcado en los últimos años, lo que indica que son tecnologías en crecimiento y por eso, recomendables para invertir.
