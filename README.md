# TensorFlow Lite text classification sample

## Overview

This is an end-to-end example of movie review sentiment classification built
with TensorFlow 2.0 (Keras API), and trained on IMDB dataset. The demo app
processes input movie review texts, and classifies its sentiment into negative
(0) or positive (1).

## Model

See [Text Classification with Movie Reviews](https://www.tensorflow.org/tutorials/keras/basic_text_classification)
for a step-by-step instruction of building a simple text classification model.

## iOS app

Follow the steps below to build and run the sample iOS app.

### Requirements

*  Xcode 10.3 (installed on a Mac machine)
*  An iOS Simuiator running iOS 12 or above
*  Xcode command-line tools (run ```xcode-select --install```)
*  CocoaPods (run ```sudo gem install cocoapods```)

## Build and run

1. Clone the repository to your computer to get the demo application.

    ```
    git clone https://github.com/khurram18/TextClassafication.git
    ```

1. Navigate to the cloned directory

    ```
    cd TextClassafication
    ```

1. Open the `TextClassification.xcworkspace` in Xcode either by double clicking on it or using below command

    ```
    open TextClassification.xcworkspace
    ```
    This launches Xcode and opens the `TextClassification` project.
    
![](screenshot.png)

### Additional Note
_Please do not delete the empty reference to the .tflite file after you clone the repo and open the project. The model reference will be fixed as the model file is downloaded when the application is built and run for the first time.

The pull request to add this example to official tensorflow examples repository is [here](https://github.com/tensorflow/examples/pull/146)
