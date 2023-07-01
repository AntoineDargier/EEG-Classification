# Sleep phases classification using electroencephalograms (EEGs) and accelerometers

### Goal
Implementing ML and DL methods for classifying sleep phases using EEGs and accelerometer data. 

### Language
```Python```

### Contents
1. Introduction
2. Pre-processing
3. Features extraction
4. Model
5. Conclusion

### Features
* statistical features: mean, median, standard deviation, skewness, kurtosis
* signal analysis features: zero-crossing rate, magnitude maximum, Hjorth coefficient (mobility, complexity), energy, power by frequency bands, Petrosian fractal dimension, Katz fractal dimension
* non-used features: Hjorth activity, Hurst exponents, Spectral entropy, variance, wavelet coefficient, slope mean, slope variance

### Libraries
* ```librosa```
* ```numpy```
* ```pandas```
* ```matplotlib```
* ```scipy```
* ```scikit-learn```
* ```pyeeg```
* ```pytorch```

### Conclusion
After fine-tuning hyperparameters, I reached 71% of f1-macro, which was the metric chosen, with an XGBoost model. The CNN model performed fairly similarly, or slightly worse.
