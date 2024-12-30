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
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SHAP
- **Tools:** Jupyter Notebooks
- **File Formats:** JSON

---

## Challenges and Learnings

### Challenges:
- Ensuring accuracy and conciseness in LLM outputs.
- Aligning LLM interpretations with real-world scenarios.
- Overcoming LLM limitations with raw data and large datasets.

### Learnings:
- LLMs perform best with summarized data and visual aids.
- Feature importance analysis highlights "Average Temperature" as a critical predictor.
- Combining regression models with LLMs yields actionable, interpretable insights.
