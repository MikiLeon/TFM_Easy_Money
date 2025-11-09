Proyecto Final TFM – easyMoney
Máster en Data Science & AI – Nuclio Digital School
Este repositorio contiene los archivos entregados para la defensa final del Trabajo Fin de Máster (TFM) titulado “easyMoney: Rentabilización de la base de clientes mediante analítica avanzada y segmentación predictiva”. El objetivo del proyecto es aplicar técnicas de análisis de datos, modelado predictivo y segmentación de clientes para diseñar estrategias de rentabilidad y crecimiento basadas en datos.

📂 Estructura de archivos
Notebooks de análisis y modelado
    1 Limpieza_BD_y_Feature_Engineering.ipynb
        ◦ Integra los 5 dataframes originales de la base de datos.
        ◦ Realiza un análisis exploratorio rápido (EDA), limpieza e imputación de nulos.
        ◦ Evalúa productos a nivel de ventas, clientes y rentabilidad.
        ◦ Desarrolla el feature engineering utilizado posteriormente en los modelos de propensión y clustering.
    2 M1_em_account_Propensión_Compra.ipynb
        ◦ Modelo de predicción de propensión de compra para el producto Cuenta EasyMoney.
        ◦ Incluye preprocesamiento, rebalanceo, competición de modelos, ajuste de hiperparámetros y predicción final.
    3 M2_emc_account_Propensión_Compra.ipynb
        ◦ Modelo de propensión de compra para el producto Cuenta EasyMoney Crypto, con la misma estructura metodológica que el anterior.
    4 M3_pension_plan_Propensión_Compra.ipynb
        ◦ Modelo predictivo para Planes de Pensiones, orientado a clientes senior o conservadores.
    5 M4_long_term_deposit_Propensión_Compra.ipynb
        ◦ Modelo predictivo para Depósitos a Largo Plazo, considerando rentabilidad esperada por cliente.
    6 M5_debit_card_Propensión_Compra.ipynb
        ◦ Modelo predictivo para Tarjeta de Débito, enfocado en clientes sin productos básicos activos.
    7 Clustering_Model.ipynb
        ◦ Desarrollo del modelo de segmentación de clientes mediante K-Means.
        ◦ Selección de features relevantes y determinación óptima de 5 clusters a partir del método del codo (Elbow Curve).
    8 Business_Proposal.ipynb
        ◦ Simulación y diseño de campañas comerciales basadas en los resultados de propensión y clusters.
        ◦ Cálculo de costes, beneficios y ROI esperado bajo escenarios pesimista, realista y optimista.

Otros archivos del proyecto
    9 requirements.txt
        ◦         •Lista de librerías y versiones de Python necesarias para ejecutar los notebooks.
    10 Dashboard easyMoney.pbix
    • Dashboard interactivo de Power BI que muestra la situación actual de la empresa, métricas de ventas, clientes y productos.
    11 Memoria TFM.pdf
    • Documento académico que detalla los objetivos, metodología, resultados y conclusiones del proyecto.
    12 Presentación.pdf
    • Presentación ejecutiva para stakeholders, utilizada en la defensa del TFM.
    • Incluye las campañas propuestas, impacto estimado y recomendaciones estratégicas.

Instrucciones básicas de ejecución
    1 Crear un entorno virtual y activar.
    2 Instalar dependencias con: pip install -r requirements.txt
    3 Ejecutar los notebooks en el siguiente orden sugerido:
        1 Limpieza_BD_y_Feature_Engineering.ipynb
        2 M1–M5 notebooks de propensión
        3 Clustering_Model.ipynb
        4 Business_Proposal.ipynb

Autores
Daniel Guidi
Juan Manuel Guatta
Miguel Angel García
Raphael Cheves
 Máster en Data Science & AI – Nuclio Digital School Barcelona, 2025
