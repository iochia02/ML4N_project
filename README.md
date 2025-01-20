# ML4N_project
This project is developed by Braidotti Sara, Iorio Chiara, Pani Matteo and Sapia Cristian during the 2024 edition of the ML4N course in the Cybersecurity Master's degree at Politecnico di Torino.

## Files
- **1-visualization.ipynb** - data exploration (1.1 and 1.2): all the graphs and metrics we produced to better understand our dataset.
- **2-preprocessing.ipynb** - preprocessing phase (1.3 and 1.4): label-encoding, correlation analysis, scaling, PCA, ECDF of the new features, and dimensionality reduction by removal of highly correlated features.
- **3-supervised_learning.ipynb**: supervised learning (section 2): models' training with default parameters, hyper-parameter tuning, choice of the best model and its investigation.
- **4-unsupervised_learning.ipynb**: unsupervised learning (section 3): models' training, hyper-parameter tuning and general clusters analysis.
- **5-cluster_analysis.ipynb**: cluster explainability and analysis (section 4): cluster distribution of traffic types, permutation importance and attack pattern investigation.
- **pca_dataset.csv**: dataset after performing preprocessing and PCA.
- **preprocessed_dataset.csv**: dataset after performing preprocessing and dimensionality reduction by removing the most correlated features.
- **results_eps_DBSCAN.csv, results_mins_DBSCAN.csv, dbscan_values.csv and dbscan_values.csv**: intermediate results of the hyper-parameter tuning of DBSCAN, used only not to have to repeat every time this process to create new plots.