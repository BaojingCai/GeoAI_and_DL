# GeoAI_and_DL
### GeoAI and Deep Learning Seminar

* inputdata downloaded from https://gigamove.rwth-aachen.de/de/download/1c33dae908eb51ad17b224e27c63e1c0

*  inputdata stored in folder data/raw Mbezi_With_Kiporo_ycbr.tif, Mlalakua_Merged_PPK_ycbr.tif and Msimbazi_Merged_ycbr.tif
(only stored locally, because datasets are too large)

### Creation of virtuell environment
```bash
python -m venv venv
```
### activation with powershell
```bash
venv/bin/activate
```
### install packages
```bash
pip install -r requirements.txt
```
or
```bash
pip install -r requirements.txt -v
```

### code organization with branches

* `main` for stable code and merging from dev
* `dev`  for development and merging from testing branches
* `testing` for own testing
