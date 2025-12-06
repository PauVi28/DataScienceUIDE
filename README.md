# 🏛️ Máster en Ciencia de Datos y Máquinas de Aprendizaje con mención Inteligencia Artificial
## Asignatura: Arquitectura, Modelado y Gestión de Datos en Data Science

### Semana 1: Fundamentos de Python para la Ciencia de Datos

---

## 🎯 Resultado de Aprendizaje de la Semana

Al finalizar esta semana, el estudiante desarrollará habilidades y competencias para ser un experto en el uso de librerías Python en procesos de análisis exploratorio, limpieza, procesamiento e ingeniería de datos.

---

## 📖 Descripción General

Este repositorio contiene los materiales teóricos, los cuadernos de Jupyter con ejercicios resueltos y un ejercicio práctico para la primera semana de la asignatura "Arquitectura, Modelado y Gestión de Datos en Data Science" del Máster en Ciencia de Datos y Machine Learning. El enfoque principal de esta semana es establecer una sólida base en Python y sus librerías fundamentales (NumPy, Pandas, Matplotlib, Seaborn) para la manipulación, el análisis exploratorio y la preparación de datos.

---

## 📚 Contenido del Repositorio

El contenido de esta semana se organiza en las siguientes secciones:

### 📄 Materiales Teóricos (PDFs)

*   `CANVAS UIDE`:
    *   Una introducción a Python como lenguaje de programación.
    *   Características clave de Python que lo hacen ideal para la Ciencia de Datos.
    *   Conceptos fundamentales de programación en Python (tipos de datos, estructuras de control, funciones, manejo de errores).
    *   Una visión general del ecosistema de librerías para Ciencia de Datos.
    *   Introducción a librerías más avanzadas de Python para el modelado de datos como Scikit-Learn, Keras, TensorFlow y PyTorch. (Nota: Estas librerías se abordarán en profundidad en futuras semanas o asignaturas, su mención aquí es a modo introductorio).

### 💻 Cuadernos de Jupyter (Notebooks)

Los cuadernos proporcionan ejemplos prácticos y ejercicios que complementan la teoría:

*   `notebooks/Sesion1_Intro_Python_Maestria.ipynb`:
    *   **Introducción interactiva a Python:** Cubre los fundamentos del lenguaje, incluyendo variables, tipos de datos (listas, diccionarios), estructuras de control (bucles, condicionales), funciones y manejo básico de errores.
    *   **Exploración de IPython:** Demuestra cómo utilizar las características interactivas de IPython (ej. `?` para documentación, `??` para código fuente) para explorar librerías.

*   `notebooks/Sesion2_Librerias_Python_DS_Maestria.ipynb`:
    *   **NumPy:** Operaciones vectorizadas y estadísticas con arrays multidimensionales, manipulación de la forma de los arrays (`reshape`) y concatenación (`np.concatenate`, `np.vstack`, `np.hstack`).
    *   **Pandas:** Creación y manipulación de DataFrames y Series, limpieza de datos (gestión de nulos, tipos de datos), agrupación (`groupby`, `agg`) y aplicación de transformaciones (`apply`). Incluye ejemplos de indexación explícita (`.loc`, `.iloc`) y combinación de DataFrames (`pd.concat`).
    *   **Matplotlib y Seaborn:** Creación de visualizaciones básicas (histogramas, barras, dispersión) con ambos estilos (estilo MATLAB y orientado a objetos), personalización de gráficos y guardado de figuras (`plt.savefig()`).
    *   **Caso práctico con el dataset Titanic:** Aplicación de los conceptos de Pandas y visualización para un análisis exploratorio de datos.

*   `notebooks/Solucion_Analisis_Transacciones_Ecommerce.ipynb`:
    *   **Solución al ejercicio autónomo de la semana:** Un ejemplo práctico de Análisis Exploratorio de Datos (EDA) de un dataset de transacciones de e-commerce (simulado). Incluye pasos detallados para:
        *   Carga y exploración inicial de datos.
        *   Limpieza y preprocesamiento de datos (manejo de nulos, tipos incorrectos, outliers, estandarización de texto).
        *   Ingeniería básica de características (cálculo de nuevas columnas).
        *   Análisis y agregación de datos para obtener insights.
        *   Visualización de datos clave utilizando Matplotlib y Seaborn.

### 📝 Evaluación y Retroalimentación

    *   Un cuestionario de 30 preguntas de opción múltiple diseñado para evaluar la comprensión de los conceptos y aplicaciones prácticas abordadas en los materiales de la semana, incluyendo retroalimentación detallada para cada opción.

---

## 🚀 Cómo Empezar

Para replicar y trabajar con este material, sigue los siguientes pasos:

1.  **Clonar el Repositorio:**
    ```bash
    git clone https://github.com/PauVi28/DataScienceUIDE.git
    cd NombreDelRepositorio
    ```

2.  **Crear un Entorno Virtual (Recomendado):**
    ```bash
    python -m venv venv
    # En Windows:
    .\venv\Scripts\activate
    # En macOS/Linux:
    source venv/bin/activate
    ```

3.  **Instalar Dependencias:**
    Instala las librerías necesarias utilizando `pip` y el archivo `requirements.txt` proporcionado:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Ejecutar Jupyter Notebook/Lab:**
    Inicia la interfaz de Jupyter para abrir y ejecutar los cuadernos:
    ```bash
    jupyter notebook
    # o si prefieres Jupyter Lab:
    jupyter lab
    ```
    Esto abrirá una nueva pestaña en tu navegador con el árbol de archivos. Navega a la carpeta `notebooks/` para abrir los cuadernos.

---

## 🛠️ Herramientas y Librerías

Este proyecto utiliza las siguientes versiones y librerías clave de Python:

*   Python 3.x
*   `pandas`
*   `numpy`
*   `matplotlib`
*   `seaborn`
*   `datetime` (módulo estándar de Python)
*   `random` (módulo estándar de Python)

---

## 👨‍🏫👩‍🏫 Autor

*   **Paulina Vizcaino** (Adaptado y complementado para fines educativos)

---

## 🤝 Contribuciones

Si tienes sugerencias, correcciones o mejoras, no dudes en abrir un *issue* o enviar un *pull request*. ¡Toda contribución es bienvenida para enriquecer este material educativo!

---

