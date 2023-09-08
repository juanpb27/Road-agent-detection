# Detección, clasificación y seguimiento de agentes viales en vídeos urbanos

Este proyecto se enfoca en detectar, clasificar y seguir agentes viales en vídeos obtenidos de cámaras de seguridad urbanas. Se utilizó un modelo pre-entrenado de YOLOv8 y se adaptó al dataset específico, el cual consiste en frames extraídos de los vídeos mencionados.

## Instalación

1. **Clone el repositorio**:
    ```bash
    git clone https://github.com/juanpb27/Road-agent-detection
    cd object_detection
    ```

2. **Cree un entorno virtual** (opcional pero recomendado):
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: .\venv\Scripts\activate
    ```

3. **Instale las dependencias**:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. **Abra Visual Studio Code**:
    ```bash
    code .
    ```

2. En Visual Studio Code, navegue al archivo `Soporte.ipynb` y siga las instrucciones contenidas allí para ejecutar y experimentar con el modelo.