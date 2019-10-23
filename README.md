[![Build Status](https://travis-ci.org/IBM/max-tutorial-app-python.svg?branch=master)](https://travis-ci.org/IBM/max-tutorial-app-python)

# MAX Fashion MNIST Web App (Lite) - Python

Python web app to consume MAX-Fashion-MNIST microservice.

This repository contains **TODOs** meant to be completed.

A working version of the app without the **TODOs** can be found here: 

# Steps

## Run Locally

**Start the Model API**

Deploy the fashion MNIST model using the steps provided here: https://github.com/SSaishruthi/max-fashion-mnist#build-the-model-docker-image

**Start the Web App**

1. [Get a local copy of the repository](#1-get-a-local-copy-of-the-repository)
2. [Install dependencies](#2-install-dependencies)
3. [Start the web app server](#3-start-the-web-app-server)
4. [Configure ports (Optional)](#4-configure-ports-optional)
5. [Try out the full version (Optional)](#5-try-out-the-full-version-optional)

### Start the Web App

#### 1. Get a local copy of the repository

Clone the web app repository locally. In a terminal, run the following command:

```
$ git clone 
```

Change directory into the repository base folder:

```
$ cd max-fashion-mnist-tutorial-app
```

#### 2. Install dependencies

Before running this web app you must install its dependencies:

```
$ pip install -r requirements.txt
```

#### 3. Start the web app server

You then start the web app by running:

```
$ python app.py
```

You can then access the web app at: [`http://localhost:8090`](http://localhost:8090)

#### 4. Configure ports (Optional)

If you want to use a different port or are running the model API at a different location you can change them with command-line options:

```
$ python app.py --port=[new port] --model=[endpoint url including protocol and port]
```

# Reference

* [Model Asset eXchange (MAX)](https://developer.ibm.com/code/exchanges/models/)
* [Center for Open-Source Data & AI Technologies (CODAIT)](https://developer.ibm.com/code/open/centers/codait/)

# License
[Apache 2.0](LICENSE)

