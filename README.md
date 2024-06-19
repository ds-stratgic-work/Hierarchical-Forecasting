# Hierarchical-Forecasting
### Intro
Time series datasets often have complex structures with various levels or hierarchies of aggregation. These hierarchies can include categories, brands, or geographical groupings. In order to make informed decisions and plans, it is crucial to have consistent forecasts across these different levels. Hierarchical Forecast provides different reconciliation methods that ensure coherent forecasts across hierarchies. This Python-based framework aims to close the gap between statistical modeling and Machine Learning in the field of time series analysis.

### Features used - Nixtla Higherarchical Forecast Models
#### Reconciliation techniques:
- Bottom Up: Basic summation at higher tiers.
- Top Down:  Propagates forecasts from the highest tiers down the hierarchies.
Innovative reconciliation approaches:
- Middle Out: Centralized: Establishes the foundation predictions at an intermediate level. The tiers above the foundation predictions adopt the ascending method, while the tiers below utilize a descending approach.
- Min Trace: Trace Minimization: Reduces the overall forecast discrepancy within the set of consistent forecasts, employing the Minimum Trace reconciliation.

### Installation required
- The installation of HierarchicalForecast's Python package index can be installed with pip
- !pip install hierarchicalforecast


Additional packages required for the following example are statsforecast and datasetsforecast. In case they are not already installed, you can install them using your preferred method, such as pip install statsforecast datasetsforecast. The datasetsforecast library enables us to download hierarchical datasets, while statsforecast will be utilized for computing the base forecasts that need to be reconciled.



   


