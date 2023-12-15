# A Text-Aware Predictive Process Monitoring Approach for Knowledge-Intensive Processes

This repository contains the source code for the paper 'Text-Aware Predictive Process Monitoring of Knowledge-Intensive Processes: Does Control Flow Matter?'.
It contains the implementation of a text-aware PPM approach for predicting the total lead time of knowledge-intensive processes. Here BERT, Topic Modeling and BoW is compared.

## How to use the implementation?
1. Create a virtual environment and install the required packages using python.
2. Create folders named _Input Data_, _Prediction Models_, and _Results_.
5. Load your event log (.xes) with the included textual information into the _Input Data_ folder.
6. For every t<n that is considered, create unique train and test dataframe with the respective features. Load your data (.csv) into the _Input Data_ folder.
7. Execute each script.
8. The best model and the results are saved into the respective folders.
