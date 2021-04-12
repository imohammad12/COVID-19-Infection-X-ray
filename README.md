# COVID-19 Infection Detection using X-ray images

We have used a pre-trained VGG-16 (with batch-norm) model for predicting COVID-19 infection using X-ray images.

Multiple balancing techniques have been used to handle unbalanced data.

Multiple Data Augmentation techniques have been used.

We have added a fully connected layer to the end of the VGG-16.

In the first 15 epochs, we freeze all weights except the last layer. Then we fine-tune the whole model for 20 epochs.

The models acheives 97% accuracy on the balanced test dataset.
