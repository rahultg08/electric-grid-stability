# Predicting electric grid stability
Dataset: UCI's simulated 
[Electrical Grid Stability data](https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+) 
to predict if a given combination of power system conditions would result in an unstable grid - and therefore risk 
causing blackouts or damaging equipment.

I then created a simple streamlit app
that can be used to see how adjusting model inputs affect the resulting predictions

The [Colab notebook](https://github.com/rahultg08/electric-grid-stability/blob/master/grid_stability.ipynb) goes through data exploration and 
feature selection, followed by model fitting, tuning, testing and pickling.
