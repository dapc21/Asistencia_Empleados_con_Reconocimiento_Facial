## 📘 Guía de Instalación en Windows para el Proyecto

# 🔧 1. Requisitos previos

✅ Instala las librerías de Visual Studio C++ Build Tools necesarias:

👉 Descargar Visual Studio C++ Build Tools

<p align="center"> <img width="876" height="378" alt="binarioscmasmas" src="https://github.com/user-attachments/assets/e9725afe-5e83-4e26-b81f-a42dae7b59f5" /> </p>

# 🐍 2. Activar entorno virtual

✅ Abre una terminal PowerShell y ejecuta:

```bash
PS C:\Users\TU_USUARIO_DE_WINDOWS> .\OneDrive\Desktop\Python\.venv\Scripts\activate
```


💡 Esto asegura que los paquetes se instalen en tu entorno virtual de Python.

✅ Verifica en PyCharm:
Settings → Project:Python → Python Interpreter → Python Path.

<p align="center"> <img width="971" height="483" alt="PyCharm" src="https://github.com/user-attachments/assets/514fadbd-f4eb-466d-b168-7aa7c620bf9c" /> </p>

# 📦 3. Instalación de paquetes necesarios

✅ Con el entorno activado, instala los paquetes:

```bash
pip install cmake
pip install https://github.com/omwaman1/dlib-for-python3.13.2/releases/download/dlib/dlib-19.24.99-cp313-cp313-win_amd64.whl
pip install face_recognition
pip install opencv-python
```

# ⚠️ 4. Posibles advertencias

❌ Si aparece el error:

ModuleNotFoundError: No module named 'face_recognition_models'


✅ Solución:

```bash
pip install face_recognition_models
```


❌ Si el warning persiste incluso después de instalarlo…

✅ Prueba con pip3:

```bash
pip3 install setuptools
```

🎉 ¡Instalación completada!

Ya deberías tener tu entorno configurado y funcionando correctamente 🚀

❌ Si el warning persiste incluso después de instalarlo...

✅ Prueba con pip3:

```bash
pip3 install setuptools
```

