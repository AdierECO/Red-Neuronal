<h1 align="center">🎭 Sistema de Reconocimiento de Emociones</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/Flask-3.0.2-green" alt="Flask">
  <img src="https://img.shields.io/badge/TensorFlow-2.16.1-orange" alt="TensorFlow">
</p>

<div align="center">
  <img src="https://example.com/ruta-a-tu-demo.gif" width="600" alt="Demo del proyecto">
</div>

<h2>📌 Descripción</h2>
<p>Aplicación web que clasifica emociones faciales usando una red neuronal convolucional (CNN) entrenada con TensorFlow/Keras y una interfaz Flask.</p>

<h2>🚀 Instalación</h2>

```bash
# 1. Clonar el repositorio
git clone https://github.com/tuusuario/proyecto-emociones.git
cd proyecto-emociones

# 2. Crear entorno virtual (Windows)
python -m venv venv
venv\Scripts\activate

# 3. Instalar dependencias
pip install -r requirements.txt

<h2>⚙️ Configuración</h2><ol> <li><strong>Prepara tu dataset</strong>: <ul> <li>Crea carpetas para cada emoción en <code>dataset/train/</code>: <pre> dataset/ └── train/ ├── feliz/ ├── triste/ ├── enojado/ ├── sorpresa/ └── neutral/</pre> </li> <li>Coloca mínimo <strong>50 imágenes por categoría</strong> (formato JPG/PNG)</li> </ul> </li> <li><strong>Entrenamiento del modelo</strong>: <pre>python app.py --action train</pre> </li> </ul><h2>🖥️ Uso</h2>
# Iniciar la aplicación Flask
python app.py

<p>Accede a la interfaz web en: <a href="http://localhost:5000">http://localhost:5000</a></p><h3>Funcionalidades:</h3> <ul> <li><strong>Entrenar modelo</strong>: Sube imágenes y entrena la red neuronal</li> <li><strong>Predecir emociones</strong>: Sube una foto para analizar</li> </ul><h2>📂 Estructura del Proyecto</h2><pre> proyecto-emociones/ ├── app.py # Aplicación principal Flask ├── model_utils.py # Lógica de la red neuronal ├── static/ # Archivos CSS/JS ├── templates/ # Vistas HTML ├── dataset/ # Carpeta para imágenes (no incluida en repo) └── model/ # Modelos entrenados (generados automáticamente) </pre><h2>⚠️ Notas Importantes</h2><ul> <li>El dataset <strong>no está incluido</strong> en el repositorio (ver <code>.gitignore</code>)</li> <li>Los modelos entrenados se guardan en <code>model/</code> (ignorados por Git)</li> <li>Requerimientos mínimos: 4GB RAM, GPU recomendada para entrenamiento</li> </ul><h2>📄 Licencia</h2> <p>MIT License - Libre para uso académico y comercial.</p><div align="center"> <p>✉️ <strong>Contacto</strong>: tu@email.com | 🌐 <a href="https://github.com/tuusuario">GitHub</a></p> </div> ```
