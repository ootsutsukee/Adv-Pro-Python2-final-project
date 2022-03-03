## Image Classifier

This is an app that classifies given image by using *[Convolutional Neural Network](https://en.wikipedia.org/wiki/Convolutional_neural_network)*. Neural Network model was trained using one of the commonly used dataset to train machine learning and computer vision algorithms – *[CIFAR-10](https://en.wikipedia.org/wiki/CIFAR-10)*.

## Installation

To get started with the application you need to complete following steps:

- Install dependencies:

```shell
$ pip install -r requirements.txt
```

- Create `.env` file with the following properties and set the appropriate values:

```
SECRET_KEY = 'your_secret_key'
```

- Run application:

```shell
$ python3 manage.py runserver 8000
```

## Usage

Run your application and upload any image you want to classify and get the result of the classification by trained model.
