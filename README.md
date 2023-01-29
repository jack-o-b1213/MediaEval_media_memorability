# MediaEval Classification Problem 

This repo contains a jupyter notebook walking through my attempt at the MediaEval Predicting Media Memorability Task: http://www.multimediaeval.org/mediaeval2019/memorability/

## Approach
A combination of provided features and features extracted using a pre-trained ResNet50 model were used to assign a binary classification to each video for their short-term memorability 

This additional feature is then used to in an ensemble of regression models to produce a short-term and long-term memorability score 