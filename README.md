# Simulador fotovoltaico

Aplicacion en Streamlit para simular la generacion de energia fotovoltaica a partir de un dataset solar horario de la provincia de Santa Fe.

## Archivos principales

- `web.py`: interfaz web en Streamlit.
- `motor.py`: motor de calculo de irradiancia, perdidas y generacion.
- `dataset_solar_santa_fe_LOCAL.parquet`: dataset solar horario local.
- `ciudades_con_coordenadas.csv`: coordenadas de ciudades para seleccionar la ubicacion.

## Ejecutar en local

```bash
pip install -r requirements.txt
streamlit run web.py
```

## Despliegue en Streamlit Cloud

El archivo de entrada para Streamlit es `web.py`.
El dataset `.parquet` se versiona con Git LFS porque supera el limite de archivos normales de GitHub.
