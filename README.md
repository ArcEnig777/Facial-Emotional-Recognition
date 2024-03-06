# Facial-Emotional-Recognition
The Facial Emotional Recognition System present in this python notebook makes use of TensorFlow to create a model which is trained to recognize emotion in faces with the use of the images in the FER 2013 database. It utilizes transfer learning to readjust the weights of a pre existent model known as MobileNetV2, which we readjust to have an output layer of 8 classes, then compile and fit with the previously mentioned database of Images. This process takes along time due to the amount of images in the database but once complete the model can be safely stored for use. Here is a link to an already compiled model for use: https://drive.google.com/file/d/1bvGmDj2dI3LBb8jPVnnyKNlrJKCY_ckN/view?usp=sharing

The Dataset Facial Emotional Recognition (FER) 2013 can be found here: https://www.kaggle.com/datasets/msambare/fer2013

Finaly using the model and webcam, the program parses the images of the webcam frame by frame using Computer Vision (OpenCV) and uses the model to predict the emotion on the face currently in front of the webcam. Note this can also work without a webcam but a static
image will have to be provided to the notebook.

Here is a screenshot of how it looks in action:

![image_2024-03-05_223654045](https://github.com/ArcEnig777/Facial-Emotional-Recognition/assets/99694399/16d085fd-5395-44fc-bcde-34a87e4a2846)

