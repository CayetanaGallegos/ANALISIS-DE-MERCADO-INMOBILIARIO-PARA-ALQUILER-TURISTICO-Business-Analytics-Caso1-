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
    
     2.1 SetUp
     2.2 Carga de datos
     2.3 Integración de datos
     2.4 Calidad de datos
    	2.4.1 Tipos de las Variables
  	2.4.2 Nombres de las Variables
  	2.4.3 Análisis de Nuls
  	2.4.4 Análisis de las Variables Numéricas
  	2.4.5 Análisis de las Variables Categóricas
  	2.4.6 Índice
     2.5 Transformación de datos
  	2.5.1 Componentes de la Fecha
  	2.5.2 Variables de Calendario: Festivos
  	2.5.3 Indicadores Exógenos
     2.6 Tablón Analítico Final

    3. ANÁLISIS E INSIGHTS:
    
    	3.1 Entendiendo los EVENTOS:
  	    3.1.1 Cómo esta funcionando el Customer Journey?
  	    3.1.2 Cuantos productos se ven,se añaden al carrito,se abandonan y se compran de media en cada sesión??
      	    3.1.3 Existen diferencias entre los eventos por horas??
  	    3.1.4 Cual es la media de facturación mensual??
  	    3.1.5 Cual es la tendencia en los últimos meses??
      	    3.1.6 Momentos de la verdad ??
      	3.2 Entendiendo los CLIENTES:
  	    3.2.1 Cómo se distribuyen los clientes en cuanto al gasto??
  	    3.2.2 Cómo se distribuyen los clientes en cuanto al número de compras??
  	    3.2.3 Cuantos productps compra un cliente de media en cada copra??
  	    3.2.4 Qué clientes generaron mas ingresos??
      	    3.2.5 Cual es la supervivivencia de los clientes??
  	    3.2.6 Cual es el LTV (LifeTimeValue) de los clientes??
  	    3.2.7 Sobre que clientes ejecutar las prósimas campañas RFM??
      	3.3 Entendiendo los PRODUCTOS:
  	    3.3.1 Cuales son los productos mas vendidos??
  	    3.3.2 Hay productos que no se venden y podriamos eliminarlos del catálogo??
  	    3.3.3 Cual es la relación entre precio y volumen de ventas??
  	    3.3.4 Hay productos que los clientes se arrepienten y eliminan más del carrito??
  	    3.3.5 Cuales son los productos mas vistos??
  	    3.3.6 Hay productos deseados pero no comprados??
  	    3.3.7 Construyendo un  SISTEMA DE RECOMENDACIÓN:
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
