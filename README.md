# csc434AIproject
This team project was assigned by Dr. Yu at SUNY Brockport.

The team members for this project were Richard Sia, Donte Black, Daniel Cona, and Padraic Darby.


This project is about building a CAPTCHA solver and then introducing different levels of noise in order to confuse the solver. CAPTCHAS
are designed in a way where a computer program is not able to solve it, therefore not allowing bots into certain websites. However, there
are CAPTCHA solvers that are able to bypass security feature and allow bots to enter websites. The inspiration for this project was to try
to design captchas that will enable the user to weaken the effectiveness of CAPTCHA solvers. the model is an OCR model with takes in an image 
as an input and outputs its' prediction as a string of characters. After taking in an image, the model consists of two convolutional neural
network layers, two Recurrent neural network layers, an output layer, and a CTC Layer which both calculates the loss at every step of the 
prediction and allows the model to take on problems where timing is variable for example every character does not need to be in a specific
location for the model to function properly.


Source code: https://github.com/keras-team/keras-io/blob/master/examples/vision/captcha_ocr.py

Dataset Link: https://www.kaggle.com/fournierp/captcha-version-2-images

