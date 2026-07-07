# 🕵️ Crime Data Analysis

**An end-to-end data analytics project uncovering patterns in crime data — from raw data to statistically validated insight to a predictive model and interactive dashboard.**

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Tableau](https://img.shields.io/badge/Tableau-Public-1f77b4?logo=tableau)](https://public.tableau.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Overview

This project walks through a complete data analysis pipeline applied to crime data, structured the way a working data analyst would approach a real stakeholder request: start from messy raw data, engineer meaningful features, validate assumptions statistically before drawing conclusions, layer in machine learning to test predictive power, and finish with visualizations built for both technical and non-technical audiences.

The goal is to move beyond descriptive statistics and answer questions such as:
- Which factors are most strongly associated with crime rates in a given area?
- Do observed differences across regions, time periods, or crime categories hold up under formal hypothesis testing, or could they be explained by chance?
- Can we build a model that reliably predicts crime-related outcomes from available features?
- How can these findings be communicated clearly to non-technical stakeholders through interactive dashboards?

---

## 🖼️ Visual Preview

**Geospatial crime distribution** — mapping incidents by location to surface regional hotspots and spatial patterns:

<p align="center">
  <img width="577" alt="Geospatial crime map 1" src="https://github.com/user-attachments/assets/8dd7d1db-60b4-46c3-8897-b3d665071f1b" />
  <img width="552" alt="Geospatial crime map 2" src="https://github.com/user-attachments/assets/e6be4ffa-a7f1-4a4c-b4e6-fb5f56f7273e" />
</p>

**Interactive Tableau dashboard** — the final, stakeholder-facing view built in Phase 5:

<p align="center">
  <img width="1600" alt="Tableau dashboard 1" src="https://github.com/user-attachments/assets/0e150bfc-0278-478d-b0aa-e40368a60b5f" />
</p>
<p align="center">
  <img width="1600" alt="Tableau dashboard 2" src="https://github.com/user-attachments/assets/af06af3b-c283-47de-8893-c704f60fabe8" />
</p>

---

## 🧭 Project Structure

The analysis is organized into five sequential phases, each in its own notebook/file so the workflow is easy to follow and reproduce:

| Phase | File | What it covers |
|-------|------|-----------------|
| 1 | [`Phase_1_Feature_engineering.ipynb`](Phase_1_Feature_engineering.ipynb) | Data cleaning, transformation, and creation of new features from raw crime data |
| 2 | [`Phase_2_Hypothesis_testing.ipynb`](Phase_2_Hypothesis_testing.ipynb) | Statistical hypothesis testing to validate relationships and trends in the data |
| 3 | [`Phase_3_Machine_Learning.ipynb`](Phase_3_Machine_Learning.ipynb) | Predictive modeling using machine learning algorithms |
| 4 | [`Phase_4_Data_Visualization.ipynb`](Phase_4_Data_Visualization.ipynb) | Exploratory and explanatory visualizations in Python |
| 5 | [`Phase_5_Tableau_Data_Visualization.twb`](Phase_5_Tableau_Data_Visualization.twb) | Interactive Tableau dashboard for stakeholder-facing insights |

Supporting document:
- [`Summary_of_Hypothesis_Testing.pdf`](Summary_of_Hypothesis_Testing.pdf) — a concise write-up of the hypotheses tested, methodology, and conclusions.

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3 |
| Data Handling | Pandas, NumPy |
| Statistical Testing | SciPy, Statsmodels |
| Machine Learning | Scikit-learn |
| Visualization | Matplotlib, Seaborn, Tableau |
| Environment | Jupyter Notebook |

> Update this table with the exact libraries imported in your notebooks so it accurately reflects your environment.

---

## 🔍 Methodology

1. **Feature Engineering** — Raw crime records are cleaned and enriched with derived features (e.g., time-based aggregations, categorical encodings, rate normalizations) to prepare the dataset for analysis.
2. **Hypothesis Testing** — Rather than relying on visual trends alone, key questions about the data are framed as formal hypotheses and tested using appropriate statistical methods, with results summarized in the accompanying PDF.
3. **Machine Learning** — A predictive model is trained and evaluated to test whether engineered features can forecast crime-related outcomes with meaningful accuracy.
4. **Visualization** — Findings are translated into clear, digestible visuals — first in Python for exploratory analysis, then in Tableau for an interactive, stakeholder-ready dashboard.

---

## 📊 Key Insights

> Replace this section with the top 3–5 findings from your analysis — this is the section recruiters and hiring managers read first. Example format below:

- **Finding 1:** [e.g., "Crime rates show a statistically significant increase during summer months (p < 0.05)."]
- **Finding 2:** [e.g., "Feature X was the strongest predictor of Y in the model, with an accuracy/F1 score of Z."]
- **Finding 3:** [e.g., "Region A consistently reports higher incidence of [crime type] compared to Region B, even after controlling for population."]

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Jupyter Notebook or JupyterLab
- (Optional) [Tableau Public](https://public.tableau.com/) to view/edit the `.twb` dashboard

### Installation
```bash
git clone https://github.com/Aryan4912/Crime-Data-Analysis.git
cd Crime-Data-Analysis
pip install -r requirements.txt
```

> Add a `requirements.txt` listing the exact packages used (e.g., `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `scipy`) so this step works out of the box.

### Running the Analysis
Run the notebooks in order for the full pipeline:
```bash
jupyter notebook Phase_1_Feature_engineering.ipynb
```
Then proceed through Phases 2–4. Open `Phase_5_Tableau_Data_Visualization.twb` in Tableau to explore the interactive dashboard.

---

## 📂 Dataset

> Add details here: source of the crime data (e.g., FBI UCR/NIBRS, a city open-data portal, Kaggle dataset), time period covered, geographic scope, and a link to the original source. This context is often the first thing a reviewer looks for.

---

## 🗺️ Roadmap / Future Work

- [ ] Expand the dataset to include more recent years
- [ ] Test additional model architectures and compare performance
- [ ] Deploy the Tableau dashboard publicly and link it here
- [ ] Add automated data pipeline / scheduled refresh

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/Aryan4912/Crime-Data-Analysis/issues).

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

> Add a `LICENSE` file to the repo if one doesn't exist yet, or update this section to match your actual license.

---

## 👤 Author

**Aryan** — [GitHub](https://github.com/Aryan4912)

If you found this project useful, consider giving it a ⭐!
