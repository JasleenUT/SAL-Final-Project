# SAL-Final-Project
This is the repo for SAL final project.

## Competition
This is for [Kaggle 2018 Data Science Bowl Competition](https://www.kaggle.com/c/data-science-bowl-2018), the goal for this project is to find the nuclei in divergent images to advance medical discovery.

## Author
[@chiahuiliu](https://github.com/chiahuiliu) [chiahuiliu@utexas.edu](chiahuiliu@utexas.edu)
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
P.S. In case there are some error messages shown in step 3, just follow the instructions from the error message to satisfy the prerequisites for tensorflow installation in R.

### About github
This for you in case you are not familiar with github.
Here are the one-time steps for you to clone and set the remote connection with this project.
1. Have a github account.
2. Fork this project to your own github repo.
3. Clone your repo to your local directory. `git clone (your repo link)`
4. Set a connection with this repo. `git remote add upstream git@github.com:chiahuiliu/SAL-Final-Project.git`
5. To confirm you successfully setting the aforementioned things successfully, type `git remote`, it should show origin and upstream.
Just to be clear, `origin` is the connection for your local directory in your laptop and your github repo, and `upstream` is the connection for your local directory in your laptop and this repo.
