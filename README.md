
# E4040-2020Fall-Project: A Neural Attention Model for Speech Command Recognition
*Author:* 
Huiyan Xing, hyxing98@outlook.com

Haikang Tan

Jiawen Yan

## Description
This directory contains the scripts for A Neural Attention Model for Speech Command Recognition project for ECBM E4040 Neural Networks and Deep Learing. 

In this project, a convolutional recurrent neural
network with attention for speech command recognition is implemented. The database they used is Google Speech Commands dataset which includes version 1 and version 2. By adding data augmentation and utilizing various parameter adjusting functions, the best accuracy achieved was  95.37%.

## Getting Started
These instructions will provide you a guideline for our basic functions as well as how to running on your machine for development and testing purposes.
### Installation
All that is required is to clone the repository from github using

> $ git clone 

or download the entire repository as a zip file. 

###  Prerequisites
The entire program is written using the Python. The following Python version and packages are required for executing the script correctly
```
Python == 2.7
Tensorflow == 2.2
librosa
spela
numpy
matplotlib
```
### Introducing the files in project
#### Jupyter Notebooks
Four tested models were in the following notebooks, as shown in file names.
 - Speech_Recog_Model_1.ipynb:
Main jupyter notebook where the whole project is implemented, including data processing, model building, training and result comparison. Run each cell in order.
- Speech_Recog_Demo_model2&4_hx2302.ipynb & Speech_Recog_Demo_model3.ipynb: same as the first one

#### Supporting .py Files

 - SpeechDownloader.py & AudioGen.py & audioUtils.py:
Downloading and pre-processing data gained from Google Speech Commands dataset, output confusion matris for result comparison.
- Data_Augmentation.py:
Augmenting data.
- adjust_utils.py:
Includes various parameter adjusting functions.


## Usage
The entire script is organized in the following way.
```
│  adjust_utils.py
│  AudioGen.py
│  audioUtils.py
│  Data_Augmentation.py
│  E4040.2020Fall.TPIA.report.hx2302.ht2545.jy3088.pdf
│  README.md
│  Spectrogram.py
│  SpeechDownloader.py
│  Speech_Recog_Demo_model2&4_hx2302.ipynb
│  Speech_Recog_Demo_model3.ipynb
│  Speech_Recog_Model_1.ipynb
│
├─models
│      model_attRNN_e.h5
│      model_attRNN_m.h5
│      model_attRNN_p1.h5
│      model_attRNN_p2.h5
│
└─plots
        picConfMatrix.png
        pic_att_weight_p2.png
        pic_mel_spec_freq_m.png
        pic_mel_spec_freq_p2.png
        pic_raw_wave_m.png
        pic_raw_wave_p2.png
```

## Weebly Website
To see the website, please click the link below:
[iotcolumbia2020tpia](https://iotcolumbia2020tpia.weebly.com)




