# Predicción de colisiones de vehículos a motor en la Ciudad de Neva York.

Este repositorio hace uso de un dataset de colisiones en la Ciudad de Nueva York. Lo usa con fines de análisis y predicción. 

## Prerrequisitos

Antes de clonar el repositorio debes de tener instalado Git LFS, esto con el fin de poder descargar el dataset de manera automática.

### Instalación de Git LFS.

Si no tienes Git LFS instalado sigue estos pasos:

```bash
# Instalar LFS en Git
git lfs install
```

# Dataset
* Nombre: Motor Vehicle Collisions - Crashes
* Fuente: City of New York - Open Data
* Descripción: Información de colisiones de vehículos a motor, con información detallada sobre la colisión, como ubicación, vehículos implicados, calles, coordenadas, etc.

## Datos que contiene:

| Nombre de la columna                     | Descripción                                                                                           | Nombre del campo API             | Tipo de dato           |
|------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------|------------------------|
| CRASH DATE                               | Fecha en que ocurrió la colisión.                                                                     | crash_date                       | Floating Timestamp     |
| CRASH TIME                               | Hora en que ocurrió la colisión.                                                                      | crash_time                       | Texto                  |
| BOROUGH                                  | Distrito donde ocurrió la colisión.                                                                   | borough                          | Texto                  |
| ZIP CODE                                 | Código postal donde ocurrió el incidente.                                                             | zip_code                         | Texto                  |
| LATITUDE                                 | Coordenada de latitud para el sistema de coordenadas global, WGS 1984, grados decimales (EPSG 4326).  | latitude                         | Número                 |
| LONGITUDE                                | Coordenada de longitud para el sistema de coordenadas global, WGS 1984, grados decimales (EPSG 4326). | longitude                        | Número                 |
| LOCATION                                 | Par de coordenadas de latitud y longitud.                                                             | location                         | Ubicación              |
| ON STREET NAME                           | Calle donde ocurrió la colisión.                                                                      | on_street_name                   | Texto                  |
| CROSS STREET NAME                        | Calle transversal más cercana a la colisión.                                                          | cross_street_name                | Texto                  |
| OFF STREET NAME                          | Dirección de la calle si se conoce.                                                                   | off_street_name                  | Texto                  |
| NUMBER OF PERSONS INJURED                | Número de personas lesionadas.                                                                        | number_of_persons_injured        | Número                 |
| NUMBER OF PERSONS KILLED                 | Número de personas fallecidas.                                                                        | number_of_persons_killed         | Número                 |
| NUMBER OF PEDESTRIANS INJURED            | Número de peatones lesionados.                                                                        | number_of_pedestrians_injured    | Número                 |
| NUMBER OF PEDESTRIANS KILLED             | Número de peatones fallecidos.                                                                        | number_of_pedestrians_killed     | Número                 |
| NUMBER OF CYCLIST INJURED                | Número de ciclistas lesionados.                                                                       | number_of_cyclist_injured        | Número                 |

## Descarga manual del dataset.

URL: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data

![image](https://github.com/user-attachments/assets/67331fe0-00d3-4a6a-9b73-0ce2a5a3b132)

![image](https://github.com/user-attachments/assets/fd028e3e-a5dd-4318-a450-3d89d9ebe813)

## Uso del Dataset
* Análisis de tendencias sobre colisiones vehiculares.
* Estudiar la seguridad en las calles de la Ciudad de Nueva York.
* Aplicación de técnicas de Machine Learning para la predicción de futuros accidentes.
