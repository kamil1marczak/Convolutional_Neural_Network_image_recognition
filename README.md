# Convolutional Neural Network Image Recognition
Convolutional Neural Network that recognizes objects in images based on a database of categorized images

CNN was tested on [Horses Or Humans Dataset](https://www.kaggle.com/sanikamal/horses-or-humans-dataset) 

To use data the it was created directory 'horse-or-human/train' for train dataset and 'horse-or-human/validation' for test dataset

### Test of one

Model was tested by 2 random images of human face and horse located in directory 'test-of-one/'
In both cases test was successful

### Final results:
        
    Epoch 1/10
    2020-07-09 01:50:10.584800: I tensorflow/stream_executor/platform/default/dso_loader.cc:44] Successfully opened dynamic library libcublas.so.10
    2020-07-09 01:50:13.759798: I tensorflow/stream_executor/platform/default/dso_loader.cc:44] Successfully opened dynamic library libcudnn.so.7
    33/33 [==============================] - 25s 747ms/step - loss: 0.4445 - accuracy: 0.8004 - val_loss: 1.1152 - val_accuracy: 0.7656
    Epoch 2/10
    33/33 [==============================] - 10s 291ms/step - loss: 0.1483 - accuracy: 0.9464 - val_loss: 1.8132 - val_accuracy: 0.7383
    Epoch 3/10
    33/33 [==============================] - 9s 275ms/step - loss: 0.0913 - accuracy: 0.9649 - val_loss: 1.3397 - val_accuracy: 0.8320
    Epoch 4/10
    33/33 [==============================] - 9s 277ms/step - loss: 0.0766 - accuracy: 0.9727 - val_loss: 1.5880 - val_accuracy: 0.7969
    Epoch 5/10
    33/33 [==============================] - 13s 391ms/step - loss: 0.0613 - accuracy: 0.9825 - val_loss: 2.4742 - val_accuracy: 0.6797
    Epoch 6/10
    33/33 [==============================] - 13s 391ms/step - loss: 0.0378 - accuracy: 0.9834 - val_loss: 2.1689 - val_accuracy: 0.7578
    Epoch 7/10
    33/33 [==============================] - 13s 394ms/step - loss: 0.0441 - accuracy: 0.9834 - val_loss: 1.9061 - val_accuracy: 0.7656
    Epoch 8/10
    33/33 [==============================] - 13s 399ms/step - loss: 0.0222 - accuracy: 0.9932 - val_loss: 2.4571 - val_accuracy: 0.7422
    Epoch 9/10
    33/33 [==============================] - 13s 398ms/step - loss: 0.0293 - accuracy: 0.9893 - val_loss: 1.9882 - val_accuracy: 0.7852
    Epoch 10/10
    33/33 [==============================] - 13s 396ms/step - loss: 0.0404 - accuracy: 0.9864 - val_loss: 1.3472 - val_accuracy: 0.8242


