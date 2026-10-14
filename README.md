# Tripmate-ai-a-multi-agent-for-travel-planner

## How to run ?
### Windows with Python (no Conda required)
Use Python 3.12. If you already created `.venv` with another Python version, remove that environment before recreating it.

1. Create and activate the virtual environment in PowerShell:
```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
```

If PowerShell blocks the activation script, allow scripts for this terminal session only, then activate:
```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\.venv\Scripts\Activate.ps1
```

2. Install the requirements:
```powershell
python -m pip install -r requirements.txt
```

### Using Conda
Conda must be installed before these commands will work. If PowerShell says `conda` is not recognized, install Miniconda or Anaconda, then open a new terminal (or use the Anaconda Prompt).

1. Create and activate the environment:
```powershell
conda create -n travel python=3.12 -y
conda activate travel
```

2. Install the requirements:
```powershell
python -m pip install -r requirements.txt
```

