![](./imgs/logo_ecyt.png)

![](./imgs/LOGO-FactorData-Color.jpg)


# Materiales

## Docente
- [Germán Rosati](https://gefero.github.io/)
- [Tomás Maguire]()

## Presentación
El objetivo general de esta materia es brindar un acercamiento a algunas técnicas avanzadas de procesamiento de lenguaje natural para la investigación empírica.  Particularmente, se trabajará desde un enfoque conceptual (fundamentos teórico-metodológicos, casos y problemas de aplicación, etc.) y técnico (análisis de algoritmos, herramientas con interfaces gráficas, etc.).

El curso es una introducción práctica al análisis computacional de textos.

Se propone que les asistentes 
- logren comprender algunos conceptos metodológicos fundamentales para el preprocesamiento de datos textuales (tokenización, lematización, stemming, etc.) y representación vectorial clásica de textos (Term-Frequency Matrix, tf-idf, bag of words, n-gramas, etc.); 
- conozcan algunas técnicas de modelado y detección de tópicos; 
- se introduzcan a algunas técnicas modernas de representación vectorial de textos (word embeddings); 
- incorporen nociones básicas de la arquitectura Transformer en particular (attention mechanism, positional encoding, etc.)
- se familiaricen con conceptos centrales de prompting (rol, instrucciones, etc.) y algunas técnicas básicas: zero shot, few-shot, chain of thought
- realicen una primera introducción al uso programático de LLMs tanto vía servidores como de forma local 
- sean capaces de identificar situaciones de aplicación de estas técnicas en sus propias investigaciones y actividades profesionales 

## Programa
- [Programa completo de la materia - 1er. cuatrimestre 2026](https://docs.google.com/document/d/1nK7JDIDGqrSHCn1dFZdi1c0vgMl78AHg/edit?usp=sharing&ouid=118216469217227231637&rtpof=true&sd=true)


## Trabajo Final Integrador (TFI)
- **Fecha de entrega:** 15 de Junio de 2026
- [Consignas](https://docs.google.com/document/d/1Zo_dA_dIXqHEjQy0LJ9Ff7gbpJD6uG2_tcv39Dr9FEc/edit?usp=sharing)


## Consignas del 1er parcial (para consulas)
- [Consignas](./Parcial/2026_Parcial_Intro_NLP.pdf)


## Contenidos y materiales

### Unidad 5. Modelos Grandes de Lenguaje (LLMs). 
De modelos clásicos de NLP a los LLMs. Arquitectura Transformers: mecanismo de atención, encoding positionales, embeddings. Algunas generalidades sobre el entrenamiento de LLMs. Casos particulares: GPT, Gemini y Llama. Uso de LLMs vía API y uso de modelos locales. Aplicaciones para clasificación de texto y modelado de tópicos. Evaluación de fortalezas y debilidades.
- [Diapositivas - parte 1](./U5/U5_c1_Intro_NLP_Python.pdf)
- [Explicación y práctica guiada 1 - Notebook](https://colab.research.google.com/drive/12QH1ZwryZXdlHoxQEeoMjGz7Si6zqUyA?usp=sharing)

- [Diapositivas - parte 2](./U5/U5_c2_Intro_NLP_Python.pdf)
- [Explicación y práctica guiada 2 APIs - Notebook](https://colab.research.google.com/drive/1qI8u_EnQqO-xjpGGbRJi-lj_fO8LkGhH?usp=sharing)
- [Explicación y práctica guiada 3 LLMs locales - Notebook](https://colab.research.google.com/drive/140NFMeAX6z1aBThi64Gdjr4uCXWD02ag?usp=sharing)
- [Explicación y práctica guiada 4 BERTopic - Notebook](https://drive.google.com/file/d/11AUAs5Blq0HGo74QcfeuJjOpZuqi6Lir/view?usp=sharing)
- [Explicación y práctica guiada 5 Interpretabilidad en NLP - Notebook](https://colab.research.google.com/drive/1JOfFRVJzZA7QOay1sZu612GOE8ZTA_1H?usp=sharing)

### Unidad 4. ¿Cómo vectorizar texto? Episodio 2.
Una introducción a los métodos de word-embeddings (word2vec). La fórmula mágica de word2vec: skip-gram + negative sampling. Uso de embeddings como features para modelos supervisados de clasificación de texto (regresión, árboles, etc.).
- [Diapositivas - parte 1](./U4/U4_c1_Intro_NLP_Python.pdf)
- [Diapositivas - parte 2](./U4/U4_c2_Intro_NLP_Python.pdf)
- [Explicación y práctica guiada 1 - Notebook](https://colab.research.google.com/drive/159iTVf3FzBII1updM88f99W0yRle9cDM?usp=sharing)
- [Práctica independiente 1 - Notebook](https://colab.research.google.com/drive/1P8x3FLGc48biXqqdPt-ubF4lzc7T2MlS?usp=sharing)
- [Explicación y práctica guiada 2 - Notebook](https://colab.research.google.com/drive/1EpeSye8scjmQX1kSaFmLyL24LYLW778w?usp=sharing)


### Unidad 3. ¿Cómo detectar temas en corpus? 
Introducción al modelado de tópicos. Descubrimiento no supervisado de estructura temática en corpus de texto. Latent Dirichlet Allocation (LDA). Intuición general del modelo. Parámetros principales. ¿Cómo seleccionar el k (número de ´tópicos?
- [Diapositivas](./U3/U3_Intro_NLP_Python.pdf)
- [Explicación y práctica guiada 1 (sklearn) - Notebook](https://colab.research.google.com/drive/1yTTWMn3sZTaK1ihKGP1xldIvX2iazbee?usp=sharing)
- [Explicación y práctica guiada 2 (gensim) + Práctica independiente - Notebook](https://colab.research.google.com/drive/1YMCWyrZP8Qh9ZnXAVeyO62E_uqg-R8vO?usp=sharing)


### Unidad 2. ¿Cómo vectorizar textos? Episodio 1. Contando palabras y extrayendo conclusiones de un corpus. 
Bag of Words. Term-frequency matrix: conteos crudos y ponderación TF-IDF. Caso: Análisis de sentimientos sobre un corpus. Relaciones entre palabras, bigramas, n-gramas y correlaciones.
- [Diapositivas](./U2/U2_c2_Intro_NLP.pdf)
- [Explicación y práctica guiada 1 - Notebook](https://colab.research.google.com/drive/1QVTW5AM0Zh6GNOjQuCGRJyMN2cbscgTO?usp=drive_link)
- [Explicación y práctica guiada 2 - Notebook](https://colab.research.google.com/drive/1caYQk1wUXOXyLArg4cqT_-VPS7rnSE_A?usp=sharing)
- [Práctica independiente - Notebook](https://colab.research.google.com/drive/1DSaqtaHZV-7Z8u4fGOINg1Zt09VGQHRD?usp=drive_link)


- Descargar corpus y datos [![](./imgs/Download.png)](./U2/data.zip)

### Unidad 1. ¿Cómo hacer de un corpus de texto crudo algo analizable mediante métodos cuantitativos? 
Cualitativo y cuantitativo como niveles de estandarización de los datos. Preprocesamiento de texto: stopwords, lemmas y stemming. Concepto general del formato tidytext.
- [Diapositivas](./U1/U1_c1_Intro_NLP.pdf)
- [Explicación y práctica - Notebook](https://colab.research.google.com/drive/1QVTW5AM0Zh6GNOjQuCGRJyMN2cbscgTO?usp=sharing)

- Descargar corpus y datos [![](./imgs/Download.png)](./U1/data.zip)


