### Rodrigo Grandez

**Quantitative Economist | Time Series, Nowcasting & Machine Learning | Data Science for Prices, Credit & Risk**

I forecast inflation and build nowcasting and machine learning models from high-frequency data at the
Central Reserve Bank of Peru (14+ years). I care about statistical rigor: out-of-sample evaluation,
reproducible pipelines and models that decision-makers can trust. I also teach Machine Learning in the
MSc in Artificial Intelligence at UPC.

**Projects**

| Project | What it shows | Result |
|---|---|---|
| [peru-inflation-nowcasting](https://github.com/Rodgrandez/peru-inflation-nowcasting) | Nowcasting monthly Lima CPI inflation from daily BCRP data: U-MIDAS, Almon-MIDAS, Ridge, LASSO, XGBoost and a forecast combination, expanding-window evaluation with Diebold-Mariano tests | Headline: combination RMSE 3.5% below AR (p = 0.098), but only 0.9% below an AR with inflation expectations; core: nothing beats the AR → daily data add little beyond expectations |
| [lima-food-prices-pipeline](https://github.com/Rodgrandez/lima-food-prices-pipeline) | Daily data pipeline for Lima wholesale food prices (MIDAGRI-SISAP): chunked download, published data-quality checks, price-pressure and shock indicators, and a [live Plotly.js dashboard](https://rodgrandez.github.io/lima-food-prices-pipeline/) | 59 varieties tracked daily since 2010 (359,680 clean observations); isolated source glitches removed (79) while real price moves are kept |
| [credit-risk-pd-validation](https://github.com/Rodgrandez/credit-risk-pd-validation) | PD scorecard (WoE logistic), XGBoost challenger, LGD, lifetime expected loss and a second-line [validation report](https://github.com/Rodgrandez/credit-risk-pd-validation/blob/main/reports/validation_report.pdf) on 36-month Lending Club loans | Out-of-time AUC 0.639 vs 0.661 for Lending Club's grade; PD under-predicts out of time (calibration ratio 0.890) → recalibration recommended |
| [bank-account-fraud-detection](https://github.com/Rodgrandez/bank-account-fraud-detection) | Fraud detection on 1M bank account applications (Feedzai BAF): strictly time-based validation, cost-based and budget-based alert decisions, calibration, fairness audit by age, drift monitoring and a [model card](https://github.com/Rodgrandez/bank-account-fraud-detection/blob/main/reports/model_card.md) | Recall 0.58 on unseen months with a threshold set for 5% false positives (6.2% realised; +0.06 vs logistic at equal FPR); flags legitimate 50+ applicants 2.3x as often -> approve with conditions |

**Publications**
- [A high frequency indicator of credit in Peru: A Random Forests and dynamic network connectedness approach](https://doi.org/10.1016/j.latcb.2026.100204) — *Latin American Journal of Central Banking* (2026)
- [Nowcasting and Backcasting Credit with Mixed-Frequency Data and Machine Learning: Evidence from Peru](https://doi.org/10.2139/ssrn.5408526) — SSRN Working Paper (2025)
- [Machine learning methods to forecast inflation in Peru](https://www.bcrp.gob.pe/docs/Publicaciones/Revista-Moneda/moneda-200/moneda-200-01.pdf) — *Revista Moneda* No. 200, BCRP (2024, in Spanish)
- [A Leading Indicator for the Peruvian Economic Real Activity](https://www.bcrp.gob.pe/docs/Publicaciones/Documentos-de-Trabajo/2017/documento-de-trabajo-01-2017.pdf) — BCRP Working Paper No. 2017-01 (2017)

**Tools:** Python (pandas, scikit-learn, XGBoost, PyTorch) · R · SQL · MATLAB · EViews · Git · Plotly Dash · Power BI

[Website](https://rodgrandez.github.io) · [LinkedIn](https://www.linkedin.com/in/grandez-rodrigo/) · [Email](mailto:rodfra123@gmail.com)
