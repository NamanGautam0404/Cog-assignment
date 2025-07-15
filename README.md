# Employee Attrition Risk Dashboard

![Workflow Diagram](https://i.imgur.com/your-diagram-image.png)

A machine learning-powered dashboard that predicts employee attrition risk and provides actionable recommendations to HR teams.

## Features

- **Risk Prediction**: Decision Tree model predicts attrition probability
- **Explainable AI**: SHAP values show key contributing factors
- **Interactive Dashboard**: 
  - Employee risk profiling
  - Visual explanations
  - Custom recommendations
- **Slack Integration**: Automatic alerts for high-risk cases
- **Decision Support**: HR intervention suggestions

## Workflow

```mermaid
flowchart TD
    A[Data Loading] --> B[Preprocessing]
    B --> C[Model Training]
    C --> D[Dashboard]
    D --> E[Slack Alerts]
    E --> F[HR Actions]
