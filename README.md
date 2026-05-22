<div align="center">
  <img src="https://github.com/user-attachments/assets/39526be9-f521-4886-acc6-a89c722d100b" width="35%" alt="Nordik Seguros Banner">

  <h1>NORDIK Seguros:  Customer Segment Intelligence Framework</h1>

  <p><i>"Decoding multi-regional customer behavioral archetypes through advanced unsupervised learning"</i></p>
  
  <br>

  [![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Unsupervised-28a745?style=flat&logo=scikit-learn&logoColor=white)](https://en.wikipedia.org/wiki/Unsupervised_learning)
  [![Data Science Pipeline](https://img.shields.io/badge/Pipeline-11--Step%20Architecture-0056b3?style=flat&logo=jupyter&logoColor=white)](https://github.com/jc-datarchitect/nordik_customer_segmentation)
  [![InsurTech Analytics](https://img.shields.io/badge/InsurTech-Customer%20Intelligence-FF9800?style=flat&logo=analytics&logoColor=white)](https://github.com/jc-datarchitect/nordik_customer_segmentation)
  [![GitHub stars](https://img.shields.io/github/stars/jc-datarchitect/TRIP-U?style=social)](https://github.com/jc-datarchitect/TRIP-U/stargazers)
</div>

---

# nordik_customer_segmentation
An enterprise-grade **Customer Segment Intelligence (CSI) framework** engineered to discover and profile latent customer behavioral archetypes for optimized housing product cross-selling strategies.

This repository deploys a production-ready, **11-stage analytical pipeline** that bridges the gap between high-dimensional transactional data and C-level commercial execution—utilizing advanced outlier isolation, PCA variance optimization, multi-metric cluster validation ($K$-Means), and generalization testing on unseen multi-regional datasets.

## Project Architecture & Insights

* **The Analytical Pipeline:** Engineers a robust 11-step computational workflow, transitioning from raw high-dimensional transactional inputs to a standardized, normalized dimensional space for model training. 
* **Advanced Governance:** Implements an automated `DataPipeline` class to ensure strict adherence to transformation logic (Log-scaling, StandardScaler, and feature engineering), eliminating training-serving skew when generalizing across unseen regional datasets.
* **Unsupervised Intelligence:** Employs $K$-Means clustering to identify five distinct behavioral archetypes, validated through a rigorous *Silhouette & Elbow* methodology to maximize intra-cluster cohesion and inter-cluster separation.
* **Commercial Application:** Bridges technical analytics with business strategy by mapping cluster-specific conversion rates, enabling data-driven identification of high-propensity segments for optimized housing insurance cross-selling.

## Key Visualizations
* **Clustering Diagnostics:** Elbow & Silhouette validation for optimal k-selection.
* **Behavioral Heatmap:** Correlation matrix highlighting multi-regional feature relationships.

---

## Technical Stack
* **Language:** Python 3.x
* **Core Libraries:** `pandas`, `numpy`, `scikit-learn`
* **Visualization:** `seaborn`, `matplotlib`
* **Architecture:** Modularized pipeline via custom `DataPipeline` class for production-ready inference.

---

## Project Structure

```text
/
├── data/                           # Contains raw datasets and intermediate processed files for model ingestion.
├── notebooks/                      # Jupyter notebooks for exploratory data analysis, visualization, and model experimentation.
├── src/                            # Core modular processing logic and ML pipeline components.
│   ├── __init__.py                 # Signals to Python that this directory should be treated as a package.
│   └── nordik_seguros_pipeline.py  # Contains the 'DataPipeline' class (cleaning, feature engineering, and model inference)
├── requirements.txt                # Essential Python dependencies to ensure environment reproducibility.
└── README.md                       # Project documentation and architectural overview.
```
