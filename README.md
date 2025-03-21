# AI Agent for Data Science Workflow Automation

This project builds an AI agent that automates various tasks in the data science workflow, including data preprocessing, model selection, hyperparameter tuning, model training, and report generation. It integrates with any given data source, enhancing productivity.

## Installation
To install the required dependencies, use the following command:

```bash
pip install -r requirements.txt
```

### Connecting to Hugging Face
To authenticate with Hugging Face, use the following:
```python
from huggingface_hub import notebook_login
notebook_login()
```

## Features
- **Automated Data Preprocessing**: The agent handles cleaning and transforming your dataset.
- **Intelligent Model Selection**: Based on your dataset, the agent suggests the appropriate model.
- **Hyperparameter Tuning**: The agent optimizes hyperparameters for the selected model to improve performance.
- **Seamless Report Generation**: Automatically generates detailed reports on model performance and analysis results.
- **Multi-framework Integration**: Works with popular machine learning frameworks, including scikit-learn and XGBoost.

## License
This project is licensed under the MIT License.
