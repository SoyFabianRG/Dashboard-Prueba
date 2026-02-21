# Dashboard Afluencia del Metro

Dashboard interactivo que muestra la afluencia del metro de la Ciudad de México, construido con **FastAPI**, **Chart.js** y datos desde un archivo CSV. Este dashboard usa datos hasta el 31 de enero de 2026.

https://datos.cdmx.gob.mx/dataset/afluencia-diaria-del-metro-cdmx

https://datos.cdmx.gob.mx/dataset/afluencia-diaria-del-metro-cdmx/resource/b1b48bbf-1c80-4988-8856-883b140d3fc7

## Ejecución

Para ejecutar:

```bash
chmod +x run_pipeline.sh
./run_pipeline.sh
```

El dashboard estará disponible en **http://127.0.0.1:8000**.

## Requisitos

- Python >= 3.10
- [uv](https://docs.astral.sh/uv/) (recomendado) o `pip`
