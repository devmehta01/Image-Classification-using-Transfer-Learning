# Image-Classification-using-Transfer-Learning
This code performs Image Classification using the VGG16 model and the pre-trained imagenet weights. We fine tune these weights to work for our task and dataset (transfer learning).

The classification is performed on the CIFAR-10 dataset and so we first download the data using keras.
I also loaded the pre-trained VGG16 model excluding the top layers so that we can add our own classification layers. Once the new layers are added on top of the VGG model, the new model is fine tuned and trained on our cifar10 dataset. 

The trained model is then evaluated and used to perform classification of new unseen images.
