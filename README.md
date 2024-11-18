# -CC219-TP-TF-2024-2
Participantes:
- Jhonny Elias Ruiz Santos
- Guido Yair Abel Jeri Saldaña
- Karim Wagner Samanamud Mosquera

Objetivo del proyecto: identificar las diferentes opiniones que los usuarios destacan en sus experiencias, siendo principalmente respecto a la calidad del producto

Descripción del dataset:El dataset utilizado contiene más de 568,000 reseñas de diversos productos de Amazon. Las variables incluidas en este conjunto de datos son: Id, ProductId, UserId, ProfileName, HelpfulnessNumerator, HelpfulnessDenominator, Score, Time, Summary y Text.

Fuente: https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews/data

Conclusión:
En este trabajo, se comparó el modelo BERT sin ajustar con fine-tuning frente a un modelo pre entrenado especializado (bert-base-multilingual-uncased-sentiment) para análisis de sentimientos en reviews de Amazon. Los resultados mostraron que el modelo pre entrenado obtuvo un desempeño más equilibrado en términos de recall y precisión, especialmente en la categoría positiva, mientras que el modelo ajustado con fine-tuning no logró superar significativamente al modelo pre entrenado y presentó limitaciones notables en todas las categorías. Esto se podría deber a una falta de mayor datos de entrenamiento y el no tener balanceados nuestros datos.A futuro, se recomienda realizar un análisis más exhaustivo de las condiciones en las que el fine-tuning puede proporcionar beneficios significativos. Asimismo, como el uso de un conjunto de datos más grande para el entrenamiento.
