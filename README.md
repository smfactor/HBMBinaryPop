# HBMBinaryPop
Hierarchical bayesian modeling code to fit a 4 hyper-parameter binary population model to KPI detections and sensitivity (though applicable to other methods)

Requiers: 
```
astropy
corner
emcee
matplotlib
numpy
scipy
tqdm
```

Code is split up into two notebooks, the first, ```binPop.ipynb```, takes the detections and sensitivity grids as input and fits a 4 parameter population model using ```emcee```. The second, ```binPop-figs.ipynb```, takes the posterior samples generated in the first notebook and generates pretty figures (seen in Factor & Kraus 2023).
