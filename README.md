# InceptionResNetV2_TransferLearning


#High accuracy

 1ms/step - loss: 3.4711e-04 - acc: 0.9999 - val_loss: 0.1961 - val_acc: 0.9936
 
 good for cats and dogs datasets





# Use ResNet152V2
10s 1ms/step - loss: 1.5802e-07 - acc: 1.0000 - val_loss: 0.3976 - val_acc: 0.9852

# ResnetV2 and blur_rainy_InceptionResNetV2

training dataset: rainy :12483 blur :2177 items


validation dataset:rainy :1220 items blur :380 items

test dataset : rainy : 100 items blur 100items


# blur_rainy_InceptionResNetV2_TransferLearning

 loss: 8.0245e-10 - acc: 1.0000 - val_loss: 0.6806 - val_acc: 0.9488
 
 
 Found 14660 images belonging to 2 classes.
 
 Found 1600 images belonging to 2 classes.
 
 Found 100 images belonging to 2 classes.

 Model: "resnet152v2"



 input_1 (InputLayer)            (None, 224, 224, 3)  0  
                                        .
                                        .
                                        .
                                        .
                                        .
                                        .
 post_bn (BatchNormalization)    (None, 7, 7, 2048)   8192        conv5_block3_out[0][0]           
 __________________________________________________________________________________________________
 post_relu (Activation)          (None, 7, 7, 2048)   0           post_bn[0][0]                    



 Total params: 58,331,648
 
 
 Trainable params: 0
 
 Non-trainable params: 58,331,648
 
 
 __________________________________________________________________________________________________


# ResnetV2

5s 1ms/step - loss: 7.1464e-04 - acc: 0.9998 - val_loss: 0.5614 - val_acc: 0.9550




input_1 (InputLayer)            (None, 299, 299, 3)  0                                      

                                       .
                                       .
                                       .
                                       .
                                       

conv_7b_ac (Activation)         (None, 8, 8, 1536)   0           conv_7b_bn[0][0]                 




