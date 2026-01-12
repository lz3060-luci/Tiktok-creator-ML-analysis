# Tiktok-creator-ML-analysis
Machine learning analysis of TikTok creator profiles using text mining and tree-based models.
This project investigates whether profile-level textual and behavioral features
encode sufficient signal to predict TikTok creator visibility in the absence
of video-level content.

## Methods
- Text preprocessing and TF-IDF vectorization
- Logistic Regression, Random Forest, and XGBoost
- Model comparison using ROC-AUC and accuracy

## Key Findings
- Engagement metrics are the strongest predictors of high-follower status
- Bio text provides additional predictive signal
- Tree-based models outperform linear models

## Files
- notebooks/: analysis project
- report/: final project report
- data/: Tiktok data source

- ## Team Project & Contribution

This project was completed as part of IEOR 4523 (Data Analytics) in a team of six.

My primary responsibility was the machine learning and modeling components of the project, including:
- Designing and implementing the main predictive framework
- Training and evaluating logistic regression models with standardized numeric and TF-IDF text features
- Building and interpreting tree-based models, including Random Forest and Gradient Boosting
- Conducting model comparison using accuracy, F1-score, and ROC-AUC
- Analyzing feature importance to identify key drivers of creator popularity
- Contributing to the writing and editing of the final report, particularly the modeling and results sections

Other team members contributed to data collection, data clearning, XGBoosting modeling, and exploratory analysis.

