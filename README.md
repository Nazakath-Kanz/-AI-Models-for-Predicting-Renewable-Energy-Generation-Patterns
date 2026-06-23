# AI Models for Predicting Renewable Energy Generation Patterns

##  Overview
This project develops deep learning models to forecast **solar photovoltaic (PV) generation** and **smart grid load demand** using real‑world datasets.  
It demonstrates an **end‑to‑end ML workflow**: data preprocessing, feature engineering, model training (LSTM, GRU, Transformer), benchmarking, interpretability (attention heatmaps), hyperparameter tuning, and deployment via a **Gradio dashboard**.

## Repository Structure
- `Renewable_Energy_Forecast.ipynb` → Main Colab notebook with all cells (data prep → training → deployment).
- `pv_forecasting_model.keras` → Pretrained PV forecasting model.
- `smartgrid_forecasting_model.keras` → Pretrained Smart Grid forecasting model.
- `datasets/` → Contains PV and Smart Grid datasets (ZIP). The model is trained to run the datasets as .zip files and not .csv files.
- `docs/` → Academic report (`Renewable_Energy_Forecasting_Report.docx`) and supporting documentation.
- `requirements.txt` → Python dependencies.
- `README.md` → Project documentation.

## Setup
Clone the repository:
```bash
git clone https://github.com/Nazakath-Kanz/-AI-Models-for-Predicting-Renewable-Energy-Generation-Patterns.git
cd -AI-Models-for-Predicting-Renewable-Energy-Generation-Patterns
