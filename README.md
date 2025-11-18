# 📊 Final Project - Edit me!

By: Krish Sah

---

This is a final project template for the IT2053C course. You can edit the `final-project.ipynb` file to complete the project.

The final project is a three part project:

- Initiation (part 1)
- Notebook (part 2)
- Presentation (part 3)

## 🚀 Quick Start

### 1. Setup Environment

In the previous assignment, you created a conda environment called `IT2053C`. If you don't have it, you can create it by running the following command:

```bash
# You must provide your 6+2 username
python scripts/setup.py --username <your_6+2_username>

# Example:
python scripts/setup.py --username gilanyym
```

Go back to the previous assignment to make sure you have set up the environment correctly.

Now, you can activate the environment in the terminal by running the following command:

```bash
# Activate your conda environment
conda activate IT2053C
```

For the final submission, you will need to make sure your notebook is organized as follows:

- Project Title
- Data set selection
- Executive summary
- Loading and file IO
- Preparation and feature engineering
- Analysis and Visualization
- Conclusions
- Appendix and References

## Analysis Plan (Markdown Summary)

### Dataset Overview

- **Dataset**: Electric Vehicle Population Data (Data.gov)
- **Why this dataset?**
  - The shift toward electric vehicles is a major trend in transportation and environmental sustainability.
  - This dataset provides detailed registration data such as make, model, location (state/city), and model year.
  - It is ideal for understanding adoption trends and regional patterns.

### Research Questions

- **Q1**: Which electric vehicle makes and models are most popular?
- **Q2**: Which states/cities lead in EV adoption?
- **Q3**: How has EV adoption changed over time based on the model year?

### Planned Visualizations

- **Bar Chart for Top EV Makes/Models**
  - Helps identify market leaders in EV popularity.
- **Choropleth Map or Bar Graph for EVs by State/City**
  - Highlights geographic concentration of EV adoption.
- **Line Chart for EV registrations over time (by model year)**
  - Illustrates how EV adoption has increased and which years show peak growth.
