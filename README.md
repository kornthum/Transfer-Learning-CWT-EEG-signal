# Transfer-Learning-CWT-EEG-signal

This project will be public as a public paper soon. So, the full detail and result cannot be public now.


**Topic:** Transfer Learning for Classifying Motor Imagery
EEG: A Comparative Study

**Objective:** We compare the classification accuracy to the short-time Fourier Transform, which is the same feature extraction method that extracts in the time-frequency domain, to see if we use a pre-trained model with CWT feature instead of a model from scratch.

**Dataset:** BCI Competition IV 2a (http://www.bbci.de/competition/iv/)

**Feature Extraction Method:** Continuous wavelet transform (CWT) and we stacked CWT image of C3, Cz, C4 channels vertically.

Continuous wavelet transform Equation:

![image](https://user-images.githubusercontent.com/66479775/140597818-4d3e8348-5c9d-4b4d-b592-69a9bbafcd83.png)

Example of fianl extracted feature with detail:

![image](https://user-images.githubusercontent.com/66479775/140597844-d7b8be3c-3fff-49f8-8fa8-faf4764bf9fc.png)


**Deep learning model:** Pre-trained model(Alexnet, ResNet18, ResNet50, InceptionV3, ShuffleNet)
