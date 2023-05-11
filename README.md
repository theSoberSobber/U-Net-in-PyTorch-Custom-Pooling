# U-Net-in-PyTorch
This is an implementation of the U-Net model from the paper, [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://papers.labml.ai/paper/1505.04597).

## How does it work?
U-Net is made up of a contracting path and an expanding path.
The contracting route is a series of convolutional layers and pooling layers that gradually diminish the resolution of the feature map.
The expansive route is a succession of up-sampling and convolutional layers that gradually enhance the resolution of the feature map.

The relevant feature map from the contracting path is concatenated with the current feature map at each step in the expansive path.

## Architecture
![image](https://github.com/Mostafa-wael/U-Net-in-PyTorch/assets/56788883/4b3f54ae-e54d-41df-9eee-12572b3066d3)

## Example output
Image -> Mask -> Predicted Mask
![image](https://github.com/Mostafa-wael/U-Net-in-PyTorch/assets/56788883/ec7c3b5f-2dd3-405d-ae9c-c98744f62536)

## Implementation 
Check the attached notebook for the implementation details. 

