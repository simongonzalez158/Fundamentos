# Fundamentos de la Ciencia de Datos - TPE

Este proyecto contiene el Trabajo Práctico Especial (TPE) de la materia **Fundamentos de la Ciencia de Datos**. Incluye análisis y preprocesamiento de datos, así como un archivo de Jupyter Notebook (`TPesp.ipynb`) y el informe en formato PDF.

## Contenidos

- `TPesp.ipynb`: Código principal en Python.
- `tpeamb`: Ambiente virtual (no incluido en GitHub, pero puede ser creado con `requirements.txt`).
- `requirements.txt`: Dependencias necesarias para el proyecto.
- `winequality_BDS.csv`: Archivo de datos necesario para el análisis.
- `informe.pdf`: Informe detallado con los resultados y análisis.



## Instalación

### 1. Clonar el repositorio

Clona el repositorio desde GitHub a tu máquina local. Abre la terminal y ejecuta:

```bash
git clone https://github.com/simongonzalez158/Fundamentos
cd Fundamentos
git checkout master
```
### 2. Crear y activar el ambiente virtual: 

Es recomendable usar un ambiente virtual para instalar las dependencias. Puedes crearlo y activarlo de la siguiente manera:
En Windows:

```bash
python -m venv tpeamb
tpeamb\Scripts\activate
```
En macOS y Linux:

```bash
python3 -m venv tpeamb
source tpeamb/bin/activate
```
### 3. Instalar las dependencias

Una vez activado el ambiente virtual, instala las dependencias necesarias con:

```bash
pip install -r requirements.txt
```
### 4. Ejecutar el Notebook

Asegurarse de que winequality_BDS.csv esté en la misma carpeta del proyecto antes de ejecutar el Notebook.
Abre el archivo TPesp.ipynb en Jupyter Notebook o Jupyter Lab para ejecutar el código paso a paso.

Este proyecto incluye código en Python para el preprocesamiento de datos y la reducción de dimensionalidad. 
