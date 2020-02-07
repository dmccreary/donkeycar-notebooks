# DonkeyCar Notebooks

We need some help creating Jupyter notebooks for working with DonkeyCar data.
Here are some ideas of what would be useful.

## Data Analysis Functions
1. Get a list of the tubs in the mycar/data directory
1. Count the number of files in a tub
2. Count the number of images and json files in a tub
1. List image sizes for a tub
1. List average speed and throttle for a tub
1. List JSON files with zero values for throttle
1. Plot angle information for a tub
1. Plot speed (throttle) information for a given tub
1. Display some sample images
1. Validate the angle and speed data is all between the correct ranges

## Cleanup Functions
1. Remove empty tubs
1. Remove JSON and JPG files that have zero speed

## Model Functions
1. List all the models in the ~/mycar/models folder
1. View data in an f5 file (compressed file system in a zip format) HDF5 format https://en.wikipedia.org/wiki/Hierarchical_Data_Format1. List models and model sizes
1. Show the layers in a model
1. List model input parameters (image height and width)
1. Test model with a given image (returns the predicted throttle and steering)
1. Show the areas of an image that the model pays attention to (hard)

## Existing Donkeycar Utilities
In the past some developers created some utility functions.  These don't work on the current release when I tried to get them to work.

http://docs.donkeycar.com/utility/donkey/
Sample functions are:
tubclean
makemovie
tubcheck
tubhist - create a histogram of a tub
cnnactivations - show the CNN Activation functions
