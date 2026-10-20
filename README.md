# Dr. Zohreh Kaheh
https://orcid.org/0000-0002-8518-8545

**[Research website — publications, projects and teaching](https://dr-zohrehkaheh.github.io/)**

**Data Science · Machine Learning · Bayesian Modelling**  
Helsinki, Finland

I am a researcher in machine learning, Bayesian computation and operations research, with a PhD in Industrial Engineering. My work focuses on forecasting, uncertainty quantification and optimisation, with applications in supply chains, energy systems and operational decision support. My experience spans computational research, software development, university teaching and research supervision.

## Applied data science projects

| Project | Focus | Verification | Software citation / archive |
|---|---|---|---|
| [Marketplace SQL Analytics](https://github.com/DR-ZohrehKaheh/marketplace-sql-analytics) | SQL/SQLite and Python; customer segmentation, category performance and seller concentration | Nine independently reconciled SQL analyses; 36 tests; Ubuntu and Windows CI | [DOI](https://doi.org/10.5281/zenodo.23435889) · [Citation metadata](https://github.com/DR-ZohrehKaheh/marketplace-sql-analytics/blob/main/CITATION.cff) |
| [AI Delivery Risk Intelligence](https://github.com/DR-ZohrehKaheh/ai-delivery-risk-intelligence) | XGBoost delivery-risk ranking, temporal validation and Streamlit decision support | Dataset-independent tests and documented historical evaluation | [DOI](https://doi.org/10.5281/zenodo.23324488) · [Citation metadata](https://github.com/DR-ZohrehKaheh/ai-delivery-risk-intelligence/blob/main/CITATION.cff) |

Marketplace SQL Analytics combines SQL analysis with Python ingestion, validation and reporting. It processes separately obtained historical Olist data and includes input validation, reproducible reporting and explicit metric definitions. The published version focuses on descriptive analytics; production-service deployment is outside its scope. [Methods and verification](https://github.com/DR-ZohrehKaheh/marketplace-sql-analytics/blob/main/docs/VALIDATION.md).

### [AI Delivery Risk Intelligence](https://github.com/DR-ZohrehKaheh/ai-delivery-risk-intelligence)

A Python research prototype for e-commerce delivery-risk ranking and interactive decision support, developed by Zohreh Kaheh. It combines **XGBoost, scikit-learn and Streamlit** with temporal validation, probability-calibration diagnostics and bootstrap intervals for performance metrics.

The project includes single-order and batch risk scoring, a dashboard preview, research notebooks, automated tests and documented historical evaluation results. The published version is a research demonstration; operational deployment and prospective validation are outside its scope.

[Release v0.1.0](https://github.com/DR-ZohrehKaheh/ai-delivery-risk-intelligence/releases/tag/v0.1.0) · [Archived version DOI: 10.5281/zenodo.23324488](https://doi.org/10.5281/zenodo.23324488) · [Citation metadata](https://github.com/DR-ZohrehKaheh/ai-delivery-risk-intelligence/blob/main/CITATION.cff)

## Research projects with student collaborators

As project supervisor, I taught the concepts and methodology, guided the students’ initial implementations, and contributed to code improvement and validation. The four projects below credit each student collaborator and document my supervisory, methodological and software contributions.

| Project | Methods and tools | Student collaborator | Software citation / archive |
|---|---|---|---|
| [Short-term load forecasting benchmark](https://github.com/DR-ZohrehKaheh/load-forecasting-benchmark) | Chronological evaluation, past-only features, baselines, Random Forest, LightGBM, LSTM and Transformer · Python, scikit-learn, PyTorch | Lei Xing | [DOI](https://doi.org/10.5281/zenodo.23335492) · [Citation metadata](https://github.com/DR-ZohrehKaheh/load-forecasting-benchmark/blob/main/CITATION.cff) |
| [Supply-chain anomaly ranking](https://github.com/DR-ZohrehKaheh/supply-chain-risk-modelling) | Temporal, graph and hypergraph models; chronological evaluation · Python, PyTorch | Yuyang Zhang | [DOI](https://doi.org/10.5281/zenodo.23312621) · [Citation metadata](https://github.com/DR-ZohrehKaheh/supply-chain-risk-modelling/blob/main/CITATION.cff) |
| [Classification validation and scoring](https://github.com/DR-ZohrehKaheh/classification-validation) | Validation design, probability calibration and batch inference · Python, scikit-learn | Ruihan Sun | [DOI](https://doi.org/10.5281/zenodo.23312435) · [Citation metadata](https://github.com/DR-ZohrehKaheh/classification-validation/blob/main/CITATION.cff) |
| [Bayesian spatial modelling](https://github.com/DR-ZohrehKaheh/bayesian-spatial-modelling) | Native sampling, simulation and trace diagnostics · C++, Python | Jingxuan Hu | [DOI](https://doi.org/10.5281/zenodo.23312496) · [Citation metadata](https://github.com/DR-ZohrehKaheh/bayesian-spatial-modelling/blob/main/CITATION.cff) |

## Methods, contributions and citation

Each project links to its methods, execution instructions, validation record and contributor credits. The repositories distinguish research demonstrations from operationally validated applications, and historical or synthetic inputs are identified in their documentation.

For citation, use the project’s `CITATION.cff` or `CITATION.bib`. Software DOIs identify archived releases; include a commit identifier when referring to a later revision. Research publications and software have separate citations.

Source code is publicly available for review and citation. Reuse terms are documented in each repository. Technical questions can be raised through the relevant repository’s Issues page.

## Current interests

- Data quality, model evaluation and reliable analytical workflows.
- Machine learning for supply-chain analytics, energy forecasting and operational decision support.
- Bayesian inference and uncertainty-aware modelling.
- Translating technical analysis into clear, useful decisions.

