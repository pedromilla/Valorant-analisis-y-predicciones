# Valorant, preparación de datos, análisis y predicciones.

El mundo de los videojuegos experimentó un notable avance cuando fue posible jugar a distancia con cualquier persona en cualquier parte del mundo. El acceso a internet y la notable evolución de la transferencia de datos, permiten que actualmente existan grandes ligas de videojuegos y campeonatos a nivel mundial con equipos profesionales compitiendo.
Este trabajo presenta la implementación de modelos de Machine Learning para predecir el resultado de partidas del videojuego Valorant, utilizando los datos generados en Random Forest y XGBoost como algoritmos de clasificación.
Para realizar las predicciones de partidas futuras, los datos se fueron agrupando de manera que por cada partida existan dos observaciones, una por cada equipo. Además, se tomaron como variables los datos generados en partidas pasadas, generando así una predicción al inicio de la partida futura.
Los resultados indican que XGBoost tiene un mejor desempeño sobre Random Forest, debido a que el ajuste de hiperparámetros y la selección de variables logró un aumento en la capacidad de predecir tanto partidas ganadas como perdidas.
