Alura Store - Análisis de Ventas y Rendimiento

Este proyecto corresponde al desafío Alura Store, cuyo objetivo es analizar las ventas y el desempeño de cuatro tiendas, con el fin de ayudar al señor Juan a decidir cuál de estas tiendas vender para invertir en un nuevo negocio.

El análisis se centra en cinco aspectos clave de las tiendas:

📈 Facturación total de cada tienda.

🛒 Categorías más populares en cada tienda.

⭐ Promedio de evaluación de los clientes.

🔝 Productos más y menos vendidos.

🚚 Costo promedio de envío hacia los clientes.

Con estos análisis, se entregará un informe final para orientar la decisión estratégica del señor Juan.

🎯 Objetivos

✔️ Evaluar el rendimiento de las 4 tiendas.
✔️ Identificar patrones en ventas y categorías más populares.
✔️ Analizar la satisfacción de los clientes mediante sus evaluaciones.
✔️ Detectar productos más y menos vendidos.
✔️ Calcular y comparar los costos de envío promedio por tienda.
✔️ Generar un informe que responda: ¿Qué tienda debería vender el señor Juan?

🛠️ Tecnologías utilizadas

Python 3

Pandas → manipulación de datos

Matplotlib & Seaborn → visualización de resultados

Jupyter Notebook / Google Colab → desarrollo y presentación de análisis

📂 Estructura del repositorio
alurastore-sales-analysis/
│── data/
│   └── stores_data.csv        # bases de datos de las tiendas
│
│── notebooks/
│   └── 01_facturacion.ipynb       # análisis de facturación
│   └── 02_categorias.ipynb        # ventas por categoría
│   └── 03_evaluaciones.ipynb      # promedio de calificación clientes
│   └── 04_productos.ipynb         # productos más/menos vendidos
│   └── 05_envio.ipynb             # costo promedio de envío
│
│── reports/
│   └── informe_final.md           # conclusiones para el Sr. Juan
│
│── requirements.txt               # dependencias del proyecto
│── README.md                      # documentación principal

📥 Datos

Los datos fueron proporcionados en el repositorio base del desafío y contienen información de las 4 tiendas de Alura Store.
Se recomienda no modificar la sección de importación de datos ya que los datasets están preconfigurados para análisis en Google Colab.

🚀 Cómo ejecutar el proyecto

Clonar el repositorio:

git clone https://github.com/RaqDxs/alurastore-sales-analysis.git
cd alurastore-sales-analysis


(Opcional) Crear un entorno virtual:

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows


Instalar dependencias:

pip install -r requirements.txt


Ejecutar los notebooks en Google Colab o Jupyter Notebook y completar cada análisis.

📊 Resultados esperados

Comparación clara de la facturación total entre tiendas.

Gráficas de las categorías más vendidas por tienda.

Análisis del promedio de calificación de clientes.

Ranking de productos más y menos vendidos.

Comparación de los costos de envío promedio.

Informe final con una recomendación sobre la tienda a vender.

👩‍💻 Autor

Repositorio desarrollado por RaqDxs
 ✨
Parte del programa One | Alura + Oracle.
