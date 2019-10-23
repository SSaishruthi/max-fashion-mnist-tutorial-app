# MAX Fashion MNIST Web App - Python

In this tutorial, we will build a Python web app to integrate the MAX-Fashion-MNIST microservice with a user-friendly interface.

# Instructions
## 1. Start the MAX-Fashion-MNIST model API

Deploy the fashion MNIST model using the steps provided here: https://github.com/SSaishruthi/max-fashion-mnist#build-the-model-docker-image


## 2. Download/Clone the WebApp template (this repository)

Clone the web app repository locally. In a terminal, run the following command:

```
$ git clone 
```

Change directory into the repository base folder:

```
$ cd max-fashion-mnist-tutorial-app
```

## 3. Complete the WebApp code

The Python code to run this web applicaton template is contained in the `app.py` file. This file contains **TODO**-comments and intructions that need to be completed to adjust this webapp template for our MAX-Fashion-MNIST model.

_NOTE: The solution can be found here: [LINK-HERE]._

TODO 1: Review how post request is structured.

TODO 2: Update model URL

TODO 3: Update code to extract prediction from the model response. 
        _NOTE_ To know the response structure, explore model microservice API.
        

## 4. Start the WebApp

Before running this web app you must install its dependencies:

```
$ pip install -r requirements.txt
```

You then start the web app by running:

```
$ python app.py
```

You can then access the web app at: [`http://localhost:8090`](http://localhost:8090)

**Configuring ports**

If you want to use a different port or are running the model API at a different location you can change them with command-line options:

```
$ python app.py --port=[new port] --model=[endpoint url including protocol and port]
```

# Reference

* [Model Asset eXchange (MAX)](https://developer.ibm.com/code/exchanges/models/)
* [Center for Open-Source Data & AI Technologies (CODAIT)](https://developer.ibm.com/code/open/centers/codait/)

# License
[Apache 2.0](LICENSE)

