# Домашняя работа к занятию “MLOps/DataOps”

Результат инференса модели
```
$ curl -X POST -H "Content-Type:application/json; format=pandas-split" --data '{"columns":["fixed acidity", "volatile acidity", "citric acid", "residual sugar", "chlorides", "free sulfur dioxide", "total sulfur dioxide", "density", "pH", "sulphates", "alcohol"],"data":[[6.2, 0.66, 0.48, 1.2, 0.029, 29, 75, 0.98, 3.33, 0.39, 12.8]]}' http://127.0.0.1:1234/invocations
[6.507185441498435]
```

