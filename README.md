# healthcare_informatics_2018


Analysis of the NIH Clinical Center DeepLesion dataset.

## Setup
Create a new conda environmnent

```console 
conda create -n deeplesion python=3.6
```

Activate the environment

```console 
source activate deeplesion
```

Install CUDA 9.2 (V9.2.148)

Using Nvidia Driver Version: 396.54

Packages:
+ seaborn
+ numpy
+ pandas
+ scikit-image
+ scikit-learn
+ pytorch
+ jupyter

### THIS DOES NOT WORK, IGNORE
The Python dependencies are listed in the requirements.txt file.

The following command will install all the required packages

```console 
while read requirement; do conda install --yes $requirement; done < requirements.txt
```
