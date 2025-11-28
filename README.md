# GeoAI_and_DL
### GeoAI and Deep Learning Seminar

* input data downloaded from https://gigamove.rwth-aachen.de/de/download/1c33dae908eb51ad17b224e27c63e1c0

*  input data stored in folder data/raw Mbezi_With_Kiporo_ycbr.tif, Mlalakua_Merged_PPK_ycbr.tif and Msimbazi_Merged_ycbr.tif
(only stored locally, because datasets are too large)

* the grid for patch creation is dowloadable under this link and was created with QGIS: https://heibox.uni-heidelberg.de/f/0d18484e9b224e77acc5/ <br>locally stored under data/grid/grid_daressalam_5m.gpkg

### Creation of virtual environment
```bash
python -m venv venv
```
### Activation with PowerShell
```bash
venv/Scripts/activate
```
### Install packages
```bash
pip install -r requirements.txt
```
or
```bash
pip install -r requirements.txt -v
```

### Code organization with branches

* `main` for stable code and merging from dev
* `dev`  for development and merging from testing branches
* `testing` for own testing

### Workflow

![Workflow](illustrations/Workflow_DL_daressalam.drawio.png)


