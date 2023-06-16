# Autores
- César Fernández García
- Oscar Tienda Beteta

# Análisis y Predicción de Ataques al Corazón

Este repositorio contiene Jupyter Notebooks y scripts para el análisis y predicción de ataques al corazón.

La estructura del proyecto es la siguiente:

    code/
        heart-attack-analysis-prediction.ipynb       # código a ejecutar
    datasets/
            heart.csv                                # dataset original
            heart_cleaned.csv                        # dataset preprocesado
            heart_reducted_pca.csv                   # dataset reducción dimensionalidad con ACP
            heart_reducted_rfe.csv                   # dataset reducción dimensionalidad con RFE
    .gitignore
    README.md
    requirements.txt                                 # librerías necesarias para ejecutar el código
    Deliverable_TIPOLOGIA_PRA2.pdf                   # documento con las respuestas a las preguntas de la práctica


## Configuración del Entorno

Para trabajar en este proyecto, necesitarás crear un entorno virtual de Python y activarlo. Este proceso aislará las dependencias de este proyecto de tus otros proyectos de Python.

Sigue estos pasos para configurar tu entorno:

1. **Instala Python**: Este proyecto requiere Python. Si aún no lo tienes instalado, puedes descargarlo desde [python.org](https://www.python.org/).

2. **Clona el repositorio**: Clona este repositorio a tu máquina local utilizando `git clone`.

3. **Crea el entorno virtual**: En la raíz del proyecto, crea un entorno virtual utilizando el siguiente comando:
   
    ```bash
    python -m venv hearth-attack-env
    ```

4. **Activa el entorno virtual**: Una vez creado, necesitas activar el entorno virtual. El comando varía dependiendo de tu sistema operativo.

   En Windows:

    ```bash
    .\hearth-attack-env\Scripts\activate
    ```

   En Unix o MacOS:

    ```bash
    source hearth-attack-env/bin/activate
    ```

5. **Instala las dependencias**: Con el entorno virtual activado, instala las dependencias necesarias para este proyecto utilizando el archivo `requirements.txt` que se encuentra en la raíz del repositorio.

    ```
    pip install -r requirements.txt
    ```

6. **Inicia Jupyter Notebook**: Finalmente, puedes iniciar Jupyter Notebook para abrir y trabajar con los notebooks disponibles en este repositorio.

    ```bash
    jupyter notebook
    ```

Recuerda siempre activar el entorno virtual antes de trabajar en el proyecto (`source hearth-attack-env/bin/activate` o `.\hearth-attack-env\Scripts\activate` dependiendo de tu sistema operativo). Cuando hayas terminado de trabajar, puedes desactivar el entorno virtual con el comando `deactivate`.

## Abrir Jupyter Notebook con Visual Studio Code

Una vez que hayas iniciado el servidor de Jupyter Notebook, puedes trabajar con los notebooks directamente en Visual Studio Code. Para hacerlo, sigue estos pasos:

1. **Obtén el enlace del servidor de Jupyter Notebook**: Cuando inicias el servidor de Jupyter Notebook desde la terminal, deberías ver un mensaje que contiene un URL. Copia este URL.

2. **Abre Visual Studio Code**: Lanza Visual Studio Code y abre el archivo Jupyter Notebook (`code/heart-attack-analysis-prediction.ipynb`).

3. **Conéctate al servidor de Jupyter Notebook**: En la parte superior derecha de la ventana del Jupyter Notebook, haz clic en el botón "Select Kernel". En el menú desplegable, selecciona la opción "Select Another Kernel". Luego, selecciona la opción "Existing Jupyter Server". Cuando se te pida que proporciones el URL del servidor de Jupyter, pega el URL que copiaste en el primer paso.

4. Si te pide un usuario, déjalo blank y pulsa Enter.

Ahora puedes editar y ejecutar celdas de Jupyter Notebook directamente desde Visual Studio Code.
