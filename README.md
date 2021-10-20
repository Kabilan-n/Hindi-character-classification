# Hindi-letter-classification

### Hindi Character Classification:
  The problem is to work on Image classification. The input dataset will consist of images containing Hindi characters. The challenge is to identify the presence of a character in images using Convolutional Neural Networks.
  
### Dataset Description:
Dataset contains eperated test and train sets of images with Letters and images that have only background. 

Model used:  VGG with some added layers.
As the size if the images and backgrounds are different. Data augmentation is done to to equalise the size of data in differnt classes.

The backgrounds in the image with letters were removed.

![image](https://github.com/Kabilan-n/Hindi-letter-classification/blob/main/images/bg1.png)         >>           ![image](https://github.com/Kabilan-n/Hindi-letter-classification/blob/main/images/letter1.png)

The new set of images with only letters and background were fed into VGG.

Then the weights of the model with some additional layers were used on the original dataset to classify images with letters and images without letters.

At last the model is test with the given test data. The result of test data was then stored in JSON file. while validation our result. this shows 100% accuracy fot the given test dataset.

## Output 

![image](https://github.com/Kabilan-n/Hindi-letter-classification/blob/main/images/with.png)        ![image](https://github.com/Kabilan-n/Hindi-letter-classification/blob/main/images/without.png)
  

  
