# traffic-signs-classification
Neural networks creation (4 models for comparison) for multi-class image classification

# Comp_Int_sigmoid_vs3   
This model consists of 3 convolutional layers with filters=32, kernel=5×5, activation=′relu′ one last convolutional layer with filters=64, kernel=5× 5, activation=′relu′ . In between, there are max pooling layers with poolsize=(2, 2) and in the end a Dropout(0.25) layer. After that, we flatten the data. A dense layer with units=128, activation= ′relu′ is added, one more Dropout(0.5) layer to avoid over-fitting and then a last dense layer with units=20, activation= ′sigmoid′. Accuracy is chosen as the validation metric and categorical crossentropy as the cost.

# Comp_Int_sigmoid_vs3b
This model consists of 3 convolutional layers with filters=32, kernel=5×5, activation=′relu′ one last convolutional layer with filters=64, kernel=5× 5, activation=′relu′ . In between, there are BatchNormalization layers followed by max pooling layers with poolsize=(2, 2), in the end a Dropout(0.35) layer. After that, we flatten the data. A dense layer with units=128, activation= ′relu′ is added, one more Dropout(0.5) layer to avoid over-fitting and then a last dense layer with units=20, activation= ′sigmoid′. Accuracy is chosen as the validation metric and categorical crossentropy as the cost.

# Comp_Int_softmax_vs3
This model consists of 3 convolutional layers with filters=32, kernel=5×5, activation=′relu′ one last convolutional layer with filters=64, kernel=5× 5, activation=′relu′ . In between, there are max pooling layers with poolsize=(2, 2) and in the end a Dropout(0.25) layer. After that, we flatten the data. A dense layer with units=128, activation= ′relu′ is added, one more Dropout(0.5) layer to avoid over-fitting and then a last dense layer with units=20, activation= ′softmax′. Accuracy is chosen as the validation metric and categorical crossentropy as the cost.


# Comp_Int_softmax_vs3b
This model consists of 3 convolutional layers with filters=32, kernel=5×5, activation=′relu′ one last convolutional layer with filters=64, kernel=5× 5, activation=′relu′ . In between, there are BatchNormalization layers followed by max pooling layers with poolsize=(2, 2), in the end a Dropout(0.35) layer. After that, we flatten the data. A dense layer with units=128, activation= ′relu′ is added, one more Dropout(0.5) layer to avoid over-fitting and then a last dense layer with units=20, activation= ′softmax′. Accuracy is chosen as the validation metric and categorical crossentropy as the cost.
