# Mushroom classification with Explainable AI (SHAP)
- project uses ML and XAI techniques to classify mushrooms as edible or poisonous based on theor physical characteristics .
---
## Dataset
- **source** : [UCI Mushrooms](https://www.kaggle.com/datasets/uciml/mushroom-classification?resource=download)
- **Desc** : 8124 mushrooms classified iointo edible or poisonous  using 22 features
---
## Model
- **Algorithm : ** Random Forest Classifier
- **Target : ** `class` (Edible=0, Poisonous=1)
---
## XAI with SHAP
- Project uses SHAP to understand the models predictions globally and locally.
---

### Key Visualiations:
- **All plots in shap_outputs folder**
- Beeswarm plots : global feature imporatancee for each class
- Waterfall plots : Local explainations for individual predictions
- Bar plot : top contributing features to poisonous classification
- Heatmap : SHAP fingerprints across many instances 
---
## Results
- Achieved high accuracy with RF.
- features like `odor`,`gill-size` and bruises heavily influenced the models decisons.
  
