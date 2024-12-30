# Interpretable Insights from Tree-Based Models using LLMs

## Project Overview

This project combines tree-based regression models and Large Language Models (LLMs) to improve electricity demand predictions and generate actionable insights. By integrating traditional machine learning techniques with LLM capabilities, the study addresses energy conservation challenges and enhances decision-making in energy management.

The project uses data from ERCOT (Electric Reliability Council of Texas), which includes information on real-time fuel mix, solar and wind power production, and locational marginal prices. Regression models such as Random Forests form the basis for accurate predictions, and LLMs are used to provide interpretable answers to critical questions about energy demand and pricing strategies.

[**Read the Full Report Here**](report.pdf)

---

## Project Status

- **Final Presentation Delivered**: Saturday, December 14, 2024

---

## Timeline

- **Milestone 1 (August 21):** Data exploration and variable identification.
- **Milestone 2 (August 28):** Data preparation and feature gathering.
- **Milestone 3 (September 7):** Initial regression modeling and LLM exploration.
- **Milestone 4 (September 25):** Research on tree-based decision-making and prompt engineering.
- **Milestone 5 (October 10):** Integration of decision trees with LLMs for insights.
- **Milestone 6 (October 20):** Refinement of LLM-generated outputs and model improvements.

---

## Objectives and Key Questions

### Addressed by Models:
- How can electricity pricing strategies impact demand?
- How do we refine state-provided demand projections?
- What factors lead to inaccuracies in state projections?

### Addressed by Data:
- Will electricity generation increase or decrease next week?
- How does the energy mix evolve seasonally?
- Is electricity demand growing year over year?

---

## Deliverables

- **Automated Prompt Generation**: Python scripts to format model outputs for LLM input.
- **Key Insights**: Enhanced understanding of LLM capabilities in answering energy-related questions.
- **Challenges Tackled**: Limitations in LLMs handling raw data and strategies to mitigate hallucinations.

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SHAP, scikit-learn
- **Models and Packages:**
  - **Regression Models:** Random Forest, Decision Tree, Linear Regression (from `sklearn`)
  - **Optimization:** GridSearchCV
  - **Interpretability:** SHAP (SHapley Additive exPlanations)
  - **Analysis Tools:** K-Nearest Neighbors (KNN)
- **Tools:** Jupyter Notebooks
- **File Formats:** JSON

---

## Challenges and Learnings

### Challenges:
- Ensuring accuracy and conciseness in LLM outputs.
- Aligning LLM interpretations with real-world scenarios.
- Overcoming LLM limitations with raw data and large datasets.

### Learnings:
1. **LLM Performance with Summarized Data**:
   - Using summarized data improved LLM accuracy compared to raw input data, measured by consistency in predicted outputs.
   - Visual aids (e.g., graphs) resulted in a reduction in misinterpretations by LLMs compared to tabular summaries.

2. **Key Model Performance**:
   - Random Forest Regressor achieved the highest predictive accuracy, with an R² score of **0.962**, a Mean Absolute Error (MAE) of **1394.32**, and a Mean Squared Error (MSE) of **3,603,917.51**.
   - Decision Tree Regressor achieved an R² score of **0.918**, an MAE of **1928.85**, and an MSE of **7,763,233.63**.

3. **SHAP Analysis**:
   - "Average Temperature (Fahrenheit)" was the most impactful feature, contributing to a **35% variance explanation** in the SHAP summary.

4. **Prompt Engineering**:
   - Refined prompts with explicit feature and variable names (e.g., "TOTAL Actual Load (MW)") increased the relevance of LLM responses.
   - Including lag features in prompts enhanced temporal pattern recognition but required external validation, which improved reliability.
