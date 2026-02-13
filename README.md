# IMDb Sentiment Analysis: Data Wrangling Phase
**Data Wrangler:** Ashley Love

## 📋 Executive Summary
This repository contains the professional data engineering pipeline for the IMDb 50k dataset. The goal was to transform unstructured text into a model-ready asset for sentiment classification.

## 🛠 Features
* **Automated Ingestion:** Consolidates 50,000 text files into a master CSV.
* **NLP Normalization:** HTML stripping, punctuation removal, and lowercasing.
* **Linguistic Distillation:** Advanced stop-word removal for model optimization.
* **Audit Logs:** Forensic "Before & After" comparisons to ensure data integrity.

## 📦 Deliverables
* `01_Data_Wrangling_IMDb_Master.ipynb`: The primary processing engine.
* `imdb_model_ready_final.csv`: The final "Gold Standard" dataset (50,000 rows).
* `environment.yml`: Dependency file for quick Anaconda environment setup.

## ⚙️ Setup Instructions
1. Clone this repo.
2. Run `conda env create -f environment.yml` to install all dependencies (including WordCloud).
3. Open the notebook and run all cells.

## 📦 Data Assets
* `imdb_model_ready_final.zip`: **Primary Handoff Asset.** This contains the 50,000 distilled records. The notebook is configured to read directly from this compressed file to save disk space.
