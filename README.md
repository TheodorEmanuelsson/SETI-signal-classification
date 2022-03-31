# SETI-signal-classification

Using ResNet50 and transfer learning (i.e using the weights from a pretrained model in ImageNet) and updating all weights, this model achieved an accuracy of XXXX. 

## Data

The Search for Extra-terrestrial Intelligence (SETI) dataset (small) contains 5600 training images (800 for each class), 700 validation images (100 for each class) and 700 test images (100 for each class) of 7 different kinds of signals. Radio data is being currently been collected by the Green Bank Observatory in West Virginia and the Parkes Observatory in New South Wales, with optical data being collected by the Automated Planet finder in California.

The data are stored in filterbank file, which are created at three different frequency resolutions. These are,

High frequency resolution (~3 Hz frequency resolution, ~18 second sample time)
High time resolution (~366 kHz frequency resolution, ~349 microsecond sample time)
Medium resolution (~3 kHz frequency resolution, ~1 second sample time)

The files are supplied as .png and are 512x384 which in the model is resized to 196x196 for application to ResNet50.

![Train_data](https://user-images.githubusercontent.com/49917684/161129509-b188e3a8-1f21-48b1-a5eb-2cdac2f18229.png)

Available at: https://www.kaggle.com/datasets/tentotheminus9/seti-data

## Model Performance



## Model Structure
