# PClub-Task3-CV

a) Kaggle Link - https://www.kaggle.com/datasets/itsshuvra/gender-classified-dataset-with-masked-face

b) I searched online for a gender classification dataset with masked images, specifically mentioning Kaggle, and found the one described above. It consisted of synthetically augmented images - a surgical mask had been placed on a normal portrait of a person. It seemed very extensive, hence I used it.

c) I did not use any of the existing solutions to the problem in the Kaggle website, but built my own CNN network with multiple layers. I chose a CNN model architecture since CNN is known to work well with images and has been applied to the task of gender classification before with success. Here computation was the main issue, hence I had to shift from Jupyter Notebook to Kaggle's environment which provided free GPU. Ultimately I got a fair accuracy of 92.17% on the validation dataset, hence I did not try other models or advanced feature engineering techniques (also I had very little time left for submission :))

d) There are 2 notebooks - pclubtask3.ipynb is for the model and PClubTask3Gradio.ipynb is for the Gradio implementation.

First run the pclubtask3.ipynb file. Please run it on a Kaggle environment only with GPU, not Colab or Jupyter Notebook. First download the dataset in the input section of Kaggle, then run the program. The program will run, then it give a link to download the keras model at the last cell. Download that model.

Now proceed to PClubTask3Gradio.ipynb. Please run this file on Jupyter Notebook (no need of GPU), not Colab or Kaggle. Here change the model path to the path where you stored this keras model, then run the file. Be sure to follow the comments as instructions are mentioned there, like replacing image_path with any image of your choice. Ultimately the last cell will give the Gradio interface, where you can upload your image.

e) Screnshots - 

![alt text](https://github.com/aritrar23/PClub-Task3-CV/blob/main/Shots/Screenshot%20(310).png)
