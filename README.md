<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
    <header>
        <h1>Proyecto Evaluación 1</h1>
        <p>Machine Learning</p>
    </header>
    <div class="container">
        <div class="section">
            <h2>Problema 1: Predicción del Precio de Casas</h2>
            <p><strong>Descripción:</strong> Predecir el precio de una casa en California según sus características elementales.</p>
            <p><strong>DataSet:</strong> <a href="https://www.kaggle.com/datasets/camnugent/california-housing-prices" target="_blank">bases de datos california</a></p>
            <div class="question">
                <strong>a)</strong> ¿Qué características influyen más en el valor de una casa?
                <img src="https://github.com/user-attachments/assets/a5394bbd-7fd9-402d-8b4a-1354451789e6" alt="Características que influyen en el valor de una casa">
                <p>Las características más influyentes en el valor de una casa son el ingreso medio, el número de dormitorios, y la proximidad al océano</p>
            </div>
            <div class="question">
                <strong>b)</strong> ¿Cuál es la precisión del algoritmo generado?
                <img src="https://github.com/user-attachments/assets/0797864a-e574-4489-9e0c-be46a409c9c5" alt="Precisión del algoritmo">
                <p>El valor de es aproximadamente 0.65, lo que significa que el modelo explica alrededor del 64.88% de la variabilidad en los valores de las casas. Esto sugiere que el modelo tiene una capacidad razonable para ajustar los datos y predecir los valores, aunque no es perfecto.</p>
            </div>
            <div class="question">
                <strong>c)</strong> Usar las métricas de evaluación del algoritmo: error absoluto medio, error cuadrático medio, puntaje r al cuadrado, la raíz del error cuadrático medio, para evaluar el modelo y explicar su interpretación.
                <img src="https://github.com/user-attachments/assets/4a89fea5-32ed-4c27-9181-a6ca7a912abf" alt="Métricas de evaluación">
            </div>
        </div>
        <div class="section">
            <h2>Problema 2: Clasificación de Correos Electrónicos</h2>
            <p><strong>Descripción:</strong> Clasificar correos electrónicos en spam o no spam basándose en el contenido del correo.</p>
            <p><strong>DataSet:</strong> <a href="https://www.kaggle.com/datasets/camnugent/california-housing-prices" target="_blank">base de datos Spam</a></p>
            <div class="question">
                <strong>a)</strong> Justificar el modelo que utilizó.
                <img src="https://github.com/user-attachments/assets/65fae682-4a1c-4335-92eb-5cb50d575a08" alt="Modelo utilizado">
                <p>Hemos optado por el clasificador Naive Bayes porque es particularmente eficaz para problemas de clasificación donde los datos se pueden modelar como distribuciones probabilísticas simples.</p>
            </div>
            <div class="question">
                <strong>b)</strong> ¿Qué características afectan más en que un correo sea Spam?
                <img src="https://github.com/user-attachments/assets/439484f4-ae5a-4e9f-819a-549fc7fc0172" alt="Características del correo Spam">
                <p>Las características que más influyen en la clasificación de un correo como spam incluyen palabras como 'free', 'money', 'business' y símbolos como '$', así como el uso de letras en mayúsculas o secuencias largas de caracteres. Estas características son comunes en correos no deseados y, por lo tanto, son fuertes indicadores.</p>
            </div>
            <div class="question">
                <strong>c)</strong> Usar las métricas: Tasa de Error, Exactitud, Matriz de confusión, tasa de positivos verdaderos, tasa de positivos falsos, Precisión, F1-Score. Investigar cuál(es) de estas métricas es más acertada para este caso y explicar su interpretación.
                <img src="https://github.com/user-attachments/assets/8a7e0d24-5508-4295-bd45-a781bf9e400a" alt="Métricas de clasificación de correos electrónicos">
            </div>
        </div>
        <div class="section">
            <h2>Problema 3: Recomendación de Productos</h2>
            <p><strong>Descripción:</strong> Recomendar productos a un usuario basado en las similitudes con otros usuarios o productos.</p>
            <p><strong>DataSet:</strong> <a href="https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?select=movie.csv" target="_blank">películas a recomendar</a></p>
            <div class="question">
                <strong>a)</strong> ¿Cuál película recomendarían si se quiere ver una película de terror?
                <img src="https://github.com/user-attachments/assets/3f3fcf72-0917-46bc-ad14-722970fa60d4" alt="Recomendación de película de terror">
                <p>"Female Vampire (Les avaleuses) (Erotic Kill) (1973)" es una recomendación interesante para los amantes del cine de terror porque combina elementos de terror psicológico y erotismo, característica del estilo único de su director, Jesús Franco. La película se destaca por su atmósfera inquietante y su enfoque en la figura de un vampiro femenino, lo que la hace una opción intrigante para quienes buscan una experiencia de terror diferente, con un toque más experimental y provocador.</p>
            </div>
            <div class="question">
                <strong>b)</strong> ¿Qué película recomendarían si mi última película fue Toy Story?
                <img src="https://github.com/user-attachments/assets/6d0a7459-5ed5-458d-8f10-ae3ec543fb08" alt="Recomendación después de Toy Story">
                <p>"Monsters, Inc." (2001) de Pixar, tiene un enfoque en la amistad y el trabajo en equipo con un toque de comedia y aventura. </p>
            </div>
        </div>
        <div class="section">
            <h2>Problema 4: Detección de Transacciones Fraudulentas</h2>
            <p><strong>Descripción:</strong> Detectar si una transacción bancaria es fraudulenta o no, basado en patrones de transacciones históricas.</p>
            <p><strong>DataSet:</strong> <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcard" target="_blank">transacción bancaria</a></p>
           <div class="question">
                <strong>a)</strong> ¿Qué kernel sería más adecuado para abordar este problema? Justifique su respuesta.
                <img src="https://github.com/user-attachments/assets/2b797019-3797-4f0d-884c-6f9d0a3dae25" alt="Kernel adecuado para el problema de SVM">
            </div>
            <div class="question">
                <strong>b)</strong> Comparar las métricas de: Precisión, Puntaje-F1, Puntaje Recall y Exactitud, explique cuál se ajusta mejor para medir la calidad del modelo y por qué.
                <img src="https://github.com/user-attachments/assets/66634b39-d9cb-4875-a31a-0fcccb5bf264" alt="Métricas de evaluación del modelo">
                <p>Dado que el recall es bajo y el F1 también es moderado, si hay un desbalance de clases, el Puntaje F1 sería la mejor métrica para evaluar el rendimiento global del modelo, ya que tiene en cuenta tanto la precisión como el recall.</p>
            </div>
        </div>
    </div>
</body>
</html>
