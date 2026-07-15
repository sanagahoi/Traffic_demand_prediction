# Traffic Demand Prediction (Flipkart Gridlock 2.0 Challenge)

Welcome! This repository contains our machine learning approach for the **Flipkart Gridlock 2.0 Hackathon** hosted on HackerEarth. The challenge—organized in collaboration with the Bengaluru Traffic Police—tasks participants with building data-driven solutions to predict and manage urban traffic congestion.

Instead of relying on idealized simulations, this project tackles the real thing: leveraging historical spatial-temporal data to forecast traffic demand patterns across Bengaluru's real-world road networks.

---

## What's Inside

*   **`Traffic_demand_prediction.ipynb`** — The core of the project. It handles everything from initial data cleaning and exploratory analysis to feature engineering and final model training.
*   **`e88186124ec611f1.zip`** — The archived dataset and submission assets provided during the hackathon.

---

## Engineering Approach

Traffic isn't random—it follows geographic and temporal patterns. Our solution focuses on extracting clean signals from chaotic urban data:

*   **Spatial Analysis:** Mapping traffic demand across specific localized grids (geohashes) to pinpoint structural bottlenecks.
*   **Temporal Features:** Capturing time-of-day cycles, day-of-the-week variations, and rolling historical averages to predict when demand will spike.
*   **Model Training:** Implementing regression and time-series techniques optimized for a solid balance between fast training times and high predictive accuracy.
*   **Validation:** Iterating on performance using $R^2$ scores and Root Mean Squared Error (RMSE) to ensure the predictions hold up reliably against real-world traffic flows.

---

## Getting Started

### Prerequisites

To run the notebook, you'll need Python 3.8+ along with standard data science libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
``` 
Setup & Execution
Clone this repository:

``` Bash
git clone [https://github.com/sanagahoi/Traffic_demand_prediction.git](https://github.com/sanagahoi/Traffic_demand_prediction.git)
cd Traffic_demand_prediction
```
Extract the dataset:

```Bash
unzip e88186124ec611f1.zip
```

Open the Jupyter notebook to see the full pipeline in action:

```Bash
jupyter notebook Traffic_demand_prediction.ipynb
```
### Acknowledgments
A big shoutout to Flipkart, the Bengaluru Traffic Police, and HackerEarth for organizing a challenge that addresses real, impactful infrastructure problems.
