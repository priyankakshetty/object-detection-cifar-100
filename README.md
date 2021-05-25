# object-detection-cifar-100

A Python program for Object Recognition for Cifar-100 dataset using Convolution Neural Net (CNN).
With this, we have achieved 53.63% accuracy using 9 layers of neural net.

**Libraries Used**
- Tensorflow
  >pip install tensorflow
  >
  The cpu version is installed using the above command. For gpu, use below command
  >pip install tensorflow-gpu
- Keras
  >pip install keras
- Cifar 100

    The Cifar 100 dataset is included in keras and can be used in the program using below command
    > from keras import cifar100

**Output**
>
>Epoch 100/100
390/390 [==============================] - 139s 357ms/step - loss: 2.0264 - accuracy: 0.5034 - val_loss: 1.9286 - val_accuracy: 0.5363
79/79 [==============================] - 6s 73ms/step - loss: 1.9286 - accuracy: 0.5363
>
>Test result: 53.630 loss: 1.929
