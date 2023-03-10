# ICNet for Real-Time Video Segmentation

### Authors: Cem Ozan Dogan and Emre Inceoglu

![](https://github.com/emrei1/ICNet/blob/master/video-gif.gif)


This project uses the ICNet segmentation model for the real-time video segmentation task.

We use a modified version of the ICNet that uses the Resnet model as its backbone. The results yield faster fps and better accuracy.

We are able to retrieve mIoU values for up to 0.65 and fps to 50 fps.

To use the notebook, upload the `icnet.yaml` file to your root directory. Hyperparameters can be tuned from this file.
