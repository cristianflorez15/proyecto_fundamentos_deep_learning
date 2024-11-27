Video de informe: https://youtu.be/Ni8zgOB4P1c

Base de datos usada en el proyecto: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

Importación de la base de datos en Python (implementada en los notebooks)
```
pip install ucimlrepo

from ucimlrepo import fetch_ucirepo 
  
# fetch dataset 
breast_cancer_wisconsin_diagnostic = fetch_ucirepo(id=17) 
  
# data (as pandas dataframes) 
X = breast_cancer_wisconsin_diagnostic.data.features 
y = breast_cancer_wisconsin_diagnostic.data.targets 
  
# metadata 
print(breast_cancer_wisconsin_diagnostic.metadata) 
  
# variable information 
print(breast_cancer_wisconsin_diagnostic.variables) 
```
