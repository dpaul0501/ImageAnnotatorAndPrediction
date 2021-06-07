# Manual Image Annotator/Classifier with a Flask backend with Model Based Image Inference
This repository is merging of two Flask application, 

1. [VGG Image Annotator](http://www.robots.ox.ac.uk/~vgg/) in order
to manually mark regions on images, which can later be used as input regions for image
classification/machine learning projects. The problem with running VIA as standalone program
in the browser is that was not an easy way to organise your data. Here, this app comes into play.
It saves the images and the connected regions in a database, which can easily
be edited, reloaded, and deleted, both one by one and in batches.

2. A pretty and customizable web app to deploy your DL model with ease https://github.com/mtobeiyf/keras-flask-deploy-webapp#readme



To make it run locally:
```
git clone https://github.com/dpaul0501/ImageAnnotatorAndPrediction/
cd ImageAnnotatorAndPrediction
pip install -r requirements.txt
```

on windows:
`set FLASK_APP=app.py`

on unix:
`export FLASK_APP=app.py`

```
flask run
```

# VGG Image Annotator

VGG Image Annotator (VIA) is an open source project developed at the
[Visual Geometry Group](http://www.robots.ox.ac.uk/~vgg/) and released under



the BSD-2 clause license. This work is supported by EPSRC programme grant
Seebibyte: Visual Search for the Era of Big Data ([EP/M013774/1](http://www.seebibyte.org/index.html)).
Visit the [VGG software page](http://www.robots.ox.ac.uk/~vgg/software/via/) for more details.

# Deploy Keras Model with Flask as Web App in 10 Minutes

https://github.com/mtobeiyf/keras-flask-deploy-webapp#readme




## Credits
https://github.com/joost823/flask-via

https://github.com/mtobeiyf/keras-flask-deploy-webapp

Author: dpaul0501

