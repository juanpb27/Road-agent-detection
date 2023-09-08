# Detección, Clasificación y Seguimiento de Agentes Viales en Vídeos Urbanos

Este proyecto tiene como objetivo detectar, clasificar y seguir agentes viales en vídeos obtenidos de cámaras de seguridad urbanas. Se utilizó un modelo pre-entrenado de YOLOv8 adaptado a un dataset específico, compuesto por frames extraídos de dichos vídeos.

## Requisitos Previos:
- **Python**: [https://www.python.org/downloads/](https://www.python.org/downloads/)
- **Git**: [https://git-scm.com/](https://git-scm.com/)
- **Visual Studio Code**: [https://code.visualstudio.com/](https://code.visualstudio.com/)

## Instalación y Configuración:
1. **Clonar el repositorio**:
   ```
   git clone https://github.com/juanpb27/Road-agent-detection
   cd Road-agent-detection
   ```

2. **Crear y activar un entorno virtual** (opcional, pero recomendado):
- En sistemas Unix (Linux/macOS):
  ```
  python3 -m venv venv
  source venv/bin/activate
  ```

- En Windows:
  ```
  python -m venv venv
  .\venv\Scripts\activate
  ```

3. **Instalar las dependencias**:
   ```
   pip install -r requirements.txt
   ```

Uso del Proyecto:

1. Abrir el proyecto en Visual Studio Code:
   ```
   code .
   ```

2. Una vez en Visual Studio Code, navegue al archivo 'Soporte.ipynb'. Este notebook contiene las instrucciones y celdas de código para experimentar con el modelo.