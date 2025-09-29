# -project-da-promo-54-modulo-3-team-2
Proyecto "Transformando el Talento" - Módulo 3 - ADALAB
# 📊 Proyecto: Optimización de Talento

## 📌 Resumen

En el entorno empresarial actual, la retención de empleados y la satisfacción laboral son factores clave para garantizar la productividad y la rentabilidad de una empresa.  
ABC Corporation nos ha contratado para analizar sus datos de empleados con el objetivo de **identificar factores que influyen en la satisfacción en el trabajo y en la rotación de personal**.  

Este proyecto aplica técnicas de **análisis exploratorio de datos (EDA)**, **transformación**, **visualización** y **modelado de bases de datos**, con el fin de proporcionar información estratégica para la toma de decisiones.

---

## 🏢 Cliente: ABC Corporation

**ABC Corporation**, fundada en 1980 en California, es una consultora tecnológica especializada en soluciones de **inteligencia artificial (IA)** y **machine learning**.  
Su último gran proyecto ha sido la creación de una **plataforma de selección inteligente**, capaz de analizar CVs automáticamente, identificar habilidades clave y recomendar a los mejores candidatos para cada puesto.

---

## 🔎 Fases del Proyecto

### 1. Análisis Exploratorio de Datos (EDA)
- Exploración inicial de los datos.
- Identificación de valores nulos, duplicados, inconsistentes o atípicos.
- Estadísticas descriptivas de las columnas principales.

### 2. Transformación de los Datos
- Corrección de valores inconsistentes (por ej., errores tipográficos en `MaritalStatus`, etc.).
- Conversión de tipos de datos (`DailyRate` de *string* → numérico).
- Reemplazo de valores no intuitivos (`Gender` → "Male"/"Female").
- Eliminación de duplicados y columnas redundantes.

### 3. Visualización de los Datos
- Creación de gráficos descriptivos para comprender patrones de satisfacción, ingresos, promociones, balance vida-trabajo, etc.
- Identificación de tendencias y factores de riesgo en la rotación.

### 4. Diseño e Inserción de la Base de Datos
- Definición de tablas, relaciones y claves primarias/foráneas.
- Inserción de los datos transformados.
- Preparación para consultas SQL.

### 5. Creación de ETL (Bonus)
- Automatización del proceso de **extracción, transformación y carga**.
- Funciones en Python para garantizar que la BBDD esté actualizada.

---

## 🗂️ Los Datos

El conjunto de datos contiene información de empleados de ABC Corporation.  
Algunas de las columnas principales son:
  
- **Employeenumber**: Número del empleado.
- **Attrition**: Si dejó la empresa (Yes/No).  
- **BusinessTravel**: Frecuencia de viajes de trabajo.  
- **Department**: Departamento del empleado.  
- **DistanceFromHome**: Distancia entre hogar y trabajo.  
- **Education**, **EducationField**: Nivel y campo educativo.  
- **Gender**, **MaritalStatus**: Variables demográficas.  
- **JobRole**, **JobLevel**, **JobSatisfaction**.  
- **MonthlyIncome**, **Salary**: Información salarial.  
- **OverTime**, **RemoteWork**: Condiciones laborales.  
- **PerformanceRating**, **WorkLifeBalance**.  
- **YearsAtCompany**, **YearsSinceLastPromotion**.  

👉 El dataset completo se encuentra en [`hr_raw_data.csv`](./data/hr_raw_data.csv).

---

## 🎯 Objetivos

1. Identificar patrones que afectan la retención de empleados.  
2. Mejorar el entendimiento de los factores de satisfacción laboral.  
3. Diseñar un modelo de datos que permita consultas estratégicas.  
4. Automatizar el flujo de extracción, transformación y carga (ETL).  
5. Practicar metodologías ágiles (*Scrum*) y control de versiones (Git/GitHub).  

---

## 🚀 Tecnologías Utilizadas

- **Lenguaje:** Python 3.10  
- **Librerías principales:**
    - `os` → Trabajo con rutas y carpetas.
    - `re` → Búsqueda de patrones en texto.
    - `pandas`, `numpy` → Manipulación de datos.  
    - `matplotlib`, `seaborn` → Visualización.  
    - `sqlite3` → Creación y uso de una base de datos SQLite (.db) local. 
    - `mysqlconnector` → Conexión con bases de datos.  
    - `scipy` → Estadística inferencial.  
- **Gestión del proyecto:** GitHub, Scrum.  
- **Base de datos:** SQL (modelo relacional).  

---

## ⚙️ Instrucciones de Uso

1. **Clonar el repositorio:**
   git clone https://github.com/usuario/-proyecto-da-promo-54-modulo-3-team-2.git
   cd -proyecto-da-promo-54-modulo-3-team-2

2. **Instalar dependencias:**
    pip install -r requirements.txt

3. **Ejecutar el análisis:**
    python main.py

4. **Revisar visualizaciones:**
    Los gráficos se guardarán en la carpeta /plots.

---

## 📅 Planificación del Proyecto

Se trabajó en 2 sprints siguiendo metodología Scrum.
Cada sprint incluye:

    - Sprint Planning → definición de tareas.
    - Desarrollo → extracción, transformación, análisis y visualización.
    - Sprint Review → demo y recogida de feedback.
    - Retrospectiva → revisión de mejoras de equipo.

---

## Historias de Usuario

    - Como analista, quiero explorar los datos para entender su estructura.
    - Como equipo, queremos limpiar los datos para mejorar su calidad.
    - Como cliente, quiero visualizaciones que me ayuden a tomar decisiones.

---

## 📊 Entregables

    Código Python: extracción, transformación y visualización.
    EDA Documentado: en Jupyter Notebooks.
    Base de Datos: creada con SQL.
    ETL Automatizada: en archivo .py.
    README.md y requirements.txt.

---

## 👩‍💻 Autoras

Clara Bueno
Esther Domínguez
Marta Sanz
Laura Parejo
Paola Sánchez

---

## 📌 Estado del Proyecto

🔧 En desarrollo.
Faltan mejoras relacionadas con:
    - Optimización de consultas SQL.
    - Expansión de la ETL.
    - Creación de dashboards interactivos.

---

## 📢 Créditos

Este proyecto ha sido desarrollado dentro del módulo 3 del curso de Análisis de Datos, con fines educativos.