# StreamlinedML

This project contains all the modules/services that are a part of Streamlined Machine Learning (SML) ecosystem.
This ecosystem is intended to not only significantly improve the end-to-end process of configuring, deploying, training, and evaluating machine learning models but also enable ML DevOps for applications.

## Building StreamlinedML

See the build readme in the build directory.

## Deploying StreamlinedML

See the Helm readme in the helm directory.

## Model Integration Software ToolKit (MISTK)

MISTK is a toolkit for integrating, validating, and evaluating machine learning models and algorithms. A machine learning model implements the MISTK model interface (mistk.model.AbstractModel) class. This class provides a set of abstract methods that represent the model lifecycle and must be implemented by the new model. Ultimately, these methods form the core of the web endpoint service that is made available for every model implementation. A model must be MISTK compatible to run in the SML ecosystem.

See the MISTK readme in the mistk directory.