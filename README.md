# Restaurant Health Inspection Risk Prediction Model

This project uses machine learning to predict restaurant health inspection outcomes using Mecklenburg County inspection data, census features, geocoding, and business type classification.

## Quick Setup

1. Create a Python 3.11.15 environment  
2. Install packages:

pip install -r requirements.txt

3. Place `VW_PUBLIC_ESTINSP2015-2024_merged.csv` in the same folder as `health_inspection.ipynb`

## Run the Project

Open and run:

`health_inspection.ipynb`

## Optional: Skip Long Processing Steps

To skip geocoding, census pulls, and Ollama classifications, extract:

`skip data processing.rar`

into the same folder as the notebook.

## Ollama Requirement

If you are not using the skip-processing files, install Ollama and make sure Llama 3.2 is available.

Example:

ollama run llama3.2

## Output

The notebook trains the model, evaluates results, and exports saved model artifacts.
