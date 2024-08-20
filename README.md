# Explainability-in-RUL-prediction


Report on
“Explainability in process outcome prediction: Guidelines
to obtain interpretable and faithful models”
from
Alexander Stevens and Johannes De Smedt
European Journal of Operational Research (2024)
Presented by Mjema Christina John
COSC 590D Graduate Seminar
2024S1-2
The University of British Columbia
Kelowna
August 20, 2024


Abstract

In Operations Research and Business Process Management, process modeling is
critical for identifying inefficiencies and optimizing resource allocation. This study
delves into predictive process monitoring, particularly process outcome prediction,
where the aim is to foresee the outcomes of ongoing business process cases. While
recent advancements in machine learning and deep learning have enhanced predictive
capabilities, the opacity of complex “black box” models poses significant challenges for
interpretability and trustworthiness.
This paper addresses these challenges by introducing new model-agnostic explain-
ability metrics that assess interpretability and faithfulness. These metrics are applied to
a broad range of machine learning models, including Logistic Regression (LR), Random
Forests (RF), XGBoost(XGB), Long Short-Term Memory networks (LSTM), Convolu-
tional Neural Networks (CNN), Logit Leaf Model (LLM), and Generalized Linear Rule
Model (GLRM). The results underscore the trade-offs between predictive performance
and interpretability, revealing that while deep learning models often excel in accuracy,
their explanations lack faithfulness. Conversely, although slightly less accurate, simpler
models provide more interpretable and trustworthy explanations.
As an extension to the work presented in this paper, we apply these metrics to
evaluate models in predicting the Remaining Useful Life (RUL) of oil wells. The
metrics are reformulated to reflect the regression problem and then used to compare the
performance and interpretability of Linear Regression, XGB, CNN, and LSTM networks.
The results show that deep learning models using attention explainers achieve a better
balance in predictive performance and interpretability compared to traditional machine
learning models.
