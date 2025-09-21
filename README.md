# Ad Campaign ROI Prediction

## ***Notebook***: 
> `ad_campaign_roi.ipynb`
----

## ***Purpose***:
> <b>Load an advertising dataset, preprocess (clean, One‑Hot encode, scale), train a RandomForestRegressor and report R² / RMSE and feature importances.</b>
----

## Files
- `ad_campaign_roi.ipynb` — main notebook
- `advertising_dataset.csv` — expected dataset (place in same folder)

## Prerequisites
- Windows machine
- Python 3.8+ (recommended)
- Git (for repository operations)
- Visual Studio Code with the Python and Jupyter extensions (optional, recommended)

## Quick setup (PowerShell)
1. Create and activate a virtual environment:
````powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
````
2. Install required packages:
````powershell
pip install --upgrade pip
pip install -r requirements.txt
````
3. Register a Jupyter kernel (so VS Code/Jupyter can select the env)
````powershell
python -m ipykernel install --user --name "ad-campaign" --display-name "Ad Campaign ROI (venv)" 
