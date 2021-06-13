# Covid 19 Infection Detection using DeepLearning
> This Project aims to be used for early detection fo Covid-19 and aims to predict  wether the person is infected with Covid or not using when given a Chest CT Scan image of using Deep Learning.

`Blogposts` are avilable on:
- [BlogPost1](https://priyank7n.me/2021/01/23/covify-code.html), "Code"
- [BlogPost2](https://priyank7n.me/2021/01/20/Covify-GUI.html), "GUI"

## Dataset:
The Dataset is available on [kaggle](https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset)

![](https://github.com/PriyanK7n/covify/blob/main/images/Screenshot%202021-03-03%20at%2012.50.52%20AM.png)

![](https://github.com/PriyanK7n/covify/blob/main/images/Screenshot%202021-03-03%20at%2012.43.31%20AM.png)

![](https://github.com/PriyanK7n/covify/blob/main/images/Screenshot%202021-03-03%20at%2012.43.41%20AM.png)

## Models:
The Models trained on my project are stored in [GoogleDrive](https://drive.google.com/file/d/1xSrqIVVmEqA8OMP3IfvhemIv6tHLO0mQ/view?usp=sharing)

## GradCam:

The GradCam object takes in 3 args:
These steps are shown below one by one and later combined in a Learner.gradcam call

- learn: a fastai Learner
- fname: path to the image file to draw the heatcam over
- labels: list of labels to draw the heatmap for. If None, draws for the highest predicted class.


Installation:
~~~~~~~~~~~~

GIT:

.. code-block:: bash

  git clone https://github.com/PriyanK7n/covify
  cd covify
  pip install -r requirements.txt
  pip install -e .



