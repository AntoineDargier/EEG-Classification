# Sleep phases classification using electroencephalograms (EEGs) and accelerometers

### Goal
Classification of sleep phases using EEGs and accelerometers data. 

### Language
```Python```

### Contents
1. Introduction
2. Pre-processing
3. Features extraction
4. Model
5. Conclusion

### Librairies
* ```librosa```
* ```numpy```
* ```pandas```
* ```matplotlib```
* ```scipy```
* ```scikit-learn```
* ```pyeeg```

### Conclusion
After fine-tuning hyperparameters, I reached $71%$ of f1-macro, which was the metric chosen, with an XGBoost model. The CNN model performed fairly similarly, or slightly worse.
