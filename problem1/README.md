(Pneumonia Detection using CNN)

Overview:

In this part of the assignment, I built a deep learning model using a Convolutional Neural Network (CNN) to detect pneumonia from chest X-ray images. The goal was to classify images into two categories: Normal and Pneumonia.


Dataset:

The dataset contains chest X-ray images and is divided into training, validation, and test sets.

It includes two classes:

* NORMAL
* PNEUMONIA


 What I Did:

* Loaded the image dataset
* Resized images to 224×224 pixels
* Normalized pixel values (1./255)
* Applied data augmentation (rotation, zoom, flipping)
* Built a CNN model using Conv2D and MaxPooling layers
* Added Dense and Dropout layers to improve performance
* Trained the model on training data


Model Used :

I used a Convolutional Neural Network (CNN) for this problem.

It is mainly used for image classification tasks and helps in automatically learning features from images.


Result:

The model was tested on unseen test data.

* Accuracy was used to measure performance
* Loss value was also calculated
* Model performed well in distinguishing Normal and Pneumonia images

Final test accuracy: **86.7%**



Tools Used :

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Google Colab


Conclusion

This part helped me understand how deep learning models like CNN work for image classification. I also learned how preprocessing and data augmentation improve model performance.
