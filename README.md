# Gradio Greet App

Una aplicación simple creada con [Gradio](https://gradio.app/) para demostrar una función básica de saludo con intensidad ajustable.

## Requisitos previos

- Python 3.8 o superior instalado en tu sistema.
- Acceso a una terminal, Símbolo del sistema o PowerShell.

## Pasos para ejecutar la aplicación

### 1. Navegar al directorio del proyecto
Abre una terminal y colócate en la carpeta principal de este proyecto:

```bash
cd c:\Users\gatom\Documents\test-neovantas\gradio_greet_app
```

### 2. Crear un entorno virtual (Recomendado)
Para mantener ordenadas las dependencias del proyecto, crea un entorno virtual de Python ejecutando:

```bash
python -m venv .venv
```

### 3. Activar el entorno virtual
Los comandos varían dependiendo de tu sistema operativo:

- **Windows:**
  ```cmd
  .venv\Scripts\activate
  ```
- **macOS / Linux:**
  ```bash
  source .venv/bin/activate
  ```
*Nota: Sabrás que el entorno está activo porque verás el prefijo `(venv)` en tu terminal.*

### 4. Instalar las dependencias
Instala los paquetes necesarios definidos en el archivo de requisitos usando `pip`:

```bash
pip install -r requirements.txt
```

### 5. Ejecutar la aplicación
Finalmente, corre el código principal desarrollado en Gradio:

```bash
python src/app.py
```

### 6. Acceder a la app
Después de ejecutar el comando y esperar a que el entorno se prepare (puede tomar unos segundos o instalar variables locales), obtendrás en la consola un texto similar a:
`Running on local URL:  http://127.0.0.1:7860/`

Ingresa esa URL en tu motor de búsqueda y navegador web favorito para interactuar con la aplicación.
