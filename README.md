Casos-Prácticos-Business-Analytics

CASO 1 : ANÁLISIS DE MERCADO INMOBILIARIO PARA ALQUILER TURÍSTICO

 
    

     
     1.DISEÑO DEL PROYECTO:
       1.1 Objetivo
       1.2 Palancas
       1.3 KPIs
       1.4 Entidades y Datos
       1.5 Preguntas Semilla
    
    
    2.ANÁLISIS INICIAL DE FICHERON Y PREPARACIÓN DEL CASO:
      2.1 SetUp
      2.2 Entender los ficheros
        2.2.1 Cargar y entender los ficheros
        2.2.2 Conclusiones del análisis de los ficheros
      2.5 Creación de una BBDD

    3.CREACIÓN DE DATAMART ANALÍTICO:
      3.1 SetUp
      3.2 Importación de datos (datos internos y externos)
      3.3 Calidad de datos
        -Visión General
        -Variables y tipos
        -Análisis de Nulos y Duplicados
        -Análisis de Variables Categóricas
        -Análisis de Variables Numéricas
      3.4 DataMart analítico 
        3.4.1 Cruzar tablas apartir de Identificador Clave

    4.PREPARACIÓN DE DATOS:
      4.1 SetUp
      4.2 Carga de datos
      4.3 Preparación de las Variables
        4.3.1 Creación de KPIs a partir de las Palancas
        4.3.2 Transformación de las Variables de Análisis 
        4.3.3 Creación de variables con datos externos

    5.ANÁLISIS E INSIGHTS:
      5.1 SetUp
      5.2 Carga de datos 
      5.3 Análisis:
        5.3.1 Análisis sobre el Precio
        5.3.2 Análisis sobre la Ocupación
        5.3.3 Análisis Geográfico sobre un mapa

    6.COMUNICACIÓN DE RESULTADOS


  CASO 2 : DETECCIÓN DE INCIDENCIAS EN UNA PLANTA SOLAR:


	     
    1.DISEÑO DEL PROYECTO:
     1.1 Objetivo
     1.2 Palancas
     1.3 KPIs
     1.4 Entidades y Datos
     1.5 Preguntas Semilla

    2.CALIDAD DE DATOS Y CREACIÓN DATAMART ANALITICO:
    2.1 SetUp:
    2.2 Carga de datos:
      2.2.1 Carga de datos PLANTA1 - DATOS DE GENERACIÓN
      2.2.2 Carga de datos PLANTA1 - DATOS DEL SENSOR AMBIENTAL
      2.2.3 Carga de datos PLANTA2 - DATOS DE GENERACIÓN
      2.2.4 Carga de datos PLANTA2 - DATOS DEL SENSOR AMBIENTAL
    2.3 Calidad de datos:
      2.3.1 Calidad de Datos PLANTA 1 - Datos de Generación:
      2.3.2 Calidad de Datos PLANTA1 - Datos del Sensor Ambiental
      2.3.3 Calidad de Datos PLANTA2 - Datos de Generación
      2.3.4 Calidad de Datos PLANTA2 - Datos del Sensor Ambiental
      2.3.5 Temas pendientes de la calidad de datos para analizar posteriormente:
    2.4 Creación de DataMart Analítico:
      2.4.1 Unión de Datasets de Generación:
      2.4.2 Unión de los Datasets de Mediciones Ambientales:
      2.4.3 Creación del DataMart Analítico
    2.5 GUARDAR EL DATAMART:


    3. TRANSFORMACIÓN DE DATOS:
     3.1 SetUp
     3.2 Carga de datos
     3.3 Creación de Variables
     3.4 Reordenación del DataFrame
     3.5 DataFrame Diario

    4. ANÁLISIS E INSIGHTS:
     4.1 SetUp:
     4.2 Carga de datos:
     4.3 Análisis e Insights:
       4.3.1 Las dos plantas reciben la misma cantidad de energía solar??
       4.3.2 Cómo se relacionan las 3 Variables??
       4.3.3 Cómo se distribuye la Irradiación y la Temperatura a lo largo del día??
       4.3.4 Amabas plantas son igual de capaces de generar DC a partir de la Irrdiación??
       4.3.5 La generación es constante a lo largo de los días??
       4.3.6 La conversión de DC a AC se genera correctamente??
     4.4 Cconclusiones



  CASO 3 : OPTIMIZACIÓN DE UN ECOMMERCE



    1.DISEÑO DEL PROYECTO:
     1.1 Objetivo
     1.2 Palancas
     1.3 KPIs
     1.4 Entidades y Datos
     1.5 Preguntas Semilla

    2. CALIDAD DE DATOS Y CREACIÓN DE DATAMART ANALÍTICO:
     2.1 SET UP:
    2.2 CARGA DE DATOS:
    2.3 INTEGRACIÓN DATOS:
    2.4 CALIDAD DE DATOS:
    	2.4.1 TIPOS DE LAS VARIABLES:
  	  2.4.2NOMBRES DE LAS VARIABLES:
  	  2.4.3 ANÁLISIS DE NULOS:
  	  2.4.4 ANÁLISIS DE LAS VARIABLES NUMÉRICAS:
  	  2.4.5 ANÁLISIS DE VARIABLES CATEGÓRICAS:
  	  2.4.6 INDICE:
    2.5 TRANSFORMACIÓN DE DATOS:
  	  2.5.1 COMPONENTES DE LA FECHA:
  	  2.5.2 VARIABLES DE CALENDARIO: FESTIVOS
  	  2.5.3 INDICADORES EXÓGENOS:
    2.6 TABLÓN ANALÍTICO FINAL:

    3. ANÁLISIS E INSIGHTS:
       3.1 ENTENDIENDO LOS EVENTOS:
  	    3.1.1 COMO ESTA FUNCIONANDO EL CUSTOMER JOURNEY?
  	    3.2.1 CUANTOS PRODUCTOS SE VEN,SE AÑADEN AL CARRITO,SE ABANDONAN Y SE COMPRAN DE MEDIA EN CADA SESIÓN??
      	3.1.3 EXISTEN DIFERENCIAS ENTRE LOS EVENTOS POR HORAS??
  	    3.1.4 CUAL ES LA MEDIA DE FACTURACIÓN MENSUAL??
  	    3.1.5 CUAL ES LA TENDENCIA EN LOS ÚLTIMOS MESES??
      	3.1.6 MOMENTOS DE LA VERDAD ??
      3.2 ENTENDIENDO A LOS CLIENTES:
  	    3.2.1 COMO SE DISTRIBUYEN LOS CLIENTES EN CUANTO A GASTO??
  	    3.2.2 COMO SE DISTRIBUYEN LOS CLIENTES EN CUANTO AL NÚMERO DE COMPRAS??
  	    3.2.3 CUANTOS PRODUCTOS COMPRA UN CLIENTE DE MEDIA EN CADA COMPRA??
  	    3.2.4 QUE CLIENTES NOS HAN GENERADO MAS INGRESOS??
      	3.2.5 CUAL ES LA SUPERVIVENCIA DE LOS CLIENTES??
  	    3.2.6 CUAL ES EL LTV (LifeTimeValue) DE LOS CLIENTES??
  	    3.2.7 SOBRE QUE CLIENTES EJECUTAR LAS PRÓXIMAS CAMPAÑAS RFM??
      3.3 ENTENDIENDO LOS PRODUCTOS:
  	    3.3.1 CUALES SON LOS PRODUCTOS MAS VENDIDOS??
  	    3.3.2 HAY PRODUCTOS QUE NO SE VENDEN Y PODRIAMOS ELIMINARLOS DEL CATALOGO??
  	    3.3.3 CUAL ES LA RELACIÓN ENTRE PRECIO Y VOLUMEN DE VENTAS??
  	    3.3.4 HAY PRODUCTOS DE LOS QUE LOS CLIENTES SE ARREPIENTAN Y ELIMINEN MAS DEL CARRITO??
  	    3.3.5 CUALES SON LOS PRODUCTOS MA VISTOS?
  	    3.3.6 HAY PRODUCTOS DESEADOS PERO NO COMPRADOS??
  	    3.3.7 CONSTRUYENDO UN SISTEMA DE RECOMENDACIÓN:
  		    3.3.7.1 CREAR DATAFRAME CON KPIs DE INTERÉS:
  		    3.3.7.2 REDUCIR LA DIMENSIÓN (OPCIONAL):
  		    3.3.7.3 SELECCIONAR LA MÉTRICA DE DISTANCIA:
  		    3.3.7.4 CALCULAR LA MATRIZ ITEM-ITEM:
  		    3.3.7.5 CREAR LA LÓGICA DE PRIORIZACIÓN:
    4. CONCLUSIONES:
      4.1 BASELINE:
        4.2 Acciones de incremento de visualizaciones:
        4.3 Acciones de incremento de conversión:
        4.4 Acciones de incremento de venta cruzada:
        4.5 Acciones de incremento de frecuencia de compra:
        4.6 Acciones de fidelización de clientes:
