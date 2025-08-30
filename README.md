# 📊 EDA en Recursos Humanos

##  Descripción del Proyecto
Este proyecto consiste en un **Análisis Exploratorio de Datos (EDA)** aplicado a un dataset ficticio de empleados de una empresa.  
El objetivo es identificar **patrones y factores relacionados con la rotación, salarios, antigüedad y satisfacción laboral**, con el fin de proponer **estrategias de retención y mejora en la gestión del talento**.


##  Objetivos del Análisis
1. Analizar la **distribución de edades** de los empleados.  
2. Identificar **diferencias salariales** entre departamentos.  
3. Detectar **departamentos con mayor rotación**.  
4. Explorar la relación entre **satisfacción laboral y rotación**.  
5. Examinar la relación entre **antigüedad en la empresa y rotación**.  


##  Dataset
El dataset contiene información ficticia de **300 empleados**, con las siguientes variables:

- `EmpleadoID`: Identificador único.  
- `Edad`: Edad del empleado (22 – 60 años).  
- `Género`: Masculino / Femenino.  
- `Departamento`: Ventas, Finanzas, IT, Producción, RRHH.  
- `Salario`: Rango entre 1,500 y 8,000 (moneda local).  
- `Antigüedad`: Años en la empresa (0 – 15).  
- `NivelEducacion`: Bachiller, Técnico, Profesional, Posgrado.  
- `Satisfacción`: Escala de 1 a 10.  
- `Rotación`: 1 = Renunció, 0 = Sigue en la empresa.  


##  Tecnologías Utilizadas
- Python 3  
- Pandas 
- Matplotlib & Seaborn  
- Jupyter Notebook / Google Colab


##  Principales Resultados
- La mayoría de empleados se concentran entre **25 y 40 años**.  
- Los salarios más altos corresponden a **IT y Finanzas**; los más bajos a **RRHH y Ventas**.  
- La **rotación** es más elevada en **Producción y Ventas**.  
- Los empleados que renuncian muestran **menores niveles de satisfacción (≤ 5)**.  
- La mayoría de renuncias ocurren en empleados con **menos de 3 años de antigüedad**.  


##  Valor de Negocio
El análisis permite a la organización:
- Diseñar **planes de retención** para empleados en riesgo de renunciar.  
- Ajustar **políticas salariales** para hacer más competitivas ciertas áreas.  
- Implementar **encuestas de satisfacción periódicas**.  
- Priorizar estrategias en **departamentos críticos** con mayor rotación.  


## Estructura del Proyecto
- `EDA_Recursos_Humanos.ipynb` → Notebook con el análisis
- `Reporte – Análisis Exploratorio de Datos (EDA).pdf` → Reporte final en PDF
- `README.md` → Documentación del proyecto


##  Próximos Pasos
- Desarrollar un **modelo predictivo de rotación de empleados**.  
- Implementar un **dashboard interactivo en Power BI / Tableau**.  


## Autor
Proyecto realizado por **Luz Angela Villate Paipilla**, como parte de su portafolio de Analista de Datos.
