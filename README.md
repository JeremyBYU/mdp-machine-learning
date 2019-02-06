# MDP Machine Learning Presentation

This repository contains the presentation and code samples for University of Michigan [Multidisciplinary Design Program (MDP)](https://mdp.engin.umich.edu/) *Intro to Machine Learning Course*. This presentation was given on 02/13/2018 by Jeremy Castagno.

The outline of the slides and presentation are as follows:

* What is Machine Learning
  * Basic Terms
  * Assessing Performance
* Simple Regression Models
  * Bias vs. Variance Trade off
* Simple Classification Model
  * Logistic Regression
  * Support Vector Machines
  * Decision Trees
* Break
* Natural Language Processing
  * Basic Fundamentals of NLP
  * NLP Advanced Feature Extraction
* Computer Vision - If time permits

The slides are written in a [Jupyter](https://jupyter.org/)  notebook and are integrated into a *live* python session. If you desire to run the presentation yourself please see the `Running the slides` section. A PDF version of the slides can be found in the `presentation/pdf` folder.

## Key Outcomes
After this short lecture students know:

* Common machine learning terms.
* Common machine learning models and which ones are best suited for a problem domain.
* How to validate and assess model performance.
* The bias/variance tradeoff and how to prevent model overfitting.
* How to train a Natural Language Processing model for text classification


## Running the slides

The slide are part of a [juypter notebook](https://jupyter.org/) and make use of the [RISE](https://github.com/damianavila/RISE) slides extension.  This allows one to have an HTML5 slide deck for a presentation.

### Dependencies

Please set up a virtual python environment using [conda](https://www.anaconda.com/distribution/).  Install the following:

1. `conda install numpy pandas seaborn sklearn nltk graphviz pygraphviz  jupyter spacy`
2. `python -m spacy download en_core_web_md`
3. `python -m pip install "msgpack<0.6.0"` - Bug with SPacY

## Running

1. `juypter notebook presentation/mdp_presentation_1.ipynb`

A full run of the notebook (`Run All Cells`) should take about 4 minutes to run. Many machine learning models are trained on a small dataset.

## Disclaimer

This lecture is scheduled for 1.5 hours and gives a *very* brief introduction of machine learning. Its focus is to help students get a handle on the main terms and concepts of machine learning. It is not meant to replace an actual Machine Learning course. The topics presented are specifically tailored to the MDP projects assigned to the students. My overall goal is to help the students feel confident in their abilities and excited to begin their project.




