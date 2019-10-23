# MAX Fashion MNIST Web App - Python

Python web app to consume MAX-Fashion-MNIST microservice.

# Requirements

1. Pre-processing code to convert input to requirement format that can be used as request payload.
2. Update post request parameters (e.g. files, model URL).
3. Post-processing code to extract prediction and send back to UI in preferred format.

# Complete **TODO**

This repository contains **TODOs** meant to be completed.

TODO 1: Review how post request is structured.
TODO 2: Update model URL
TODO 3: Update code to extract prediction from the model response. 
        _NOTE_ To know the response structure, explore model microservice API.


A working version of the app without the **TODOs** can be found here: 

# Steps

## Run Locally

1. [Start the Model API](#1-start-the-model-api)
2. [Get a local copy of the repository](#2-get-a-local-copy-of-the-repository)
3. [Install dependencies](#3-install-dependencies)
4. [Start the web app server](#4-start-the-web-app-server)
5. [Configure ports (Optional)](#5-configure-ports-optional)

### Start the Web App

#### 1. Start the Model API

Deploy the fashion MNIST model using the steps provided here: https://github.com/SSaishruthi/max-fashion-mnist#build-the-model-docker-image

#### 2. Get a local copy of the repository

Clone the web app repository locally. In a terminal, run the following command:

```
$ git clone 
```

Change directory into the repository base folder:

```
$ cd max-fashion-mnist-tutorial-app
```

#### 3. Install dependencies

Before running this web app you must install its dependencies:

```
$ pip install -r requirements.txt
```

#### 4. Start the web app server

You then start the web app by running:

```
$ python app.py
```

You can then access the web app at: [`http://localhost:8090`](http://localhost:8090)

#### 5. Configure ports (Optional)

If you want to use a different port or are running the model API at a different location you can change them with command-line options:

```
$ python app.py --port=[new port] --model=[endpoint url including protocol and port]
```

# Reference

* [Model Asset eXchange (MAX)](https://developer.ibm.com/code/exchanges/models/)
* [Center for Open-Source Data & AI Technologies (CODAIT)](https://developer.ibm.com/code/open/centers/codait/)

# License
[Apache 2.0](LICENSE)

