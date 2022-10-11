# Time_GAN-for-Energy-Data

The TimeGAN is a deep learning project that uses synthetic time series data for the GAN processing. It is implement for synthetic data for energy related
dataset.

(1) data_loading.py
Transform raw time-series data to preprocessed time-series data (Googld data)
Generate Sine data

(2) Metrics directory 

(a) visualization_metrics.py
PCA and t-SNE analysis between Original data and Synthetic data 

(b) discriminative_metrics.py
Use Post-hoc RNN to classify Original data and Synthetic data 

(c) predictive_metrics.py
Use Post-hoc RNN to predict one-step ahead (last feature)

(3) timegan.py
Use original time-series data as training set to generater synthetic time-series data

(4) main_timegan.py
Report discriminative and predictive scores for the dataset and t-SNE and PCA analysis

(5) utils.py
Some utility functions for metrics and timeGAN.
