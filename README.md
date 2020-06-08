# flask based Heroku web app for malaria detection


------------------
## About the app
> This repository was created to help clarify how to utilise flask and gunicorn to easily deploy a python/keras deep learning model as a web app on Heroku. This example features code for online deployment of a binary medical image classification model, based on convolutional neural network architecture. The CNN has three hidden layers and has been trained on the following malaria parasite image dataset  <a href="https://ceb.nlm.nih.gov/repositories/malaria-datasets/">National Library of Medicine</a>. The trained model achieved accuracy of more than 95% on the test set and its weights have been saved in the Models folder (see file: my_model.h5) in the very useful HDF5 format. You may use your own saved trained model! Just make sure you put it in the Models folder and name it appropriately so that the flask app may call it.

## Deployment

To deploy it for public use, you need to upload this app on heroku or other python enabled server. However heroku is pretty good at recognising and running python apps. There is also a free version!

