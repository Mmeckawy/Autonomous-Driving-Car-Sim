# Autonomous Driving Car Simulation
You need to make sure the following libraries are installed before running the code
 - numpy
 - OpenCV
 - IPython
 
## Run the Code
Open jupyter notbook using the command suitable with your operating system, then run the code

## Debugging Mode
Set the debugger to true in the debugging function, and stages of the pipeline will appear in the form of images

## Vehicle Detection Testing
The HOG descriptor focuses on the structure or the shape of an object. It is better than any edge descriptor as it uses magnitude as well as angle of the gradient to compute the features. For the regions of the image it generates histograms using the magnitude and orientations of the gradient.

Heat mapping is a method used to analyze and detect movemenet of objects in videos, their directional flow and gather clusters of useful data. In our case, it is additionally used to remove false positives during the process of vehicle detection
![pipeline](https://user-images.githubusercontent.com/69309651/186995050-caa4dbb7-1c75-4fe1-8918-dc85b5644307.png)

