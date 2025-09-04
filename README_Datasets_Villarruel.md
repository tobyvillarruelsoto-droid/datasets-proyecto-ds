# Datasets - Avance 1 (Tobias Villarruel)

Este paquete contiene los archivos iniciales que podés subir a tu repositorio de GitHub para la preentrega: el notebook y un script para descargar los datasets.

## Archivos
- `Datasets_Villarruel_upload_ready.ipynb` : Notebook listo para cargar/descargar los datasets.
- `download_datasets.py` : Script Python para descargar los CSVs localmente.
- `README_Datasets_Villarruel.md` : este archivo (instrucciones).

## Datasets (URLs raw)
- Ames Housing: https://raw.githubusercontent.com/austinlasseter/hosting_some_files/main/pandas_files/iowa.csv
- Airbnb NYC: https://raw.githubusercontent.com/Siddharth1698/New-York-City-Airbnb-Data-Case-Study/main/AB_NYC_2019.csv
- FIFA players: https://raw.githubusercontent.com/ifrankandrade/data-visualization/main/datasets/players_21.csv

## Cómo usar
1. Descargá los archivos a tu máquina o abre el notebook en Google Colab.

2. Ejecutá `python download_datasets.py` para descargar los CSVs a la carpeta actual.

3. Subí los CSVs resultantes y el notebook a tu repo de GitHub (Add file → Upload files).


## Nota
Si preferís no descargar los CSVs y solo usar las URLs raw dentro del notebook, podés reemplazar `pd.read_csv('ames.csv')` por `pd.read_csv('<url_raw>')` en las celdas correspondientes.

