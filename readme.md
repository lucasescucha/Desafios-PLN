# Proyectos de IA aplicada al Procesamiento del Lenguaje Natural

En este repositorio podrá encontrar una serie de proyectos con soluciones a diversos desafíos propuestos, relacionados al Procesamiento del Lenguaje Natural con Inteligencia Artifical. Un recorrido por estas soluciones le permitará atravesar los temas más relevantes del NLP mediante distintos abordajes y propuestas.

A continuación, se detalla el contenido de cada una de estas soluciones:

1. **Primer desafío**
En esta carpeta encontrará la solución a un desafío relacionado con algunos de los conceptos más elementales del campo del PLN: la vectorización y la medida de similitud o similaridad. En la solución también se trabajó con modelos de clasificación (e.j. Naïve Bayes) que bien pueden ser utilizados como modelos baseline en muchas aplicaciones.

* *Conceptos clave*: vectorización, similaridad coseno, clasificación, Term Frequency-Inverse Term Frequency

* *Recursos*:

Modelo estadístico Naïve Bayes: 
$$P(y \mid x_1, \dots, x_n) = \frac{P(y) \prod_{i=1}^{n} P(x_i \mid y)}
                                 {P(x_1, \dots, x_n)}$$

Similaridad coseno:
$$\cos (\theta ) =   \dfrac {A \cdot B} {\left\| A\right\| _{2}\left\| B\right\| _{2}} $$


2. **Segundo desafío**
En este desafío se exploran algunas herramientas del pre-procesamiento de texto y del feature engineering. Se trabajan con tokenizadores y con words embeddings. Estos modelos nos permitirán lograr representaciones vectoriales de diferentes tokens de un corpus y su análisis nos ayudará a descubrir algunas interesantes propiedades de las representaciones.

* *Conceptos clave*: pre-procesamiento de texto, words embeddings, tokenizadores, word2vec

* *Recursos*:

Dos modelos de Words Embeddings:

![Words Embeddings](https://swimm.io/wp-content/webp-express/webp-images/uploads/2023/11/word2vec--1024x559.png.webp)

3. **Tercer desafío**
Esta solución abarca un tema central y de mayor importancia en el mundo del NLP: los modelos de lenguaje. En este caso, buscamos atacar un problema de principio a fin. Es decir, desde la definición del tokenizador a utilizar hasta el diseño de un modelo basado en redes recurrentes con capas LSTM, para dar respuesta a la tarea de predecir el próximo token de una cadena.

* *Conceptos clave*: modelos de lenguaje, clasificación, LSTM, perplexity

* *Recursos*:

Modelos de lenguaje: 
![Modelo de lenguaje 1](https://thegradient.pub/content/images/2019/10/Screenshot-from-2019-10-08-15-56-38-2.png)
![Modelo de lenguaje 2](https://thegradient.pub/content/images/2019/10/lm-1.png)

4. **Cuarto desafío**
En este desafío, se desarrolló un Bot conversacional utilizando una arquitectura del tipo Seq2Seq. Se implementaron y entrenaron distintos modelos utilizando redes recurrentes con capas LSTM.

* *Conceptos clave*: Seq2Seq, LSTM, tokens especiales

* *Recursos*:

Ejemplo de modelo Seq2Seq:

![Seq2Seq](https://pytorch.org/tutorials/_images/seq2seq.png)

5. **Quinto desafío**
En este último desafío, se utilizó un modelo basado en la arquitectura transformer, pre-entrenado para, aplicando técnicas de transfer learning, lograr un clasificador o analizador de sentimientos. El modelo pre-entrenado utilizado fue el modelo BERT.

* *Conceptos clave*: transformers, transfer learning, BERT model, words embeddings contextuales

* *Recursos*:

Arquitectura del modelo BERT:

![BERT architecture](https://miro.medium.com/v2/resize:fit:786/format:webp/0*ViwaI3Vvbnd-CJSQ.png)

Todas las soluciones son presentadas en formato Python Notebook.
