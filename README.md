# CHC-ML-NBA-Draft-Predictor
### Assessing the Predictive Accuracy of Machine Learning Models in NBA Draft Player Evaluation

**Thesis PDF:** *Link will be added upon completion*

## Abstract

Evaluating amateur basketball talent represents a tough challenge for professional sports franchises, where dependence on human intuition often conflicts with the prospering of quantitative, real-time performance data. This thesis investigates the effectiveness of traditional, readily-available machine learning models in predicting National Basketball Association (NBA) career success. This study was evaluated by a combination of:
- Value Over Replacement Player (VORP)
- Win Shares per 48 minutes (WS/48)

The  datasets used utilized data from the National Collegiate Athletic Association (NCAA) and NBA performance box-scores from the seasons of 1991-92 until 2016-2017. We iteratively evaluated six traditional regressor model architectures: 
- Random Forest
- XGBoost
- K-Nearest Neighbors
- Multi-layer Perceptron
- LightGBM
- ExtraTrees

To preserve the chronological integrity of the draft process, we used a Walk-Forward Validation approach. This allowed us to ensure that every model was trained only on the data available prior to a particular draft year. Our results show us that while raw-box score statistics provide poor baseline predictions, the adoption of an individual player-efficiency based feature set in addition to physical metadata significantly improved model stability and ordinal logic. Throughout our study, professional NBA General Managers (GMs) maintained a consistent lead over most models in talent prediction accuracy. However, our findings suggest that traditional ML models have rapidly developed to being able to effectively separate tiers of talent within a draft class, offering a potent arsenal for noise reduction in the turbulent modern scouting process.

# Setup Instructions

1- Clone the repository:
```bash
git clone https://github.com/ohosman04/CHC-ML-NBA-Draft-Predictor.git
```
2- Open and run the notebook
```bash
Collab_NotebookFinal.ipynb
```
Execute all cells in order to reproduce data preprocessing, model training, evaluation, and visualizations.
