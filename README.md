# Proyecto Final – EDA y Dashboard sobre Airbnb NYC (2019)

## Descripción del proyecto
Este proyecto forma parte del Proyecto Final del Máster en Data Analytics.  
El objetivo es realizar un Análisis Exploratorio de Datos (EDA) y construir un dashboard utilizando datos reales de Airbnb en la ciudad de Nueva York.

El trabajo se centra en:
- Limpieza y transformación profunda de los datos
- Unión de múltiples fuentes
- Análisis descriptivo y estadístico
- Visualización de datos
- Creación de un dashboard operativo

## Datasets utilizados

### Airbnb NYC Listings (2019)
Dataset principal que contiene información sobre los alojamientos de Airbnb en Nueva York:
- Precio
- Tipo de alojamiento
- Localización (borough)
- Disponibilidad
- Número de reseñas

Total aproximado: **48.895 registros**
URL: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

### NYC Census Data
Dataset socioeconómico con información demográfica y económica de la ciudad:
- Ingresos
- Pobreza
- Empleo y desempleo
- Medios de transporte
- Composición poblacional

Este dataset se agrega posteriormente a nivel de zona para poder unirlo con Airbnb.

URL: https://www.kaggle.com/datasets/muonneutrino/new-york-city-census-data?utm_source=chatgpt.com&select=nyc_census_tracts.csv

## Herramientas utilizadas

### Análisis de datos
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Visual Studio Code

### Visualización
- Power BI Desktop

## Estructura del repositorio

├── data/
│ ├── raw/ # Datos originales
│ └── processed/ # Dataset final limpio
│
├── notebook/
│ └── EDA_Proyecto_final.ipynb
│
├── dashboard/
│ └── Airbnb_NYC.pbix
│
└── README.md


## Proceso seguido

### 1. Limpieza y transformación de datos
- Conversión de fechas y tipos de datos
- Tratamiento de valores nulos
- Normalización de nombres de zonas (borough)
- Eliminación de columnas no relevantes
- Agregación de datos socioeconómicos por zonas

### 2. Unión de datasets
- Unión de Airbnb y Census utilizando el borough como clave
- Creación de un dataset final con variables de ambos orígenes

### 3. Análisis exploratorio y estadístico
- Análisis de variables numéricas y categóricas
- Histogramas, boxplots y gráficos comparativos
- Matrices de correlación para detectar relaciones entre variables

### 4. Dashboard en Power BI
Se desarrolla un dashboard con tres páginas:
- Visión general del mercado Airbnb
- Análisis de precios
- Relación entre variables socioeconómicas y el mercado de Airbnb

## Conclusiones principales
- Manhattan es la zona con precios más elevados.
- Brooklyn y Manhattan concentran la mayor oferta de alojamientos.
- Los alojamientos completos tienen precios más altos que las habitaciones privadas.
- Las variables socioeconómicas muestran diferencias claras entre zonas, aunque no explican por completo el comportamiento de los precios.

## Autoría
Proyecto realizado por Maria Adell Armela
Máster en Data Analytics — Proyecto Final
Año académico: 2025
