# KNN-Classification (from scratch)
Image Classification

The Dataset: The Animals datasets consists of 3,000 images with 1,000images per dog, cat, and panda class, respectively. Each image is represented in the RGBcolor space. It is better to preprocess each image by resizing it to 32x32 pixels. Taking into account the three RGB channels, the resized image dimensions imply that each image in the dataset is represented by 32x32x3 = 3,072 integers.

![Cats](https://user-images.githubusercontent.com/48844625/54872253-cbb36980-4d86-11e9-9c02-3166e2dbe38f.PNG)
![Dogs](https://user-images.githubusercontent.com/48844625/54872254-cbb36980-4d86-11e9-8cb6-dfb8102020e1.PNG)
![Pandas](https://user-images.githubusercontent.com/48844625/54872255-cc4c0000-4d86-11e9-9f89-75df3a7d524d.PNG)


Step 1:
 - Split the Dataset: Using three splits of the data. One split for training, one split for validation and the other for testing. 
 
Step 2:
 - Train the Classifier: k-NN classifier will be trained on the raw pixel intensities of the images in the training set by converting the
   images to data vectors with labels. To calculate the distance with K- Neighbors we use L1 Distance as the measure to for the
   distance between the images.

Step 3:
 - Evaluate: Once k-NN classifier is trained, performance accuracy, precision, recall, F-measure metrics are evaluated on the test set. 
