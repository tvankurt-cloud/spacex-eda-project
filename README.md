# 🚀 SpaceX Falcon 9 Launch EDA

Explore and analyze SpaceX Falcon 9 launch data to uncover patterns, visualize key metrics, and prepare the dataset for machine learning applications focused on landing prediction.

![Landing Success Rate](images/landing_success_chart.png)

---

## 📖 Overview

This repository contains an end-to-end Exploratory Data Analysis (EDA) workflow for SpaceX launches. You'll collect, clean, and explore real-world launch data, generate mission-critical insights, and prepare labels for future predictive modeling.

---

## 📁 Project Structure

```
spacex-eda-project/
│
├── data/
│   └── dataset_part_1.csv
│   └── dataset_part_2.csv
│
├── notebooks/
│   └── 1_data_collection.ipynb      # Gathers raw data from SpaceX API
│   └── 2_eda_and_labeling.ipynb     # Cleans and analyzes launch data, creates label columns
│
├── images/
│   └── launch_site_distribution.png
│   └── landing_success_chart.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ✅ Features

- Pulls launch data via the SpaceX API
- Cleans and normalizes with pandas
- Visualizes launch sites, payloads, and outcomes
- Creates binary landing success labels for ML
- Ready for extending to feature engineering and modeling

---

## 🏃 Quickstart

<details>
<summary>Get started in a few steps</summary>

1. **Clone the repository**
    ```bash
    git clone https://github.com/tvankurt-cloud/spacex-eda-project.git
    cd spacex-eda-project
    ```
2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```
3. **Run notebooks**
    Open `notebooks/` in Jupyter and execute each notebook step by step.

</details>

---

## 📊 Notebooks

- **1_data_collection.ipynb**  
  *Fetches and saves SpaceX launch data from API as CSVs*

- **2_eda_and_labeling.ipynb**  
  *Explores key metrics (launch site, payload, outcomes) and creates label columns for ML*

Outputs: See visualizations in the `images/` folder (e.g. ![Launch Site Distribution](images/launch_site_distribution.png)).

---

## 🧪 Next Steps

- Feature engineering
- Model training and evaluation

---

## 💾 Requirements

- Python >=3.8
- pandas
- numpy
- matplotlib
- seaborn
- requests

Install all dependencies:
```bash
pip install -r requirements.txt
```

---

## 👤 Author

GitHub: [tvankurt-cloud](https://github.com/tvankurt-cloud)

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Contributions and suggestions are welcome! Please open an issue or submit a pull request.
