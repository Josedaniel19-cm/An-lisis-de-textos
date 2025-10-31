# An-lisis-de-textos
Hecho por: Jose Daniel Cabarcas Mass

Contexto general

En la actualidad, el volumen de información textual disponible en medios digitales, redes sociales, artículos científicos y portales de noticias crece exponencialmente. Este contexto ha impulsado el desarrollo de técnicas de Procesamiento de Lenguaje Natural (NLP, por sus siglas en inglés), disciplina que combina la lingüística computacional con la inteligencia artificial para permitir que las computadoras comprendan, interpreten y analicen lenguaje humano de manera automatizada.

El análisis de textos constituye una de las aplicaciones más representativas de esta área. Permite extraer información significativa, identificar patrones lingüísticos, analizar sentimientos, resumir documentos o incluso generar contenido de manera automatizada. En este trabajo, se aplican técnicas básicas de NLP utilizando el lenguaje Python y la librería spaCy, una de las más potentes y versátiles para el tratamiento del lenguaje natural.

2. Propósito del trabajo

El propósito del trabajo es aplicar técnicas de procesamiento y análisis textual para comparar dos textos de forma estructurada, desde la limpieza inicial hasta la identificación de sus elementos lingüísticos más relevantes.
El estudiante pondrá en práctica la normalización, tokenización, lematización, eliminación de stopwords, análisis gramatical (POS tagging) y extracción de relaciones semánticas mediante tripletas Sujeto–Verbo–Objeto (SVO), utilizando las herramientas del ecosistema Python.

A través de este ejercicio, se busca que el estudiante comprenda cómo transformar texto en datos analizables, desarrollar competencias básicas en NLP y obtener conclusiones interpretativas sobre el contenido y estilo de los textos procesados.

3. Objetivos
Objetivo general

Realizar un análisis comparativo de dos textos utilizando técnicas de procesamiento de lenguaje natural, identificando sus características lingüísticas, palabras predominantes y estructuras gramaticales más representativas.

Objetivos específicos

Cargar y limpiar dos textos independientes, eliminando ruido y formatos innecesarios.

Describir y comparar la estructura de ambos textos (párrafos, oraciones y palabras).

Aplicar tokenización, eliminación de stopwords y lematización.

Analizar la frecuencia de términos y generar nubes de palabras para visualizar los temas predominantes.

Implementar el etiquetado gramatical (POS tagging) para identificar sustantivos, verbos y adjetivos frecuentes.

Extraer tripletas Sujeto–Verbo–Objeto (SVO) y analizar las relaciones semánticas que revelan.

4. Metodología

El trabajo se desarrolla en Python, empleando principalmente la librería spaCy para el análisis lingüístico, junto con otras herramientas complementarias como:

NLTK: para la gestión de stopwords.

WordCloud: para generar visualizaciones de frecuencia de palabras.

Matplotlib y Seaborn: para la representación gráfica de los resultados.

TextBlob: para análisis semántico básico y procesamiento de texto.

El procedimiento se compone de las siguientes etapas:

Carga de textos: lectura de los archivos .txt con los textos seleccionados.

Normalización: limpieza de etiquetas HTML, URLs, signos, emojis y caracteres extraños.

Análisis descriptivo sin spaCy: conteo de párrafos, oraciones y palabras.

Procesamiento con spaCy: tokenización, lematización y filtrado de stopwords.

Visualización: generación de nubes de palabras y conteo de términos frecuentes.

POS tagging: análisis gramatical para extraer sustantivos, verbos y adjetivos dominantes.

Extracción de tripletas SVO: detección de relaciones semánticas para identificar estructuras de significado.

Comparación e interpretación: observación de diferencias y similitudes entre ambos textos.

5. Importancia del trabajo

El procesamiento de lenguaje natural es una de las habilidades más relevantes en la ciencia de datos contemporánea, ya que permite extraer conocimiento de fuentes no estructuradas como textos, comentarios o artículos.
Mediante este trabajo, el estudiante adquiere competencias esenciales para transformar texto en información cuantificable, comprender las bases lingüísticas del análisis de datos y aplicar técnicas de NLP en contextos académicos y profesionales.

Además, el ejercicio fomenta la capacidad crítica y analítica, al permitir comparar textos desde una perspectiva objetiva, basada en la evidencia lingüística más que en la interpretación subjetiva.

6. Resultados esperados

Al finalizar el trabajo, el estudiante será capaz de:

Cargar, limpiar y preparar textos para su análisis computacional.

Aplicar técnicas básicas de NLP con spaCy y librerías complementarias.

Identificar las palabras más representativas y su relevancia dentro del texto.

Comprender las categorías gramaticales y su función en la estructura de las oraciones.

Generar visualizaciones (nubes de palabras y tablas de frecuencia) que permitan comparar textos.

Extraer y analizar tripletas SVO para interpretar el significado central de cada documento.

7. Estructura del trabajo

El documento está organizado en las siguientes secciones:

Introducción.

Carga de librerías y lectura de textos.

Limpieza y normalización.

Análisis descriptivo sin spaCy.

Procesamiento con spaCy (tokenización y lematización).

Visualización y nubes de palabras.

Análisis gramatical (POS tagging).

Extracción de tripletas SVO.

Conclusiones y observaciones comparativas.
