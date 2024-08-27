# PyTorch Projects that could be found here:
001. [Binary Classification with PyTorch](PyTorch_Binary_Classification_Project.ipynb) - diabetes dataset.
   
  Data: diabetes dataset with 520 entries and 17 features; target variable - class (1 for presence of disease, 0 for absense). Dataser is slightly imbalanced.

  Metric: custom accuracy function, 95.91 reached.
  
  Architecture: 3 linear layers, ReLU. Loss function: BCEWithLogitsLoss, optimiser: SGD.
  
  Data Preprocessing: Label Encoding for Numerical Features and Target Encoding for 'class' (target feature); Standard Scaling of Age feature.
  
