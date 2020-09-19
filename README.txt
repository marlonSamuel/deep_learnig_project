PROYECTO STATISTICAL LEARNING II

Estructura.

-complicaciones y conclusiones
-VGG16: breve analisis de red VGG16 para clasificación de imagenes.
-cnn: modelo convolucional
	-process_dataset: extracción de labels, gender y etnia para clasificación y edad para regresión.
	-model_cnn_faces: notebook con el procesamiento, creación y entrenamiento del modelo.
	-model_transefering_learning: notebook con entrenamiento del modelo con VGG16.

-rnn: modelo red neuronal recurrente
	-sentiment_a: notebook principal, procesamiento de texto y entrenamiento de red neuronal recurrente.
	-tokenizer.picle: archivo con nokenización que se realizó en la fase de entrenamiento para posteriormente realizar la inferencia.
	-inference rnn: notebook de inferencia y prueba del modelo.

-mlp: modelo basico multilayer perceptron
	-mlp_recomendations: notebook principal, procesamiento y entrenamiento de modelo para recomendaciones de peliculas.
	-inference: inferencia sobre el modelo entrenado.

NOTA:

-Se realizó bastante experimentación en cada tipo de modelo, guardando todos los modelos en cada una de ellas. no se adjuntaron 
a esta carpeta porque el archivo se hacía muy pesado, de la misma forma con los dataset procesados.

-unicamente se incluyo el notebook principal y ordenado por cada modelo.