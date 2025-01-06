## Notebooks en Google Colab

En este repositorio, utilizamos **Google Colab** como plataforma para ejecutar los Notebooks de Python. Google Colab es una herramienta gratuita basada en la web que permite escribir y ejecutar código Python de manera interactiva. Colab proporciona acceso a entornos de ejecución con recursos de computación gratuitos, lo que lo convierte en una excelente opción para proyectos de análisis de datos y aprendizaje automático.

### ¿Qué es Google Colab?

**Google Colab** es un servicio basado en la nube que permite ejecutar Jupyter Notebooks de manera interactiva, sin necesidad de instalar nada en tu equipo. Ofrece las siguientes ventajas:

- **Acceso gratuito a GPUs**: Puedes utilizar recursos de GPU para acelerar el procesamiento de tus proyectos.
- **Interactividad en tiempo real**: Permite ejecutar código, visualizar gráficos y agregar texto explicativo todo en el mismo documento.
- **Facilidad de uso**: Al ser una plataforma basada en la web, solo necesitas un navegador y una cuenta de Google para empezar a trabajar.
- **Colaboración**: Puedes compartir Notebooks fácilmente con otras personas, permitiendo que trabajen en el mismo proyecto de manera colaborativa.

### Cómo utilizar Google Colab

1. **Abrir un Notebook en Google Colab**: 
   - Para abrir un Notebook desde este repositorio, simplemente ve a [Google Colab](https://colab.research.google.com/).
   - Luego, selecciona **"Abrir desde GitHub"** e ingresa la URL de este repositorio para cargar los Notebooks directamente en Colab.

2. **Ejecutar celdas**:
   - Una vez dentro del Notebook, puedes ejecutar las celdas de código simplemente presionando el botón de "play" al lado de cada celda o utilizando el atajo de teclado `Shift + Enter`.

3. **Guardar y compartir**:
   - Los Notebooks en Colab se guardan automáticamente en tu cuenta de Google Drive, lo que te permite acceder a ellos desde cualquier lugar. Además, puedes compartirlos con otros mediante enlaces de Google Drive o descargar los archivos como `.ipynb`.

4. **Montar Google Drive**:
   - Para cargar datos directamente desde tu Google Drive, puedes montar tu unidad de Google Drive en Colab con el siguiente comando:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

### Beneficios de usar Google Colab

- **Acceso a recursos computacionales gratuitos**, como CPU y GPU, sin necesidad de configuración adicional.
- **Colaboración en tiempo real**, permitiendo que varios usuarios trabajen en el mismo Notebook simultáneamente.
- **Integración con Google Drive**, lo que facilita el almacenamiento, acceso y compartir archivos.
