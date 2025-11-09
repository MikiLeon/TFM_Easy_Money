# Proyecto Final TFM — easyMoney
**Máster en Data Science & AI – Nuclio Digital School**

## 📌 Descripción del proyecto
El objetivo del TFM **“easyMoney: Rentabilización de la base de clientes mediante analítica avanzada y segmentación predictiva”** es aplicar técnicas de **análisis de datos, modelado predictivo y segmentación de clientes** para diseñar estrategias de rentabilidad y crecimiento basadas en datos.

Se busca:

- Analizar el comportamiento de los clientes y productos.  
- Predecir la propensión de compra de distintos productos financieros.  
- Segmentar la base de clientes en clusters relevantes para campañas comerciales.  
- Generar recomendaciones estratégicas y estimaciones de ROI.

---

## 📂 Estructura del repositorio


``` python
TFM_Easy_Money/

├── notebooks/

│ ├── 1_Limpieza_BD_y_Feature_Engineering.ipynb

│ ├── 2_M1_em_account_Propensión_Compra.ipynb

│ ├── 3_M2_emc_account_Propensión_Compra.ipynb

│ ├── 4_M3_pension_plan_Propensión_Compra.ipynb

│ ├── 5_M4_long_term_deposit_Propensión_Compra.ipynb

│ ├── 6_M5_debit_card_Propensión_Compra.ipynb

│ ├── 7_Clustering_Model.ipynb

│ └── 8_Business_Proposal.ipynb

├── requirements.txt # Librerías  necesarias

└── Presentación.pdf # Presentación ejecutiva para stakeholders

```

---

## ⚙️ Requisitos e instalación

- Python 3.8+ (recomendable 3.9)  
- Crear un entorno virtual (`venv` o `conda`)  

Instalación con pip:

```python
git clone <URL_REPO>
cd TFM_Easy_Money
python -m venv .venv
.venv\Scripts\activate    # Windows
source .venv/bin/activate # Linux/Mac
pip install -r requirements.txt
```

 ## 📝 Cómo ejecutar los notebooks

**1_Limpieza_BD_y_Feature_Engineering.ipynb**  
Este notebook integra todos los dataframes originales, 
realiza un análisis exploratorio completo y aplica limpieza de datos. 
Además, desarrolla el **feature engineering** que se usará en los modelos de propensión y clustering.

**2–6 Notebooks de propensión de compra (M1–M5)**  
Cada uno de estos notebooks implementa la predicción de propensión de compra para un producto específico.
 Incluyen **preprocesamiento**, rebalanceo de clases, comparación entre modelos, ajuste de hiperparámetros y predicción final.

**7_Clustering_Model.ipynb**  
Aquí se desarrolla la **segmentación de clientes** mediante K-Means. 
Se realiza la selección de features relevantes y se determina la cantidad óptima de clusters mediante el método del codo (Elbow Curve).

**8_Business_Proposal.ipynb**  
Este notebook simula y diseña **campañas comerciales** basadas en los resultados de propensión y clustering. 
Se calculan costes, beneficios y ROI esperado bajo distintos escenarios (pesimista, realista y optimista).


## 👥 Autores

Daniel Guidi

Juan Manuel Guatta

Miguel Ángel García

Raphael Cheves

**Máster en Data Science & AI – Nuclio Digital School, Barcelona 2025**
