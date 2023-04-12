Here's a documentation of what each colab above contains: 

a to g)Colabs to illustrate various data augmentation and generalization techniques (with A/B tests)
- l1 l2
- dropout
- earlystop
- montecarlo dropout
- various initializations and when to use what
- batch norm
- custsom dropout, custom regularization

Have tried various regularization techniques. Regularization is used to prevent overfitting, it ensures model is not too complex and can generalize well to new data.
Dropout is a technique where randomly selected neurons are ignored during training. L1 regularization encourages the model to have sparse weights, which can help to eliminate features that are not useful for the task. L2 regularization penalizes the model for having large weights, which can help to prevent overfitting by encouraging the model to use all of the features in a more balanced way.
Have also used Optimizers, which are an essential to train deep neural networks efficiently by updating the model's parameters to minimize the loss function during training.
Have tried various initialization techniques, which are important as they can have a significant impact on the training process and the performance of the model. Hence we should choose an appropriate weight initialization method that can help to improve the training process and prevent common issues such as vanishing or exploding gradients.

Colab name : Regularization.ipynb and Early_Stopping.ipynb

Colab links : 

https://colab.research.google.com/drive/1jybfxmiufO7w3JKJq5Lf1Ag6vT7mE4BM?usp=share_link

https://colab.research.google.com/drive/118oD5uu0Y3gd_JucUgnmK_JqyArHjhg1?usp=share_link

h) using callbacks and tensorboard 

This colab is for building an image classifier and Regression Multi layer perceptron using Sequential API, using keras to load dataset, model is built using sequential API, compiled, trained and evaluated. Then I have used callbacks and tensorboard for visualization.

Colab name : callbacks_and_tensorboard.ipynb

Colab link : https://colab.research.google.com/drive/1DwtG_UscTTEaIFDhM7rnjd7w59no6mcb?usp=share_link

i) using keras tuner

Keras tuner helps us search for the best hyperparameters of our deep learning models automatically, without manual tuning. Have perfromed various techniques for tuning hyperparameters in the model I developed, to avoid exploding/vanishing gradients problem, and to improve model performance.

Colab name : Regularization.ipynb

Colab link : https://colab.research.google.com/drive/1jybfxmiufO7w3JKJq5Lf1Ag6vT7mE4BM?usp=share_link

j)using keras cv data augmentation

Used KerasCV to build a preprocessing pipeline, augment a dataset, create, train, test and evaluate the model. KerasCV is used for image classification, object detection, image segmentations, image data augmentation etc. I have used the model to generate images based on input text.

Colab name : Keras_cv_data_aug.ipynb

Colab link : https://colab.research.google.com/drive/17UEaUe1uedmkT5L2lZqTkh67eaY-Umbq?usp=share_link

k) colabs for data augmentation and classification  for image, video, text, audio -

In these colabs, I have used AugLY - a data augmentations library that supports 4 modalities(audio, video, image and text) - to augment data in model training.

I have used my own audio, text, video. 
Images(image I have obtained from tensorflow dataset). 
Have done various data augmentations such as Adding noise to audio, augmentation and transformation in intensity and length of audio.
For text, swapping gender in text and other augmentations, then evaluating performance.
In video, trim video, add emoji in video, add noise, blur video etc. 
For images, I have performed data augmentation such as flip image horizonatlly, vertically, grayscale an image,  saturate image, change brightness of image, center crop image, rotate image, change contrast and random transformations. 

Colab names : image_data_aug.ipynb, text_data_aug.ipynb, video_data_aug.ipynb, Audio_Data_Aug.ipynb

Colab links : 

Video : https://colab.research.google.com/drive/1_Ty-FKXkiR8wUk6M189uPspWci7JNIS_?usp=share_link

Audio : https://colab.research.google.com/drive/1J0hVFWc3jnpjuXTVigUiu3u1YQHztam5?usp=share_link

Text : https://colab.research.google.com/drive/1PxLfl5lmDIrRn_oOxUMBrZJ0nk69vk1N?usp=share_link

Image : https://colab.research.google.com/drive/1NVkTSWDPeb7LU32IHYukBW5qvzz5SprG?usp=share_link

l) Demonstrate fastai data augmentation capablities 

In this colab, I have performed tasks such as normalization, mixup(data augmentation technique), progressive resizing approach and test time augmentation. Using Imagenette to train model from scratch

Colab name : fast_ai_data_aug.ipynb

colab link : https://colab.research.google.com/drive/1IxiwcfFDfhTrniMFL8NiZ8UoNzXJ7NEf?usp=share_link
