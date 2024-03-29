# DigitRecognizer 

<img src="screenshots/digitrecognizerfinal.gif" width="400" height="450">

A simple program made with Tkinter and Keras, it prompts the user to draw a number, process the image (crop, pad, center, resize), and then make a prediction of what it is using a convolutional neural network trained on the mnist dataset.  
  
The mnist dataset is a popular dataset containing 70000 28x28 images of handwritten digits.  
Here is a quick look at some of its instances :  

<img src="screenshots/screenshot_mnist.png" width="290" height="125">

# Usage

`python3.7 digit_recognizer.py`

# Dependencies

- tkinter
- matplotlib
- numpy
- tensorflow
- opencv
  
Also uses imagemagick and gs. (which aren't python dependencies, you can get them with brew, pacman, yay, apt-get, or whatever package manager you use)
