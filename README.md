# Files Documentations
### idc_with_header.csv / minmax.xlsx: 
  These are the dataset and its corresponding labels, the dataset is normalized using min-max normalization technique.

### codes.ipynb:
  This notebook has the final version of the Encoders code, along with a test of genetic algorithm combined with VAE.

### genetic.ipynb:
  This notebook has the final version of the genetic algorithm combined with both AE and VAE.
  
### PCA + GA.ipynb
  PCA for dimensionality reduction, evaluates reconstruction error, trains (RF, NB, SVM) with the reduced features, and optimizes hyperparameters using Genetic Algorithms
  
### PSO.ipynb:
  Includes a PSO combined with classification model to compare the performance against the Encoders + GA.

### images.ipynb: 
  This notebook currently holds the first version of transforming spectra data into images. We will continue working on finding various method to best suit CNN.

### Requirements.txt: 
  File automatically by listing all the libraries installed in our current Python environment. (Widely accepted practice in software development and data science projects)

### BGWO.ipynb optimizes the hyperparameters of the Random Forest & SVM classifiers to compare with PCA + GA
 
  **Run**
  *pip install -r requirements.txt*
