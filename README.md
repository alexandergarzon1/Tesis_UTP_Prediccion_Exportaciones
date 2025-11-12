# 🚀 Tesis: Predicción del Comportamiento Exportador (UTP)
Autores: Germán Andrés Charfuelán Guancha y Alexander Garzón Rodríguez

## ⚠️ NOTA CRÍTICA: Acceso a Datos Grandes (Datasets)

Debido al tamaño de los DataFrames de exportaciones utilizados en la tesis, estos **NO** se han subido a GitHub. Los datos crudos requeridos se encuentran alojados en Google Drive.

Para que los Notebooks funcionen correctamente, siga estos 3 pasos:

### 1. Ubicación y Descarga de los Datos
Los datos crudos y preprocesados para los tres productos se encuentran en el siguiente enlace de Google Drive:
https://drive.google.com/drive/folders/1HMl0m0mrzRGNXWT97ZLGqwq2NPchTtpN?usp=drive_link

### 2. Preparación de Google Drive
Una vez acceda al enlace, debe hacer lo siguiente en su propia cuenta de Google Drive:
* Cree una carpeta llamada: **`Tesis_UTP_Datos`**.
* Copie o mueva los archivos de datos descargados dentro de su carpeta **`Tesis_UTP_Datos`**.

### 3. Conexión en Google Colab
Todos los Notebooks (`cafe/`, `rosas/`, `banano/`) están configurados para buscar los archivos de datos en la siguiente ruta estándar de Colab, después de la conexión:

```python
# CÓDIGO DE CONEXIÓN EN CADA NOTEBOOK
from google.colab import drive
drive.mount('/content/drive')

# RUTA ESTÁNDAR DE CARGA
ruta_datos = '/content/drive/MyDrive/Tesis_UTP_Datos/'
