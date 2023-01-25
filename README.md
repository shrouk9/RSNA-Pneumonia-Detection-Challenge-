# RSNA-Pneumonia-Detection-Challenge-
Kaggle Competition

Building an algorithm to detect a visual signal for pneumonia in medical images. 
Specifically, this algorithm automatically locate lung opacities on chest radiographs.
in this project I trained used te ster R-CNN (Region-based Convolutional Neural Network). 
For convenient training, evaluation and visualization we will use Torchvision package.

![image](https://user-images.githubusercontent.com/82754493/214641648-a113fb04-394d-4ee3-b6e3-1d690cd0ac35.png)


# **Workflow**

- Gather the data i.e image dataset.

- Explore the annotations & boxs.

- Data Preprocessing and Visualization.

- Resize images & Edit Annotation for R-CNN.

- Prepare Training & validation data.

- Image Augmentation.

- Define and fine-tune the R-CNN model.

- Define some callbacks for logging and model checkpoints.

- Training the model & Evaluation.

- Save the Model.


# **Dataset Description**

The training archive contains 25,000 images of dogs and cats. Train your algorithm on these files and predict the labels for test1.zip (1 = dog, 0 = cat).

You can download it for free from <a href="https://www.kaggle.com/c/dogs-vs-cats/data"> here</a>

Don't hesitate to ask me and I will do my best to answer.
