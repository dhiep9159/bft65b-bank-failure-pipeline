# BFT65B – A Big-Data Pipeline for Bank Failure Early Warning

**Course:** BFT65B – Big Data Analytics in Finance (National Economics University)  
**Author:** Duong Duc Hiep (Dương Đức Hiệp) – Student ID: 11230959  
**Dataset Scope:** US FDIC Call Reports (`Financials` 1984Q1–2026Q2, `Failures`, `Institutions`)  
**Data Snapshot Date:** 2026-11-26

## 1. Repository Structure
- `BIGDATA.ipynb`: End-to-end pipeline (Parts 1–6) with saved outputs and fixed seeds (`random_state=42`).
- `requirements.txt`: Pinned Python package versions.
- `.gitignore`: Excludes raw/processed data files (`.csv`, `.parquet`) and model artifacts per submission rules.

## 2. How to Reproduce End-to-End

### Option A: Google Colab (Recommended)
1. Upload `BIGDATA.ipynb` to Google Colab.
2. Select **`Runtime` → `Run all`** to execute all cells sequentially from top to bottom.
3. Section `1.1` automatically mounts Google Drive and creates `/content/drive/MyDrive/bft65b_project/`.

### Option B: Local Machine (Python 3.10+, Java 11/17 for PySpark)
1. Install pinned dependencies:
   ```bash
   pip install -r requirements.txt
