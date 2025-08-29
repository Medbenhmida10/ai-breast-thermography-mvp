# Ai-breast-thermography-mvp

This repository hosts the **MVP (Minimum Viable Product)** for an 
AI-assisted thermography solution in breast cancer screening.

## 🔬 Purpose
- Explore thermographic imaging as a **non-contact, portable screening tool**.
- Develop a **deep learning CAD (Computer-Aided Diagnosis)** pipeline.
- Evaluate feasibility and accuracy of models on public datasets.

## 📂 Project Structure
- `notebooks/` — Colab & Jupyter experiments (training, visualization).
- `data/` — Placeholder for synthetic/test data .
- `results/` — Experimental results, PDFs, charts.
- `docs/` — Documentation, literature reviews, and related resources.

## ⚙️ Features
- Preprocessing: Temperature normalization, breast ROI segmentation, grayscaling, resizing ...
- Model: ResNet18 with Grad-CAM for explainability.
- Evaluation: Accuracy, Sensitivity, Specificity.
- Charts & visual storytelling for technical presentations.

## 📌 Issues & Projects
We use **GitHub Issues** for bug tracking & tasks, 
and **Projects** for roadmap visualization.

## Quick Start

1. Clone repo:  
git clone https://github.com/Medbenhmida10/ai-breast-thermography-mvp.git
cd ai-breast-thermography-mvp

2. Install dependencies:
- `pip install -r requirements.txt`  
- or (Conda) `conda env create -f environment.yml && conda activate breast-thermo-mvp`

3. Prepare dataset folder (example placeholder):
   mkdir data/DMR-IR

4. Launch the Colab notebooks:
- `notebooks/ResNet18_MVP.ipynb` – full pipeline with preprocessing, training, eval, visuals

5. View results in `results/` and read the detailed report in `reports/`.

6. Track tasks via the GitHub **Projects** board.



## ⚠️ Disclaimer
This MVP is for **research & prototyping only**.  
No real patient-sensitive data is stored here.
