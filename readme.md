# Classification of Room Occupancy
> **MPA-MLF Final Project**

## Get started
Best results were achived using code in [project_cascade_classifier](project_cascade_classifier.ipynb), Google Colab Jupyter server with GPU accelerator was used. The preprocessing was done locally using [preprocessing file](preprocessing.ipynb). 

## Introduction
The rapid advancement of wireless sensing technologies has opened new frontiers in indoor
monitoring and smart building management. Among these, 60 GHz millimeter-wave (mmWave)
radar has emerged as a powerful tool for non-intrusive occupancy sensing. Unlike traditional
camera-based systems, radar-based sensing preserves user privacy while remaining functional
in diverse lighting conditions and environments. These signals are highly sensitive to micro-
movements, making them ideal for detecting the presence of humans through the analysis of
reflections from the body.


The primary objective of this project is to develop a machine learning model capable of
accurately classifying the number of persons in a room based on 60 GHz radar transmission data.
The classification task involves distinguishing between four distinct states: a room containing
only machinery (zero persons), one person, two persons, or three persons. By processing signals
in the delay-Doppler domain, the model must learn to identify the unique signatures created by
human movement and positioning to provide reliable occupancy counts.