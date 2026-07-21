# CLUB AGS 2 - "DEL MICRÓFONO AL CEREBRO ARTIFICIAL: ¡JARVIS, ESTOY MOLESTO!"

## Descripción del Club

¿Puede una máquina saber si estás enojado solo por cómo suena tu voz? ¿Es posible que un dispositivo del tamaño de una tarjeta aprenda a reconocer emociones humanas? ¿Y cómo se entrena una IA para escuchar al mundo?

En este club exploraremos cómo la inteligencia artificial puede analizar señales de audio para identificar y clasificar emociones humanas, usando dispositivos pequeños de cómputo. A partir de grabaciones de voz, aprenderás cómo las máquinas transforman sonidos en datos, extraen patrones invisibles al oído humano y toman decisiones inteligentes.

Comenzaremos con las bases: ¿qué es el sonido y cómo se representa digitalmente?, y, ¿qué es una red neuronal artificial? Después entraremos al corazón del taller: entrenaremos modelos de aprendizaje de máquina para distinguir emociones (como el enojo) a partir del audio. Para ello utilizaremos Python, herramientas y métodos actuales de ciencia de datos, trabajando con modelos de IA usados hoy en día en investigación y desarrollo tecnológico.

Finalmente, llevaremos estos modelos al mundo físico al implementarlos en dispositivos pequeños, mostrando que la IA también puede vivir fuera de grandes servidores. Al finalizar, desarrollarás un proyecto funcional: una máquina capaz de escuchar y reconocer emociones.

## Objetivos de aprendizaje

- Identificar y describir los fundamentos del procesamiento de señales de audio y las redes neuronales artificiales, comprendiendo cómo las máquinas transforman sonido en datos y extraen patrones para reconocer emociones humanas.
- Construir e implementar modelos de aprendizaje de máquina en Python —usando herramientas modernas de ciencia de datos— capaces de clasificar emociones a partir de señales de voz, aplicando técnicas de preprocesamiento, entrenamiento y evaluación de redes neuronales.
- Diseñar y demostrar un sistema funcional de reconocimiento de emociones en audio desplegado en dispositivos de cómputo de bajo consumo, integrando hardware, software e IA para enfrentar un problema real de contexto social.

## Instructores

- Hugo Mitre ([hmitre@cimat.mx](mailto:hmitre@cimat.mx))
- Rodolfo Ferro ([ferro@cimat.mx](mailto:ferro@cimat.mx))

## Programa

### Día 1 (20/07/2026)

#### 📚 Contenidos

- **Presentación del club**
    - Presentación del curso ([slides](slides/s1_presentacion_club.pdf))
- **Introducción al cómputo afectivo** ([slides](slides/s2_computo_afectivo.pdf))
    - Emociones discretas: modelo de Ekman
    - Cómputo para el reconocimiento de emociones y sus aplicaciones reales (Oura Ring, asistentes de voz, etc.)
    - Planteamiento del problema: violencia familiar en México como caso de uso
    - Motivación del hardware: conociendo el ESP32-S3 y la visión del proyecto final
- **Fundamentos de Python y herramientas** ([slides](slides/intro-python.pdf))
    - Variables, tipos de datos y estructuras de control
    - Bibliotecas clave: NumPy, matplotlib/plotly, librosa
- **Procesamiento de señales de audio (I)** ([slides](slides/s3_audio_I%20%20-%20%20Reparado.pdf))
    - ¿Qué es el sonido y cómo se representa digitalmente?
    - Frecuencia de muestreo y teorema de Nyquist
    - Transformada de Fourier Rápida (FFT) y espectrogramas
    - Coeficientes Cepstrales en las Frecuencias de Mel (MFCC)
    - Preprocesamiento de audio:
    - Eliminación de ruido (electrónico y no humano)
    - Balanceo, muestreo y filtrado de datos

> #### 📒 Notebook: Base de señales
> 
> En este cuaderno aprenderás un sobre Python, creando un vector que representa una onda de audio y generando el sonido de la misma.
>
> [![Base de señales](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RodolfoFerro/cerebroartificial/blob/main/notebooks/Base_de_se%C3%B1ales.ipynb)

> #### 📒 Notebook: Introducción a Python
> 
> En este cuaderno aprenderás sobre Python, cómo funciona y resolveremos algunos ejercicios prácticos relacionados al procesamiento de imágenes y canales de color. Para poder abrir tu cuadernillo de trabajo, pulsa en el botón a continuación.
>
> [![Introducción a Python](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RodolfoFerro/cerebroartificial/blob/main/notebooks/Introducci%C3%B3n_a_Python.ipynb)

<center>
    <img src="assets/images/cat.png" width="75%">
</center>
<br>

### Día 2 (21/07/2026)

#### 📚 Contenidos

- **Procesamiento de señales de audio (II)** ([slides](#))
    - ¿Qué es el sonido y cómo se representa digitalmente?
    - Frecuencia de muestreo y teorema de Nyquist
    - Transformada de Fourier Rápida (FFT) y espectrogramas
    - Coeficientes Cepstrales en las Frecuencias de Mel (MFCC)
    - Preprocesamiento de audio:
    - Eliminación de ruido (electrónico y no humano)
    - Balanceo, muestreo y filtrado de datos
- **Redes neuronales para clasificación de señales (I)** ([slides](slides/intro-dl.pdf))
    - ¿Qué es una red neuronal y cómo aprende?
    - Componentes principales: perceptrón, capas ocultas y funciones de activación
    - Entrenamiento: retropropagación y optimización
    - Implementación en Python y con TensorFlow

> #### 📒 Notebook: Introducción a las redes neuronales artificiales
> 
> En este cuaderno aprenderás sobre qué son y cómo operan las neuronas artificiales, desde un contexto histórico, hasta la aplicación de este tipo de modelos para la resolución de problemas interesantes. Para poder abrir tu cuadernillo de trabajo, pulsa en el botón a continuación.
>
> [![Introducción a Python](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RodolfoFerro/cerebroartificial/blob/main/notebooks/Introducci%C3%B3n_a_las_redes_neuronales_artificiales.ipynb)


## Referencias

Material para que revises:
- **[Curso de introducción a la programación científica con Python](https://futurelabmx.github.io/cdecmx/):** ¿No has programado antes? ¡No te preocupes! Este curso te dará las bases de programación con Python. El curso se divide en 3 secciones, lo básico lo encontrarás en la sección A. Python, pero será de utilidad en tu carrera como científic@ conocer las otras 2.
- **[Curso intensivo de aprendizaje automático](https://developers.google.com/machine-learning/crash-course?hl=es-419) por Google:** ¿Ya programas y quieres prepararte aún más? Te recomendamos que vayas echando un vistazo a este curso intensivo sobre Machine Learning. En este curso encontrarás ideas sobre cómo funcionan los modelos de IA en la actualidad, elementos que nos serán de utilidad durante nuestro club.
