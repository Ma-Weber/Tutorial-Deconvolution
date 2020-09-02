# Tutorial-Deconvolution
Tutorial for the deconvolution of hydrophone measurement data

Author: Martin Weber, Volker Wilkens and Sascha Eichstädt

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Ma-Weber/Tutorial-Deconvolution.git/master?filepath=TutorialFinal.ipynb)

## Abstract

This tutorial presents and explains examples of the deconvolution of hydrophone measurement data. The motivation for performing deconvolution is that, in many cases, measurements of ultrasonic signals are performed with a hydrophone that is (more or less) far from being perfect. The characteristic addressed by deconvolution is the frequency response of the hydrophone, which, in general, is different from an ideal flat characteristic. Mathematically speaking, the measured signal voltage (expressed in the time domain) of the hydrophone is the convolution of the acoustic pulse waveform and of the hydrophone impulse response. The hydrophone sensitivity can be determined by calibration. In recent years, calibration methods have been improved and extended and provide now the possibility to obtain amplitude and phase data in a broad frequency range and with a high number of sampling frequencies. For deconvolution, it is required that the sensitivity as a complex quantity (usually noted as a real and as an imaginary value or amplitude / modulus and phase value) is available. If experimental phase data are not available, phase responses may be calculated from modulus data assuming minimum phase system behavior. Determination of the uncertainty may be less straightforward when deconvolution is applied – in comparison to the usage of a single hydrophone sensitivity factor (scaling). It is therefore particularly addressed within this tutorial.

This tutorial uses a set of hydrophone calibration data and hydrophone measurement data as examples. The data sets and the results obtained by deconvolution are made publicly available through the PTB repository to serve as reference data sets. The data sets can be applied to validate of other deconvolution implementations by users.

## How to use

You can either run this notebook online with [binder](https://mybinder.org/v2/gh/Ma-Weber/Tutorial-Deconvolution.git/master?filepath=TutorialFinal.ipynb) or download all files and run it on your local computer with [Anaconda 3](https://www.anaconda.com/). Just start *Anaconda Navigator* and launch *Jupyter Notebook*. Jupyther Notebook will start in your browser, where you can open the *TutorialV20.ipynb* file. 
