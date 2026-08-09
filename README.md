# Jing-Zhi Chen
 
**Data Science undergraduate @ Soochow University, Taiwan** · Graduating June 2027
 
---
 
## Featured Projects
 
### [mlb-pitch-framing-analysis](https://github.com/jameschen108/mlb-pitch-framing-analysis)
1.06M called pitches, 2021–2023. A GAM over pitch location supplies the counterfactual
("what would an average catcher get called here?"), and the residual is framing. The
unadjusted leaderboard tracks Baseball Savant at r = 0.99 — but once catcher, umpire and
pitcher effects have to compete for the same residual, umpire-to-umpire variation
(τ = 0.233) comes out larger than catcher variation (τ = 0.192). Split-half reliability
0.82, year-over-year 0.60.
 
`Python` · `rossed random effects` · `ogistic GAM` · `Statcast`
 
---
 
### [food-calorie-vlm](https://github.com/jameschen108/food-calorie-vlm)
Fine-tuning improved recognition unambiguously (item F1 0.358 → 0.607, p < 0.0001) and
±20% calorie accuracy from 8.8% to 40.4%. Mean absolute error did **not** significantly
improve — its confidence interval crosses zero, because a handful of internally
inconsistent references dominate the mean. Freezing the vision tower still recovers 82% of
the F1 gain, which places the improvement on the language side rather than in visual
features. Runs end to end on a free Colab T4; the evaluation harness is CPU-only and tested.

`PyTorch` · `Qwen2-VL` · `LoRA` · `Hugging Face`
 
---
 
### [tw-stock-lstm-evaluation](https://github.com/jameschen108/tw-stock-lstm-evaluation)
An LSTM forecaster for Taiwan-market equities, evaluated the way a trading desk would:
rolling-origin forecasts and a Sharpe-ratio backtest rather than in-sample RMSE.
 
`TensorFlow/Keras` · `pandas` · `NumPy`
 
---
 
### [santander-transaction-prediction](https://github.com/jameschen108/santander-transaction-prediction)
Kaggle binary classification on 200 anonymized features. MLP with 5-fold stratified
cross-validation; ‹AUC score› on the public leaderboard.

`TensorFlow/Keras` · `scikit-learn`
 
---
 
## Technical Skills
 
| | |
|---|---|
| **Languages** | Python, SQL, R |
| **Statistical Methods** | regression, time-series analysis, hypothesis testing, cross-validation design |
| **ML & Deep Learning** | XGBoost, LSTM, SHAP, transfer learning, LoRA fine-tuning |
| **Data & Tools** | pandas, NumPy, TensorFlow/Keras, PyTorch, LangChain, Git |
 
---
 
