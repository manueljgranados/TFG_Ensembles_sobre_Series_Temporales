📁 Estructura del proyecto

Este repositorio contiene todos los notebooks, modelos y datos empleados en el proyecto de predicción de series temporales financieras multivariadas mediante Deep Learning (GRU, CNN y Transformer).

📦 Directorios principales

🗂️ /data/
Contiene los datos utilizados en los distintos notebooks.
En cada fichero se accede a ellos mediante rutas relativas.

🧱 /models_cnn_huber_sweep/
Modelos CNN obtenidos para cada escenario.
La numeración de los ficheros indica el valor del delta de Huber empleado.

🔷 /models_gru_huber_sweep/
Modelos GRU obtenidos para cada escenario.
La numeración de los ficheros indica el valor del delta de Huber empleado.

🌀 /models_transformer_huber_sweep/
Modelos Transformer obtenidos para cada escenario.
La numeración de los ficheros indica el valor del delta de Huber empleado.

🧠 Notebooks de prueba de modelos individuales

📘 CNN_x_PRO.ipynb
Siendo x ∈ {L, M, S}: prueba de los modelos CNN en los escenarios L, M y S, aplicados a datos de producción.

📙 GRU_x_PRO.ipynb
Siendo x ∈ {L, M, S}: prueba de los modelos GRU en los escenarios L, M y S, aplicados a datos de producción.

📗 Transformer_x_PRO.ipynb
Siendo x ∈ {L, M, S}: prueba de los modelos Transformer en los escenarios L, M y S, aplicados a datos de producción.

🤝 Notebooks de ensembles

⚙️ Ensemble_x.ipynb
Siendo x ∈ {L, M, S}: evaluación de las combinaciones de ensembles en los escenarios L, M y S, sobre los datos de test.

🧩 x_PRO_Ensemble.ipynb
Siendo x ∈ {L, M, S}: evaluación de las combinaciones de ensembles en los escenarios L, M y S, sobre los datos de producción.

🏋️‍♂️ Notebooks de entrenamiento

🔵 TrainingCNN.ipynb
Entrenamiento, validación y test de los modelos CNN.

🟢 TrainingGRU.ipynb
Entrenamiento, validación y test de los modelos GRU.

🟣 TrainingTransformer.ipynb
Entrenamiento, validación y test de los modelos Transformer.

📄 Otros ficheros

📊 medidas.txt
Recopilación en texto plano de las métricas devueltas durante la obtención de cada modelo.

⚖️ scaler_modelos.joblib
Archivo del escalador (scaler) utilizado de forma común por todos los modelos para el preprocesamiento de los datos.
