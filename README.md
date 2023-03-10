![header](https://capsule-render.vercel.app/api?type=waving&height=300&section=header&text=%20Análisis%20Standard%20and%20Poor's%20500&fontSize=30&&color=15:92a8d1,100:f7cac9&desc=%20%20&fontColor=ff6347&fontAlignY=35)


## INDICE:
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenido</summary>
  <ol>
    <li><a href="#header">TÍTULO E IMAGEN DE PORTADA</a></li>
    <li><a href="#INDICE">ÍNDICE</a></li>
    <li><a href="#INTRODUCCIÓN">INTRODUCCIÓN</a></li>
    <li><a href="#OBJETIVO">OBJETIVO</a></li>
    <li><a href="#SCOPE-OF-WORK">SCOPE OF WORK</a></li>
    <li><a href="#ESTADO">ESTADO</a></li>
    <li><a href="#EDA">EDA</a></li>
    <li><a href="#PowerBI">PowerBI</a></li>
    <li><a href="#PLANTEO-KPIs">PLANTEO-KPIs</a></li>
    <li><a href="#MINI-DEMO">MINI-DEMO</a></li>
    <li><a href="#ACCESO-AL-PROYECTO">ACCESO AL PROYECTO</a></li>
    <li><a href="#TECNOLOGÍAS">TECNOLOGÍAS UTILIZADAS</a></li>
    <li><a href="#DESARROLLADORES">DESARROLLADORES DEL PROYECTO</a></li>
    <li><a href="#SUPERVICIÓN">SUPERVICIÓN</a></li>
  </ol>
</details>


## INTRODUCCIÓN
Se propone hacer un analisis minucioso de un índice en particular, el indicador S&P 500. Este índice pondera la capitalización bursátil de las 500 mayores empresas que cotizan en la bolsa de los Estados Unidos. El índice está considerado como el mejor indicador de la renta variable estadounidense y es ampliamente utilizado y referenciado

## OBJETIVO
- Hacer analisis minucioso del indice S&P500
- Sacar información y conclusiones de valor para determinar decisiones de inversion
- Identificar Industrias o Sectores con mejor Retorno y contraponerlas con la información que se obtuvo anteriormente
- Desarrollo de KPIs elijiendo un foco
- Identificar días en donde conviene generar inversiones


## SCOPE-OF-WORK
La propuesta de trabajo se llevará a cabo en las siguientes etapas:
1. Adquisición de información de las siguientes fuentes: 
   -  API de yahoo finance
   - Librería: https://pypi.org/project/yfinance/ 
   - Página oficial
   - Lista índice SP500
   Información extra obtenida de APIs: Evaluación de datos históricos de las siguientes companias 
   - Advanced Micro Devices, Inc. (AMD)
   - Broadcom Inc. (AVGO) https://finance.yahoo.com/quote/AVGO/history?p=AVGO
   - Monolithic Power Systems, Inc. (MPWR) https://finance.yahoo.com/quote/MPWR/history?p=MPWR
   
2. Análisis exploratorio de datos (EDA) Link: (https://github.com/RocioAldanaMendez/S-P_500_EDA_Dashboard/blob/main/EDA.ipynb)
3. Desarrollo de Dashboard con Power BI. 
    Link en MEGA: 
    https://mega.nz/file/hdR1BaiZ#wb29iR6_sQQa3b5zWwRJ-fyadTLNDkPk0EHC4nyejBw
    Link  en Drive:
    https://drive.google.com/file/d/19dJEoxE87EBPVTh-PVxSCvxXH0G4ORzm/view?usp=share_link

![RUTA](https://github.com/RocioAldanaMendez/S-P_500_EDA_Dashboard/blob/main/assets/RUTA1.png)

## ESTADO:
<h4 align="center">
:white_check_mark: Proyecto finalizado :white_check_mark:
</h4>

## EDA
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width=40px height=40px/><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width=40px height=40px/><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width=40px height=40px/>  

1. Análisis Introductorio de la primera fuente de datos
2. Agregar más información de la segunda fuente de datos
3. Union de toda la información
4. Agregar columna de días, cambiar el idioma de los encabezados, convertir fechas en formato date, verificar nulos, outliers
5. Analisis minucioso: análisis univariado, análisis bivariado, verificar el promedio de cierre del indice desde el 2000 a la actualidad, variación de las industrias, variación de las industrias tomando mas valores.
6. Primeras conclusiones
7. Variación de los cierres a lo largo de los años, cálculo de volatilidad, evaluación del retorno total.
8. Segundas conclusiones
9. Cálculo de mejores dias de inversión.
10. Exportación de datos en .parquet, y .csv (siempre es mejor tener un respaldo)

Link Desarrollo de Analisis Exploratorio de Datos en .ipynb: (https://github.com/RocioAldanaMendez/S-P_500_EDA_Dashboard/blob/main/EDA.ipynb)

## PowerBI
## PLANTEO-KPIs:
- `KPI 1`: Retorno promedio anual mayor al 8% a lo largo de 12 meses
               
- `KPI 2`:  Volatilidad menor al 5,0% en el período de un año 
                    
- `KPI 3`: Alcance del mercado de un sector mayor al 10% contemplando una tendencia alsista a lo largo de 2 años.
           
- `KPI 4`: El volumen superior a 0.4 billones en un período de 2 años. 

- `KPI 5`: Valor de ganancia nominal por acción de un sector ( EPS) mayor a 13 millones en un período de un año.
  
* Link Proyecto POWER BI alojado en la página oficial (teniendo cuenta institucional o profesional UdeMM):
https://app.powerbi.com/links/DobA7PM_4n?ctid=bd085bdc-7e08-4b26-870c-a9331a90ec70&pbi_source=linkShare&bookmarkGuid=a503a7e9-712f-46c2-b2f1-3d646c247717

* Link Proyecto POWER BI alojado en MEGA:
https://mega.nz/file/hFQyxSqQ#yoK-BFbpq7nIqq6eg82Rq9zBSRFNm130Q3jZ-iJbuDc

* Link Proyecto POWER BI alojado en Drive:
https://drive.google.com/file/d/19dJEoxE87EBPVTh-PVxSCvxXH0G4ORzm/view?usp=share_link

## MINI-DEMO

![DEMO1](https://github.com/RocioAldanaMendez/S-P_500_EDA_Dashboard/blob/main/assets/DEMO1.gif)


## ACCESO-AL-PROYECTO
            ## 🛠️ Para visualizar el EDA, basta con abrir el proyecto de extención .ipynb desde git, o descargarlo y correrlo en tu IDE de preferencia, yo trabajé en esta oportunidad con Colab: https://colab.research.google.com/
            
            ## Para abrir el proyecto Power BI, opcion 1) puedes dirigirte al link de despliegue en esa plataforma solo si tenes cuenta universitaria o profesional de UdeMM (Universidad de la Marina Mercante)
            2) podes encontrar el archivo .pbix alojado en la nube de MEGA, por lo que es necesario descargarlo y correrlo en Power BI.
            3) podes encontrar el archivo .pbix en la nuve de Google Drive, por lo que es necesario descargarlo y correrlo en Power BI.
            
         
 
## TECNOLOGÍAS
 <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width=40px height=40px/>
## DESARROLLADORES

| [<img src="https://avatars.githubusercontent.com/u/83037176?v=4" width=115><br><sub>Rocío Méndez</sub>](https://github.com/RocioAldanaMendez) |
| :---: | 

## SUPERVICIÓN

Proyecto bajo supervición de los siguientes profesionales:
![integrantes](https://github.com/RocioAldanaMendez/S-P_500_EDA_Dashboard/blob/main/assets/integrantes.png)

Muchisimas gracias por ver este desarrollo, podes seguir los futuros cambios dandole una estrellita en la parte superior derecha del repositorio. Podes Clonarlo, y/o podes hacer un PullRequest ya que todo aporte es bienvenido. :smiley: :wave:


