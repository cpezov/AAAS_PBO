# Dataset

Dataset was obtained from the [Pseudo Boolean Competition](https://www.cril.univ-artois.fr/PB16/).  

The file data.rar contains the following files:
- data_features.csv : contains, for all 3128 instances, the domain-specific features' values for the non-linearized versions of the instances, the timestep, and the solver with the best performance for that <instance,timestep> pair (label).
- data_features_linear.csv : contains, for all 3128 instances, the domain-specific features' values for the linearized versions of the instances, the timestep, and the solver with the best performance for that <instance,timestep> pair (label).

# Machine Learning Models

We implemented Machine Learning models in Python using the scikit-learn library.  

The models using domain-specific features use the csv files in the dataset directory as input ("_linear" models use data_features_linear.csv, while the rest of the models use data_features.csv).

# Citation

Pezo, C., Hochbaum, D., Godoy, J., & Asin-Acha, R. (2024). Automatic Algorithm Selection for Pseudo-Boolean Optimization with Given Computational Time Limits. Computers and Operations Research, accepted.
