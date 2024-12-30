# p300-character-prediction

This repository contains code for a P300-based character prediction system. 
It uses EEG data to predict which row/column the user intends, based on the P300 ERP.

## Features
- Preprocessing with Savitzky-Golay filter and bandpass filtering
- Automatic channel selection based on signal variance
- Parallel processing using joblib for each trial
- Confusion matrix visualization

## Installation
```bash
pip install -r requirements.txt
# or conda install ...
