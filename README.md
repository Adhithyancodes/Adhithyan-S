# Databyte Inductions Task

# Problem Statement
To train a  CNN to classify a labeled dataset, here Iron man, Black widow, with reasonable accuracy

# My Approach and Core Logic

Preparation of Dataset:
  I have used the chrome extension "download all images" to download pictures of Iron man and Black widow, and then removed images of unwanted types and of those with size less thn 10KB, further classified them into folders of training and testing data under the folder data1.
  Then by walking throuugh the data1 folder using os library, I represented the summary of total images in each sub folders further defined their directeries to access them 
  
  Visualising:
     I have used the PIL library to display random images image, I have also used matplotlib to try that method as well
     
Loading data:
     I have used the pytorch framework to build the model. Using transforms, I have resized all the images into 64x64 and converted them into tensors. Then we group the images in folders, finally using the dataloaders we make our dataset iterable and accessible.
     
Model:
    Here I have used a model of 4 convolution layers and 4 activation laers alongwith 2 Pooling layers, these layers are arranged in two blocks 
    

# Core Logic 
