# di504-project-face-emotion-recognition
for di504 course at metu. this is a deep learning project for face emotion recognition with different cnns.

----------
Default parameters: optimiser: Adam, learning_rate=0.0001, loss = categorical_crossentropy, metrics = accuracy, epochs: 50/100

Some callbacks: early stopping, reduce learning rate

--------------
Model # | Model
------ | ------
1      | Custom CNN with Different Learning Rates of 1, 0.01, 0.0001
2      | Custom CNN with Data Augmentation
3      | Simpler Custom CNN
4      | Deeper Custom CNN
5      | Custom CNN with Residual Blocks
6      | Custom CNN with Separable Convolutions
7      | Custom CNN with Global Average Pooling
8      | Transfer Learning with VGG16
9      | Transfer Learning with ResNet50
