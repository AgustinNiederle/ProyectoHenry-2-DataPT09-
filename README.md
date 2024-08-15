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

    Según lo observado en el EDA podemos anticipar que la tecnología Cablemodem migrará por Fibra óptica al menos parcialmente. Esto permite tener en cuenta a los posibles usuarios actuales de Cablemodem, además de los de Fibra óptica, y proyectar capturar esa porción de la población que aún no ha accedido a esta tecnología en provincias como Catamarca, Jujuy o Salta, sin contar que con una camapaña adecuada, parte de los usuarios de Fibra óptica podrían migrar a la empresa si ofrece comodidad en el proceso y mejores beneficios.

### Análisis y funcionalidad de los KPIs sugeridos.

    KPI solicitado: "Acceso por cada 100 hogares" de varios años (diferenciados por trimestres). El KPI busca controlar el objetivo de  aumento en un 2% del acceso al servicio de internet por trimestre, cada 100 hogares, por provincia. 

    KPI 1: Propone un incremento en el ingreso trimestral del 25%, lo que implica un retorno de la inversión del 100% anual. Este valor se propone ante el análisis de los ingresos y se considera posible.

    KPI 2: Plantea el incremento trimestral de accesos a internet sobre el total de habitantes en Argentina, planteando un valor equivalente a 50%. 

    KPI 3: Plantear un aumento del 20% en el servicio de Fibra óptica cada año, o de un 5% por trimestre.
    
    KPI 4: por tasa de conversión (conversion rate) que mide la cantidad de clientes que pasan de otras tecnologías (como Cablemodem, ADSL, etc.) a Fibra Óptica por        año. Este dato no lo tenemos, pero a los fines de este análisis podríamos inferir/suponer que hay recambio de tecnologìa por los datos de años anteriores mostrando     la caida en ADSL, simultanea al ascenso de Fibra Óptica y Cablemodem).

### Insights:
    
    Queda en evidencia una desigualdad en oportunidad de acceso a tecnología y sus beneficios por parte del interior del Pais. Esto podría deberse a falta de infraestructura o de inversiones hasta la fecha. Puede recomendarse invertir en las ciudades con menos accesos, no solo para llegar a esa porción de la población que aun no ha accedido.

    Tanto cablemodem como Fibra óptica tienen un ascenso muy marcado en los últimos años, lo que indica que son tecnologías en crecimiento y por eso, recomendables para invertir.
