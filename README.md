# BFT65B – A Big-Data Pipeline for Bank Failure Early Warning

**Course:** BFT65B – Big Data Analytics in Finance (National Economics University)  
**Author:** Duong Duc Hiep (Dương Đức Hiệp) – Student ID: 11230959  
**Dataset Scope:** US FDIC Call Reports (`Financials` 1984Q1–2026Q2, `Failures`, `Institutions`)

## 1. Repository Structure
- `BIGDATA.ipynb`: End-to-end pipeline (Parts 1–6) with outputs and fixed seeds (`random_state=42`).
- `requirements.txt`: Pinned library versions.
- `.gitignore`: Excludes raw and processed data files per submission rules.

## 2. How to Reproduce End-to-End
1. Open `BIGDATA.ipynb` in Google Colab (recommended) or locally with Python 3.10+.
2. Install dependencies: `pip install -r requirements.txt`
3. Mount Google Drive (or set `BASE_DIR` locally) and run all cells sequentially from top to bottom.

## 3. References & Academic Integrity Disclosure
- **Data Source:** FDIC BankFind Suite Public API (`https://api.fdic.gov/banks`).
- **Course Materials:** Dr. Nguyen Tuan Long (2026), *BFT65B – Big Data Analytics in Finance (Lectures 1–4)*, National Economics University.
- **Literature:** López de Prado, M. (2018), *Advances in Financial Machine Learning*, Wiley; Chambers, B., & Zaharia, M. (2018), *Spark: The Definitive Guide*, O'Reilly Media.
- **AI Tools Disclosure:** Generative AI (Gemini; Claude) assisted with workflow planning, code structuring/debugging, and report organization. All code was executed and verified by the author.
