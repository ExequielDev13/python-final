# Proyecto Final de Python

Este repositorio contiene el proyecto final de Python donde se realizaron todos los pasos manuales para crear un entorno virtual, usar Git y subir el proyecto a GitHub, tal como indica la consigna.

---

## Pasos realizados

```bash
# Crear la carpeta del proyecto y entrar en ella
mkdir python-final
cd python-final

# Iniciar un repositorio Git
git init

# Crear el archivo principal de Python
touch finales.py

# Abrir Visual Studio Code en la carpeta actual
code .

# Verificar la versión de Python instalada
python -V
# o
python3 -V

# Crear un entorno virtual para aislar dependencias
python3 -m venv venv

# Activar el entorno virtual
# En Linux o Git Bash:
source venv/bin/activate

# En Windows (CMD o PowerShell):
venv\Scripts\activate

# Actualizar el gestor de paquetes pip
python3 -m pip install --upgrade pip

# Agregar todos los archivos al repositorio local
git add .

# Hacer el primer commit con un mensaje descriptivo
git commit -m "Primer commit"

# Conectar el repositorio local con el remoto en GitHub
git remote add origin https://github.com/ExequielDev13/python-final.git

# Subir los cambios al repositorio remoto en la rama main
git push -u origin main


¿Qué es pip y por qué se actualiza?
pip es el gestor de paquetes de Python. Permite instalar, actualizar y desinstalar librerías y paquetes externos que no vienen incluidos por defecto con Python, como por ejemplo Flask, Requests o Pandas.

Actualizar pip es importante para contar con la versión más reciente, que incluye mejoras, correcciones de errores y compatibilidad con las últimas versiones de paquetes. Esto ayuda a evitar problemas durante la instalación o uso de librerías.

Autor
Exequiel Abraham
Fecha: Junio 2025
GitHub: ExequielDev13