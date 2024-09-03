hello,
welcome to my project of lung disease detection using ResNet model 

dataset link:- https://drive.google.com/drive/u/0/folders/1tCjbWZD9QUbOE_4Nke2bOP7-2DJrb66t
test dataset link:- https://drive.google.com/drive/u/0/folders/1iL13H_ahh9zUDVNFeBqHaTqMCu_SSjIn

# 1. Import Libraries and Datasets

To import our data, we used image generator to generate tensor images data and normalize them. We used 428 images for training (80%) and 104 images for our validation (20&). Before we generate our data, we perform shuffling to prevents the model from learning the order of the training.

We generate a batch of 40 images and labels. The following is label names for each classifications :

- 1 = Viral Pneumonia
- 2 = Bacterial Pneumonia
- 3 = Covid-19
- 4 = Normal

here we applied ResNet 50 with self modified parameter. 
