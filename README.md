# Kaggle-diamonds

## Predicting diamonds' price

# Cleaning Techniques
- Eliminar las filas con x/y/z=0
- Estudiar la correlación: eliminar columnas muy relacionadas (x,y,z)
- Histograma de las categóricas:  
    - color/clarity: valor numérico
    - Cut: good/fair + get dummies
- Separar por mediana los datos y estudiarlos por separado

# Regression Models
- LinearSVR ~ 0.6

- KNeighborsRegressor ~ 0.85

	[0.95-0.97]
- GradientBoostingRegressor 

- HistGradientBoostingRegressor (el de mejores resultados)
- RandomForestRegressor 
