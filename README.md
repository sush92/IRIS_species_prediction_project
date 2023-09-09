# Iris flower classification and Exposing random forest machine learning service as an API

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

Access API

```bash
localhost/8000/apidocs
```





