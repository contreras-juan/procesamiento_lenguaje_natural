# Procesamiento de Lenguaje Natural

Material de apoyo en Jupyter Notebooks para el curso **Procesamiento de Lenguaje Natural** de la Especialización en Inteligencia Artificial (UPTC): desde el preprocesamiento de texto y los modelos probabilísticos clásicos hasta Transformers y grandes modelos de lenguaje.

Autor: [Juan Felipe Contreras](https://www.linkedin.com/in/juanf-contreras/)

---

## Tabla de contenido

- [Descripción](#descripción)
- [Estructura del repositorio](#estructura-del-repositorio)
- [Módulo 1. Introducción al PLN](#módulo-1-introducción-al-pln)
- [Módulo 2. Métodos probabilísticos en PLN](#módulo-2-métodos-probabilísticos-en-pln)
- [Módulo 3. Modelos secuenciales aplicados a PLN](#módulo-3-modelos-secuenciales-aplicados-a-pln)
- [Módulo 4. Atención, convolución y modelos preentrenados](#módulo-4-atención-convolución-y-modelos-preentrenados)
- [Talleres prácticos](#talleres-prácticos)
- [Proyectos de aplicación](#proyectos-de-aplicación)
- [Cómo usar este material](#cómo-usar-este-material)
- [Requisitos](#requisitos)
- [Bibliografía](#bibliografía)

---

## Descripción

El curso ofrece una inmersión en los modelos orientados al procesamiento del lenguaje humano. Cubre el diseño, la implementación y la evaluación de algoritmos para tareas de PLN: preprocesamiento, clasificación, traducción, sumarización y respuesta a preguntas. Para ello usa tanto modelos tradicionales como modelos de vanguardia basados en redes neuronales.

El contenido está organizado en cuatro módulos de dos semanas cada uno. Cada módulo tiene cuadernos de clase, talleres prácticos con su solución y un proyecto de aplicación. A lo largo del curso se discuten las implicaciones éticas del PLN: privacidad, equidad, sesgo algorítmico, alucinaciones y transparencia.

**Requisitos de acceso:** Aprendizaje Automático, Ciencia de Datos y Aprendizaje Automático para la Toma de Decisiones, y Aprendizaje Profundo. Se espera experiencia avanzada en Python.

---

## Estructura del repositorio

```text
procesamiento_lenguaje_natural/
├── Cuadernos/              # Notas de clase (00–19), organizadas por módulo
├── Ejercicios/             # Talleres prácticos para estudiantes
│   └── Soluciones/         # Soluciones de referencia
├── Proyectos/              # Proyecto de aplicación de IA por módulo
└── img/                    # Imágenes de apoyo
```

---

## Módulo 1. Introducción al PLN

Semanas 1–2 · Ruta: [`Cuadernos/`](Cuadernos/)

| # | Cuaderno | Tema |
|---|----------|------|
| 00 | [00_Intro_PLN.ipynb](Cuadernos/00_Intro_PLN.ipynb) | Fundamentos, historia y tendencias del PLN |
| 01 | [01_Preprocesamiento_Tokenizacion.ipynb](Cuadernos/01_Preprocesamiento_Tokenizacion.ipynb) | Preprocesamiento de texto y tokenización |
| 02 | [02_Desambiguacion_Etiquetado.ipynb](Cuadernos/02_Desambiguacion_Etiquetado.ipynb) | Desambiguación y etiquetado de palabras |
| 03 | [03_Sentimiento_Regresion_Logistica.ipynb](Cuadernos/03_Sentimiento_Regresion_Logistica.ipynb) | Análisis de sentimiento con regresión logística |
| 04 | [04_Sentimiento_Naive_Bayes.ipynb](Cuadernos/04_Sentimiento_Naive_Bayes.ipynb) | Análisis de sentimiento con Naive Bayes |
| 05 | [05_Espacios_Vectoriales.ipynb](Cuadernos/05_Espacios_Vectoriales.ipynb) | Modelos de espacios vectoriales |

---

## Módulo 2. Métodos probabilísticos en PLN

Semanas 3–4 · Ruta: [`Cuadernos/`](Cuadernos/)

| # | Cuaderno | Tema |
|---|----------|------|
| 06 | [06_BoW_NGramas.ipynb](Cuadernos/06_BoW_NGramas.ipynb) | Bag-of-Words y N-gramas |
| 07 | [07_Clasificacion_NLTK.ipynb](Cuadernos/07_Clasificacion_NLTK.ipynb) | Clasificación de texto con NLTK |
| 08 | [08_HMM.ipynb](Cuadernos/08_HMM.ipynb) | Modelos ocultos de Markov (HMM) |
| 09 | [09_Viterbi.ipynb](Cuadernos/09_Viterbi.ipynb) | Algoritmo de Viterbi |
| 10 | [10_MEMM.ipynb](Cuadernos/10_MEMM.ipynb) | Modelos de Markov de máxima entropía (MEMM) |

---

## Módulo 3. Modelos secuenciales aplicados a PLN

Semanas 5–6 · Ruta: [`Cuadernos/`](Cuadernos/)

| # | Cuaderno | Tema |
|---|----------|------|
| 11 | [11_Embeddings_Redes_Neuronales.ipynb](Cuadernos/11_Embeddings_Redes_Neuronales.ipynb) | Embeddings de palabras con redes neuronales |
| 12 | [12_Word2Vec_GloVe.ipynb](Cuadernos/12_Word2Vec_GloVe.ipynb) | Word2Vec y GloVe |
| 13 | [13_RNN_LSTM_GRU_PLN.ipynb](Cuadernos/13_RNN_LSTM_GRU_PLN.ipynb) | RNN, LSTM y GRU aplicadas a PLN |
| 14 | [14_Seq2Seq.ipynb](Cuadernos/14_Seq2Seq.ipynb) | Modelo Seq2Seq |

---

## Módulo 4. Atención, convolución y modelos preentrenados

Semanas 7–8 · Ruta: [`Cuadernos/`](Cuadernos/)

| # | Cuaderno | Tema |
|---|----------|------|
| 15 | [15_CNN_Texto.ipynb](Cuadernos/15_CNN_Texto.ipynb) | Redes convolucionales para texto |
| 16 | [16_Atencion_Transformers.ipynb](Cuadernos/16_Atencion_Transformers.ipynb) | Atención y Transformers |
| 17 | [17_BERT_GPT_Fine_Tuning.ipynb](Cuadernos/17_BERT_GPT_Fine_Tuning.ipynb) | Modelos preentrenados y fine-tuning: BERT y GPT |
| 18 | [18_Aplicaciones_Preentrenados.ipynb](Cuadernos/18_Aplicaciones_Preentrenados.ipynb) | Clasificación, traducción, sumarización y respuesta a preguntas |
| 19 | [19_Etica_PLN_LLM.ipynb](Cuadernos/19_Etica_PLN_LLM.ipynb) | Ética en PLN y grandes modelos de lenguaje |

---

## Talleres prácticos

Ruta: [`Ejercicios/`](Ejercicios/)

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Taller_Sentimiento_RL_NB.ipynb](Ejercicios/01_Taller_Sentimiento_RL_NB.ipynb) | Taller práctico: análisis de sentimiento con regresión logística y Naive Bayes |
| 02 | [02_Taller_Espacios_Vectoriales.ipynb](Ejercicios/02_Taller_Espacios_Vectoriales.ipynb) | Taller práctico: espacios vectoriales |
| 03 | [03_Taller_BoW_NGramas.ipynb](Ejercicios/03_Taller_BoW_NGramas.ipynb) | Taller práctico: Bag-of-Words y N-gramas |
| 04 | [04_Taller_HMM_MEMM.ipynb](Ejercicios/04_Taller_HMM_MEMM.ipynb) | Taller práctico: HMM, Viterbi y MEMM |
| 05 | [05_Taller_Embeddings_RNN.ipynb](Ejercicios/05_Taller_Embeddings_RNN.ipynb) | Taller práctico: embeddings, RNN, LSTM y GRU |
| 06 | [06_Taller_Word2Vec_GloVe_Seq2Seq.ipynb](Ejercicios/06_Taller_Word2Vec_GloVe_Seq2Seq.ipynb) | Taller práctico: Word2Vec, GloVe y Seq2Seq |
| 07 | [07_Taller_CNN_Texto.ipynb](Ejercicios/07_Taller_CNN_Texto.ipynb) | Taller práctico: redes convolucionales para texto |
| 08 | [08_Taller_Transformers.ipynb](Ejercicios/08_Taller_Transformers.ipynb) | Taller práctico: atención, Transformers y modelos preentrenados |

### Soluciones

Ruta: [`Ejercicios/Soluciones/`](Ejercicios/Soluciones/)

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Taller_Sentimiento_RL_NB_Solucion.ipynb](Ejercicios/Soluciones/01_Taller_Sentimiento_RL_NB_Solucion.ipynb) | Solución de referencia del taller de análisis de sentimiento |
| 02 | [02_Taller_Espacios_Vectoriales_Solucion.ipynb](Ejercicios/Soluciones/02_Taller_Espacios_Vectoriales_Solucion.ipynb) | Solución de referencia del taller de espacios vectoriales |
| 03 | [03_Taller_BoW_NGramas_Solucion.ipynb](Ejercicios/Soluciones/03_Taller_BoW_NGramas_Solucion.ipynb) | Solución de referencia del taller de Bag-of-Words y N-gramas |
| 04 | [04_Taller_HMM_MEMM_Solucion.ipynb](Ejercicios/Soluciones/04_Taller_HMM_MEMM_Solucion.ipynb) | Solución de referencia del taller de HMM y MEMM |
| 05 | [05_Taller_Embeddings_RNN_Solucion.ipynb](Ejercicios/Soluciones/05_Taller_Embeddings_RNN_Solucion.ipynb) | Solución de referencia del taller de embeddings y RNN |
| 06 | [06_Taller_Word2Vec_GloVe_Seq2Seq_Solucion.ipynb](Ejercicios/Soluciones/06_Taller_Word2Vec_GloVe_Seq2Seq_Solucion.ipynb) | Solución de referencia del taller de Word2Vec, GloVe y Seq2Seq |
| 07 | [07_Taller_CNN_Texto_Solucion.ipynb](Ejercicios/Soluciones/07_Taller_CNN_Texto_Solucion.ipynb) | Solución de referencia del taller de CNN para texto |
| 08 | [08_Taller_Transformers_Solucion.ipynb](Ejercicios/Soluciones/08_Taller_Transformers_Solucion.ipynb) | Solución de referencia del taller de Transformers |

---

## Proyectos de aplicación

Ruta: [`Proyectos/`](Proyectos/)

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Proyecto_Analisis_Sentimiento.ipynb](Proyectos/01_Proyecto_Analisis_Sentimiento.ipynb) | Análisis de sentimiento para clasificación de texto |
| 02 | [02_Proyecto_Modelos_Probabilisticos.ipynb](Proyectos/02_Proyecto_Modelos_Probabilisticos.ipynb) | Modelos probabilísticos para clasificación y predicción de texto |
| 03 | [03_Proyecto_Modelos_Secuenciales.ipynb](Proyectos/03_Proyecto_Modelos_Secuenciales.ipynb) | Modelos secuenciales para clasificación y traducción de texto |
| 04 | [04_Proyecto_Transformers_Preentrenados.ipynb](Proyectos/04_Proyecto_Transformers_Preentrenados.ipynb) | Modelos de atención y preentrenados para modelado de texto |

---

## Cómo usar este material

1. Clona el repositorio:
   ```bash
   git clone https://github.com/contreras-juan/procesamiento_lenguaje_natural.git
   cd procesamiento_lenguaje_natural
   ```
2. Abre los cuadernos con Jupyter Notebook, JupyterLab, VS Code/Cursor o directamente en Google Colab (botón *Open in Colab* de cada cuaderno).
3. Se recomienda seguir el orden numérico de los cuadernos y resolver el taller de cada módulo antes de pasar al siguiente.

---

## Requisitos

Entorno recomendado con Python 3 y las siguientes librerías:

- `numpy`, `pandas`, `matplotlib`, `scikit-learn`
- `nltk`, `spacy` (PLN clásico)
- `gensim` (Word2Vec y GloVe)
- `tensorflow` / `keras` (embeddings, RNN, CNN y Seq2Seq)
- `torch`, `transformers` (versión 5 o posterior), `datasets`, `accelerate` (Hugging Face: BERT, GPT, fine-tuning y LLM). Desde su versión 5, `transformers` solo funciona con PyTorch, así que el módulo 4 usa PyTorch para los modelos preentrenados

Cada cuaderno incluye una celda `%pip install` con las librerías que necesita. Los cuadernos 17 a 19 y el taller 08 descargan modelos de cientos de millones de parámetros: se recomienda ejecutarlos en Google Colab con GPU (*Entorno de ejecución → Cambiar tipo de entorno de ejecución → T4 GPU*). Para instalar Jupyter:

```bash
pip install notebook
```

---

## Bibliografía

1. Dawani, J. (2020). *Hands-On Mathematics for Deep Learning*. Packt.
2. Foster, D. (2023). *Generative Deep Learning*. O'Reilly Media.
3. Aggarwal, C. C. (2023). *Neural Networks and Deep Learning*. Springer.
4. Zhang, A., Lipton, Z. C., Li, M. & Smola, A. J. (2020). *Dive into Deep Learning*.
5. Chollet, F. (2021). *Deep Learning with Python*. Manning.
6. Jurafsky, D. & Martin, J. H. *Speech and Language Processing*. Pearson.
7. Bird, S., Klein, E. & Loper, E. (2009). *Natural Language Processing with Python*. O'Reilly Media.
8. Tunstall, L., von Werra, L. & Wolf, T. (2022). *Natural Language Processing with Transformers, Revised Edition*. O'Reilly Media.
9. Vajjala, S., Majumder, B., Gupta, A. & Surana, H. (2020). *Practical Natural Language Processing*. O'Reilly Media.
10. Rao, D. & McMahan, B. (2019). *Natural Language Processing with PyTorch*. O'Reilly Media.
11. Thomas, A. (2020). *Natural Language Processing with Spark NLP*. O'Reilly Media.
12. Lane, H., Howard, C. & Hapke, H. (2019). *Natural Language Processing in Action*. Manning.
13. Rothman, D. *Transformers for Natural Language Processing and Computer Vision*. Packt.
14. Ozdemir, S. (2023). *Quick Start Guide to Large Language Models*. O'Reilly Media.
15. Raj, A. (2024). *Mastering Large Language Models with Python*. AVA.
16. Rothman, D. (2022). *Transformers for Natural Language Processing*. Packt.
