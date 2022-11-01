# Important links

* Dataset source : [clothing-dataset-small](https://github.com/alexeygrigorev/clothing-dataset-small)
* Tensorflow EfficientNetV2 (used for the transfer learning) : https://www.tensorflow.org/api_docs/python/tf/keras/applications/efficientnet_v2/EfficientNetV2L
* Project Inspiration: https://github.com/alexeygrigorev/mlbookcamp-code/blob/master/chapter-07-neural-nets/07-neural-nets-train.ipynb

I have used a different base model from the one used in the original project. Also, I have used 2D Convolutional Layer as the next layer of the base model instead of Dense Layer used in the above proect which gave a better accuracy for the validation data in smaller model after Data Augmentation.
