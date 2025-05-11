# Files Documentations
### idc_with_header.csv / minmax.xlsx: 
  These are the dataset and its corresponding labels, the dataset is normalized using min-max normalization technique.

### codes.ipynb:
  This notebook has the final version of the Encoders code, along with a test of genetic algorithm combined with VAE.

### GA folder:
  This notebook has the final modified version of Genetic Algorithm implementation with Encoders. It also contains a separate file for running codes with RF as a fitness function.
  
### PCA + GA folder:
  PCA for dimensionality reduction, evaluates reconstruction error, trains (RF, NB, SVM) with the reduced features, and optimizes hyperparameters using Genetic Algorithm
  
### PSO folder:
  Includes a PSO combined with classification model to compare the performance against the Encoders + GA.

### ABC folder:
  Implementation of Artificial Bee Colony Optimization to compare the performance against Encoders + GA. (references: https://github.com/BrianMburu/Artificial-Bee-Colony-in-python/blob/master/artificial_bee_colony.py)

### CNN folder:
  Contains all the test files and images that have been done so far on the CNN methods. Might be creating a separate repository for these later on.

### BGWO folder:
  Optimizes the hyperparameters of the Random Forest & SVM classifiers to compare with our methods. As well as a file for BGWO feature selection based.

### GSA folder: 
  Optimizes the hyperparameters of the Random Forest & SVM classifiers to compare with our methods

### Requirements.txt: 
  File automatically by listing all the libraries installed in our current Python environment. (Widely accepted practice in software development and data science projects)
 
  **Run**
  *pip install -r requirements.txt*
