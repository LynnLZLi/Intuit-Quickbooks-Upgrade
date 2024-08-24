# Intuit-Quickbooks-Upgrade

### Project Description:
In this detailed project, I was tasked with developing predictive models to target businesses for an upsell campaign for Intuit's QuickBooks software. The primary challenge was to identify which businesses, from a dataset of 75,000 that did not respond to the first wave of marketing, would likely respond to a second wave. The dataset, provided in a Parquet file, included various business attributes and response data from the first marketing wave. My responsibilities included preprocessing the data, developing predictive models using logistic regression and neural networks, and estimating potential profit from targeting specific businesses in the second wave.

### Technology Stack:
- **Data Analysis and Modeling**: Python, pandas, scikit-learn, pyrsm
- **Data Visualization**: Matplotlib
- **Version Control**: Git and GitHub for code management and collaboration

### Key Accomplishments:
1. **Data Preprocessing**:
   - Implemented one-hot encoding for categorical variables to prepare them for modeling.
   - Standardized features to ensure consistent model performance across different scales.

2. **Predictive Modeling**:
   - Developed multiple predictive models, including logistic regression and neural networks, to estimate the response probabilities for the second wave.
   - Utilized Lasso regression for feature selection to improve model accuracy and interpretability.

3. **Model Evaluation and Selection**:
   - Conducted extensive model testing and validation using AUC (Area Under the Curve) to compare different models.
   - Employed techniques like GridSearchCV for hyperparameter tuning to optimize neural network architectures.

4. **Profit Estimation**:
   - Calculated potential profit based on costs of mailing and expected revenue from successful upsells, scaling estimates from the test set to the full dataset.
   - Formulated a strategy to target businesses in the second wave based on predicted response probabilities and break-even analysis.

5. **Report and Documentation**:
   - Prepared a detailed report summarizing the methodologies, model evaluations, and business implications of the predictive models.
   - Ensured reproducibility of results by developing the report in Jupyter Notebook format and managing codebase on GitHub.

### Key Outcomes:
- **Improved Targeting Efficiency**: Successfully identified a subset of businesses with a higher likelihood of responding to the upsell campaign, potentially increasing the campaign's ROI.
- **Data-Driven Decision Making**: Enabled data-driven strategies for marketing campaign management by quantifying the impact of different variables on customer response.
- **Scalability and Adaptability**: Established a scalable modeling framework that can be adapted for future marketing campaigns with different parameters or in different contexts.
