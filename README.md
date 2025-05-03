# Keyword Spotting for Historical Documents

## Overview
This project implements a machine learning approach for spotting keywords in historical documents from the George Washington Database. The system finds similar words based on visual appearance rather than text content.

## Project Structure
- `data/`: Contains raw and processed datasets
- `src/`: Source code for data processing, feature extraction, model training, and evaluation
- `notebooks/`: Jupyter notebooks for exploration and visualization
- `scripts/`: Standalone scripts for running the pipeline
- `configs/`: Configuration files

## Setup
1. Create a virtual environment: `python -m venv kws-env`
2. Activate it: `source kws-env/bin/activate` (Unix) or `kws-env\Scripts\activate` (Windows)
3. Install dependencies: `pip install -r requirements.txt`

## Usage
- Data preparation: `python scripts/prepare_data.py`
- Model training: `python scripts/train_model.py`
- Model evaluation: `python scripts/evaluate_model.py`

## Results
(Summary of results will be added after completion)

## Contributors
- Raunak Pillai


# 8. Create .gitignore file
cat > .gitignore << EOF
# Python
__pycache__/
*.py[cod]
*.class
*.so
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
*.egg-info/
.installed.cfg
*.egg

# Jupyter Notebook
.ipynb_checkpoints

# Virtual Environment
kws-env/
venv/

# Data
data/processed/

# Models
*.pth

# VS Code
.vscode/

# PyCharm
.idea/

# Mac OS
.DS_Store
