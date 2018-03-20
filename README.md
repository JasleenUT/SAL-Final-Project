# SAL-Final-Project
This is the repo for SAL final project.

## Competition
This is for [Kaggle 2018 Data Science Bowl Competition](https://www.kaggle.com/c/data-science-bowl-2018), the goal for this project is to find the nuclei in divergent images to advance medical discovery.

## Author
@chiahuiliu
@
@
@

(To be added)

## Methodology
Use CNN to automactically categorize the data.

## Prerequisites
- R installation


## Install Tensorflow in R
1. Install a package from CRAN (I chose US(TX)), then type `install.packages("tensorflow")`
2. Install `curl` to have tensorflow installation smoothly. `install.packages('curl')`
3. Install tensorflow by typing  `library(tensorflow)` and then typing `install_tensorflow()`
4. To comfirm that you have successfully installed tensorflow in R, type 
```
sess = tf$Session()
hello <- tf$constant('Hello, TensorFlow!')
sess$run(hello)
```
P.S. In case there are some error message shown in step 3, just follow the instructions from the error message to satisfy the prerequisites for tensorflow installation in R.

