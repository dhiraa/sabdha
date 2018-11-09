[![Build Status](https://travis-ci.com/dhiraa/shabda.svg?branch=master)](https://travis-ci.com/dhiraa/shabda/)
[![Documentation Status](https://readthedocs.org/projects/shabda/badge/?version=latest)](https://shabda.readthedocs.io/en/latest/?badge=latest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/asyml/texar/blob/master/LICENSE)
 

# Shabda 
 
## Introduction

In recent past, Deep Learning models have proven their potential in many application areas, 
however its entry into embedded world has its own twists and practical difficulties.

## Problem Statement

To come up with a framework that enables a fast prototyping of Deep Learning 
models for Audio (to start with!) and provides an easy way to port the models 
on to Android using TFLite.

## Proposed Solution

Come up with following modular components which can be then used as plug and play components:
 - Dataset modules with preprocessing modules
 - DataIterator modules
 - Tensorflow Models (Estimators)
 - Engine to run the models
 - Tensorflow model serving using TFLite
    - Web app
    - Mobile

## Architecture

![](docs/images/shabda_stack.png)

## [Doc](https://shabda.readthedocs.io/en/latest/index.html)

## [Dataset](data)
- [FreeSound from Kaggle](https://www.kaggle.com/c/freesound-audio-tagging)
- Speech Recognition
    - [Kaggle](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge)
    - [Google](https://www.tensorflow.org/tutorials/sequences/audio_recognition)


## [Notebooks](notebooks)

## [Examples](src/main/python/shabda/examples)


## Other notatble Audio Repos
- https://github.com/mozilla/DeepSpeech
