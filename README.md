# Iris Flower Classification
[![PEP8](https://img.shields.io/badge/code%20style-pep8-green.svg)](https://www.python.org/dev/peps/pep-0008/)
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](https://github.com/Vaaceph/iris-flower-classification/blob/master/LICENSE.md)  </br></br>
Building machine learning random forest model to predict type of the flower in IRIS data and using flask to expose it as an API

Dataset:

The IRIS dataset contains sepal length, sepal width, petal length, petal width as features. All these lengths were in centimeters. </br></br>
Three class for classification are as follows:</br>

* Iris-setosa
* Iris-versicolor
* Iris-virginica


## To run this Project

Git clone on your local machine

```bash
Git clone https://github.com/sush92/IRIS_species_prediction.git
```

Start your Docker app 

```bash
docker build -t apache-flask . 
```

```bash
docker run -d -p 8000:8000 apache-flask
```






