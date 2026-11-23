# HDB Resale Price Analysis

Analysis of Singapore HDB resale transactions covering **Model Prediction** (`model_prediction.ipynb`) and **Link Analysis** (`link_analysis.ipynb`).

## Requirements

- Python **3.11** (developed with **3.11.8**)
- VS Code with the Python and Jupyter extensions
- The five supplied source CSV files placed directly inside `data/`

## Setup

Open a terminal in the project root (the folder containing `model_prediction.ipynb` and `link_analysis.ipynb`).

On macOS or Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

On Windows PowerShell:

```powershell
py -3.11 -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

## Running the Notebooks

1. Open `model_prediction.ipynb` or `link_analysis.ipynb` in VS Code.
2. Select this project's `.venv` Python environment via **Select Kernel → Python Environments**.
3. Run each notebook from the project root using **Restart Kernel**, then **Run All** so all cells execute from top to bottom.