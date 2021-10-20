# Hindi-letter-classification

### Hindi Character Classification:
  The problem is to work on Image classification. The input dataset will consist of images containing Hindi characters. The challenge is to identify the presence of a character in images using Convolutional Neural Networks.
  
### Dataset Description:
Dataset contains eperated test and train sets of images with Letters and images that have only background. 

Model used:  VGG with some added layers.

Initially the backgrounds in the image with letters were removed.
![image](https://user-images.githubusercontent.com/59824729/135139673-7504ace8-13e0-4589-a127-e161b018a93b.png)
Then the new set of images with only letters and background were fed into VGG. Then the weights of the model with some additional layers were used on the original dataset to classify images with letters and images without letters.


  

  
