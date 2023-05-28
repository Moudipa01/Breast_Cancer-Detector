# Breast_Mitosis-Detector
![Build Status](https://travis-ci.org/IBM/MAX-Breast-Cancer-Mitosis-Detector.svg?branch=master)
## IBM Code Model Asset Exchange: Breast Cancer Mitosis Detector
> This repository contains code to instantiate and deploy the mitosis detection model.
 
> This model takes a 64 x 64 PNG image file extracted from the whole slide image as input, and outputs the predicted probability of the image containing mitosis. 

> For more information and additional features, check out the [samples](https://github.com/Moudipa01/Breast_Cancer-Detector/tree/main/samples).

> The code in this repository deploys the model as a web service in a Docker container. 

## Model Metadata
| Domain | Application | Industry  | Framework | Training Data | Input Data Format |
| ------------- | --------  | -------- | --------- | --------- | -------------- | 
| Vision | Cancer Classification | Health care | Keras | [TUPAC16](https://github.com/Moudipa01/Breast_Cancer-Detector/tree/main/docs) | 64x64 PNG Image|

_Note:_ Although this model supports different input data formats, the inference results are sensitive to the input data. In order to keep the extracted images the same as the original datasets, PNG image format should be used.


## References
* _Dusenberry, Mike, and Hu, Fei_, [Deep Learning for Breast Cancer Mitosis Detection](https://github.com/CODAIT/deep-histopath/raw/master/docs/tupac16-paper/paper.pdf), 2018.

## Licenses

| Component | License | Link  |
| ------------- | --------  | -------- |
| Test Samples | Custom License | [Sample](https://github.com/Moudipa01/Breast_Cancer-Detector/tree/main/samples) |


## Run Locally

1. [Build the Model](#1-build-the-model)
2. [Deploy the Model](#2-deploy-the-model)
3. [Use the Model](#3-use-the-model)
4. [Development](#4-development)
5. [Cleanup](#5-cleanup)

