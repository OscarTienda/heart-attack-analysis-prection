# Análisis y Predicción de Ataques al Corazón

Este repositorio contiene Jupyter Notebooks y scripts para el análisis y predicción de ataques al corazón.

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
