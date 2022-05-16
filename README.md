# Phase One and Two of the image processing project.
****
## Phase One : Lane Detection

In this phase, we have a sample video in which we detect the lane lines of.

This is done using Thresholding and Sobel Filters, then getting a bird's eye view of the region of interest, and processing each frame using the silding windows technique to find the lane lines.

****

## Phase Two: Vehicle Detection

In this phase, we detect vehicles in a sample video.

This is done extracting the HOG features of a set of training images and training a linear SVC classifier of a SVM model. Then we pass a sliding window over the entire screen and extract the HOG features of the frame, and pass them to the classifier. We then extract a heatmap of the most dominant pixels, and threshold the heatmap, which extracts the vehicles.
