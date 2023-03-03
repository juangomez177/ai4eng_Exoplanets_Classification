# ai4eng_Exoplanets_Classification
## Miembros del grupo
Juan José Gomez Mejia, CC 99051217248, Ingeniería de Sistemas

## Datos
Los datos del proyecto vienen del sitio web Kaggle, con nombre Kepler Exoplanet Search Results, proporcionados por la NASA; son datos obtenidos por el telescopio espacial Kepler lanzado en 2009 durante casi 1 década que duró la misión espacial. Se pueden hacer disponibles ejecutando desde cualquier notebook de Google Colab con los siguientes comandos:
```
# Instalación del paquete de Kaggle
!pip install -U -q kaggle

# Creación de un directorio para las credenciales de Kaggle
# (Deberá tener sus credenciales de usuario en un archivo kaggle.json y subirlo)
# Si no lo tiene, vaya a su perfil de Kaggle/Account/API/Create New API Token
!mkdir -p ~/.kaggle
from google.colab import files
files.upload()
!cp kaggle.json ~/.kaggle/

# Descarga del dataset desde Kaggle a Google Colab
# (Deberá copiar el API command del dataset que desea descargar, generalmente está cerca del boton descargar localmente)
!kaggle datasets download -d nasa/kepler-exoplanet-search-results
```
