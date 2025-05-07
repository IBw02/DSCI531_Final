# Bias in AI Gaming: Final Analysis

This repository contains a comprehensive analysis of algorithmic bias in AI systems applied to gaming environments. The analysis focuses on detecting, quantifying, and mitigating gender-related biases in prediction models.

## Contents

- `Merged_Bias_in_AI_Gaming_Final.ipynb`:  
  A unified Jupyter Notebook combining all components of the project, including data preprocessing, bias analysis, model evaluation, and mitigation strategies.

## Objectives

- Identify potential biases in AI-driven recommendation or prediction systems within gaming contexts.
- Evaluate fairness using statistical measures such as statistical parity and equalized opportunity.
- Implement mitigation techniques including data reweighting, resampling, and adversarial training.
- Analyze the trade-off between accuracy and fairness.

## Methodology

The notebook is structured in the following sequence:

1. **Data Preparation**: Loading and preprocessing of input datasets.
2. **Initial Modeling**: Training baseline models to observe initial bias levels.
3. **Bias Measurement**: Quantitative analysis of model outputs by demographic groups.
4. **Mitigation Techniques**: Application of various fairness-enhancing strategies.
5. **Post-Mitigation Evaluation**: Assessing effectiveness of mitigation and summarizing outcomes.

## Tools and Libraries

- Python (Pandas, NumPy, Scikit-learn)
- Visualization: Matplotlib, Seaborn
- Fairness Metrics: Custom implementations and external libraries as applicable

## Results Summary

- Initial models demonstrated imbalanced predictions across gender groups.
- Post-mitigation models showed improved fairness with marginal trade-offs in predictive accuracy.
- Visualizations illustrate the shifts in outcome distributions and fairness metrics.

## How to Use

To reproduce the analysis:

1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
