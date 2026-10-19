# Spatial Join Without ArcGIS

This Jupyter Notebook performs spatial analysis and mapping using open-source Python libraries (**GeoPandas**, **Shapely**, and **Folium**). It fetches public feature data directly from ArcGIS REST endpoints using **Requests**, bypassing the need for the proprietary `arcgis` library or an ArcGIS Online login.

---

## Prerequisites

Make sure you have **Python 3.8 or higher** installed on your system. 

If you are using **Geospatial libraries** (like GeoPandas) for the first time, it is strongly recommended to use **Conda/Mamba** or create a clean virtual environment to manage complex C-library dependencies (like PROJ and GEOS).

---

## Setup Instructions

Using pip and a Virtual Environment

Open your terminal or command prompt, navigate to your project directory, and create a virtual environment:

```
python -m venv venv
```
Activate the environment:

Windows:

```
venv\Scripts\activate
```

macOS / Linux:

```
source venv/bin/activate venv
```
Upgrade pip and install the dependencies from the requirements.txt file:

```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Launching the Notebook
Ensure your environment (venv) is activated.


Launch JupyterLab:

```
jupyter lab
```