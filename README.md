# Functional-datasets-with-derivatives
This repository contains several benchmark functional datasets with class labels along with their first and second derivative datasets calculated via cubic spline data interpolation technique in MATLAB, since underlying function is usually unknown. They can be used for the purpose of classification of functional data. Several types of datasets are included, binary and multi-class, high and low dimensional, balanced and imbalanced, and small and large-scale. There are no missing values. Data descriptions are present in readme.md file.

## Files are arranged as follows :

```shell
  datasetName/datasetName # This is the original dataset with class labels 
``` 
```shell
  datasetName/datasetName_original # This is the dataset without labels used to calculate derivatives
``` 
```shell
  datasetName/datasetName_first_derivative # This is the first-order derivative dataset
``` 
```shell
  datasetName/datasetName_second_derivative # This is the second-order derivative dataset
``` 
## Data descriptions :
### 1. HAM 
####  Ham dataset includes measurements from Spanish and French dry-cured hams.
* Size: 214
* Dimension: 431
* Number of classes: 2
* Label +1: 103
* Label -1: 111

### 2. COFFEE
#### Food spectrographs are used in chemometrics to classify food types, a task that has obvious applications in food safety and quality assurance. The coffee dataset is a two-class problem to distinguish between Robusta and Aribica coffee beans.
* Size: 56
* Dimension: 286
* Number of classes: 2
* Label +1: 27 
* Label -1: 29

### 3. GROWTH
#### Growth dataset consists of 93 growth curves for a sample of 54 boys and 39 girls, and the observations were measured at a set of thirty-one ages from one to eighteen years old. The ages are not equally spaced.
* Size: 93
* Dimension: 31
* Number of classes: 2
* Label +1: 54
* Label -1: 39

### 4. ECG
#### ECG dataset contains the electrical activity recorded during one heartbeat and the two classes are a normal heartbeat and a Myocardial Infarction.
* Size: 200
* Dimension: 96
* Number of classes: 2
* Label +1: 133
* Label -1: 67

### 5. TECATOR
#### Tecator dataset consists of 215 near-infrared absorbance spectra of meat samples. Each observation consists of a 100-channel absorbance spectrum in the wavelength range 8,501,050 nm. The goal here is to predict whether the fat percentage is greater than 20% from the spectra.
* Size: 215
* Dimension: 100
* Number of classes: 2
* Label +1: 138
* Label -1: 77

### 6. WEATHER
#### Weather dataset consists of one year of daily temperature measurements from 35 Canadian weather stations, and the two classes are considered depending if the total yearly amount of precipitations are above or below 600.
* Size: 35
* Dimension: 365
* Number of classes: 2
* Label +1: 15
* Label -1: 20

### 7. WAFER
#### Wafer data relate to semi-conductor microelectronics	fabrication. A collection of inline process control	measurements recorded from various sensors during the processing of silicon wafers for semiconductor fabrication constitute the wafer database; each dataset in the wafer database contains the measurements recorded by one sensor during the processing of one wafer by one tool. The two classes are normal and abnormal process. There is a large class imbalance.
* Size: 7164
* Dimension: 152
* Number of classes: 2
* Label +1: 6402
* Label -1: 762

### 8. PHONEME
#### Phonemes data set is related to a speech recognition problem, namely the phoneme classification problem. The data correspond to logperiodograms constructed from recordings available at different equispaced frequencies for the five phonemes: “sh” as in “she”, “dcl” as in “dark”, “iy” as in “she”, “aa” as in “dark”, and “ao” as in “water”. The aim is to predict the phoneme class for a new log-periodogram.
* Size: 2000
* Dimension: 150
* Number of classes: 5
* Size of each class is the same i.e. 400

### 9. YEAST_CELL_CYCLE
#### The yeast cell cycle data set represent the fluctuation of expression levels of n genes over 17 time points, corresponding to two cell cycles. 
* Size: 384
* Dimension: 17
* Number of classes: 5
* Label 1: 67
* Label 2: 135
* Label 3: 75
* Label 4: 52
* Label 5: 55
