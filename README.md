# 📊 Alura Store – Análisis de Desempeño Comercial

Este proyecto consiste en un análisis exploratorio y visual de datos de ventas de **Alura Store**, una tienda ficticia con 4 sucursales (Lojas 1 a 4). El objetivo es identificar cuál de las tiendas presenta un menor rendimiento comercial para recomendar su venta 
---
## Propósito del análisis
El análisis busca:
- Calcular e interpretar **los ingresos totales de cada tienda**.
- Analizar la **evolución de la facturación mensual**.
- Evaluar la **satisfacción de los clientes** por loja.
- Comparar los **costos de envío promedio**.
- Identificar los **productos más y menos vendidos**.
- Recomendar qué tienda vender, integrando todos los indicadores en una **evaluación combinada**.
---
## Estructura del proyecto

alura-store/ ├── data/ │ ├── loja1.csv │ ├── loja2.csv │ ├── loja3.csv │ └── loja4.csv ├── notebooks/ │ └── alura-store-analysis.ipynb ├── images/ │ ├── facturacion_total.png │ ├── evaluacion_clientes.png │ └── flete_vs_evaluacion.png ├── README.md └── requirements.txt

- `data/`: contiene los archivos de ventas de cada loja.  
- `notebooks/`: notebook principal con todo el análisis.  
- `images/`: exportación de los gráficos generados.  
- `README.md`: documentación del proyecto.  
- `requirements.txt`: dependencias necesarias para ejecutar el análisis.
---
##  Ejemplos de gráficos e insights
### Ingresos Totales por Loja
![Ingresos](images/facturacion_total.png)

**Insight:** Loja 4 registró los ingresos más bajos, incluso considerando el costo de envío como ingreso.
---
### Evaluación Promedio de Clientes
![Evaluación](images/evaluacion_clientes.png)

**Insight:** Loja 3 tiene la mejor evaluación. Loja 1 está por debajo de 4.0.
---
### Relación Frete vs Evaluación
![Frete vs Evaluación](images/flete_vs_evaluacion.png)

**Insight:** A mayor costo de envío, hay tendencia a menor evaluación.
---
## Recomendación Final
**La tienda que debe ser vendida es Loja 4**, ya que presenta el menor ingreso total, baja rotación de productos y desempeño plano en su evolución mensual.
---
## Instrucciones para ejecutar el notebook
1. Cloná el repositorio:
   ```bash
   git clone https://github.com/tuusuario/alura-store.git
   cd alura-store
Instalá las dependencias:

pip install -r requirements.txt
Ejecutá el notebook con Jupyter o Google Colab:
Abrir en Colab
O localmente:

jupyter notebook notebooks/alura-store-analysis.ipynb
Asegurate de que los archivos .csv estén dentro de la carpeta data/.

Tecnologías utilizadas
Python ,Pandas, Matplotlib, Jupyter Notebook

Proyecto desarrollado por Néstor Germán Córdoba

