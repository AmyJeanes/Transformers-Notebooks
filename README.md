# Maya voice model

# First time setup

## Create virtual environment

```bash
python -m venv .venv
```

## Activate virtual environment

## Windows

### PowerShell

```bash
.venv\Scripts\Activate.ps1
```

### Command Prompt
```bash
.venv\Scripts\activate.bat
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Install PyTorch

Go to https://pytorch.org/get-started/locally/ and pick the appropriate CUDA platform for your system e.g. CUDA 13.0 and run the install command provided, e.g. for CUDA 13.0:

```bash
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu130
```

## Running the notebook

Open this repository folder in VSCode and open `main.ipynb`. Make sure the virtual environment is selected as the interpreter (top right corner). Then run the cells in order to generate audio. The generated audio files will be displayed and optionally saved in the `output` folder.