# di504-project-face-emotion-recognition
for di504 course at metu. this is a deep learning project for face emotion recognition with different cnns.

----------
Default parameters: optimiser: Adam, learning_rate=0.0001, loss = categorical_crossentropy, metrics = accuracy, epochs: 50/100

Some callbacks: early stopping, reduce learning rate

--------------
Model # | Model
------ | ------
1      | Custom CNN with Different Learning Rates of [1](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/Learning_Rate_1.ipynb), [0.01](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/Learning_Rate_0_01.ipynb), [0.0001](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/CNN_and_CNN%2BAugmentation.ipynb)
2      | [Custom CNN with Data Augmentation](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/CNN_and_CNN%2BAugmentation.ipynb)
3      | [Simpler Custom CNN](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/Simpler_CNN.ipynb)
4      | [Deeper Custom CNN](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/Deeper_CNN.ipynb)
5      | [Custom CNN with Residual Blocks](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/CNN_with_Residual_Blocks.ipynb)
6      | [Custom CNN with Separable Convolutions](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/CNN_with_Separable_Convolutions.ipynb)
7      | [Custom CNN with Global Average Pooling](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/CNN_with_Global_Average_Pooling.ipynb)
8      | [Transfer Learning with VGG16](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/TL_with_VGG16.ipynb)
9      | [Transfer Learning with ResNet50](https://github.com/burcia1711/di504-project-face-emotion-recognition/blob/main/TL_with_ResNet50.ipynb)

-------------------
### Custom CNN Architecture 
(for models with different learning rates, and the model using the data augmented data)

![image](https://github.com/burcia1711/di504-project-face-emotion-recognition/assets/11876117/b4f97016-d59c-4883-97ab-56d5bf891df4)


### Simpler CNN Architecture

![image](https://github.com/burcia1711/di504-project-face-emotion-recognition/assets/11876117/ae1d8001-0577-4720-800f-f3bec2da055a)

### Deeper CNN Architecture

![image](https://github.com/burcia1711/di504-project-face-emotion-recognition/assets/11876117/9bfb3245-8d0f-496d-8b6e-056f32429228)

### Custom CNN with Residual Blocks

![image](https://github.com/burcia1711/di504-project-face-emotion-recognition/assets/11876117/aa53eb5a-590b-489f-b7d8-86b78a5452c4)

### Custom CNN with Separable Convolutions

![image](https://github.com/burcia1711/di504-project-face-emotion-recognition/assets/11876117/2aad39e7-366a-4d19-b699-b7a04f5b9b71)

### Custom CNN with Global Average Pooling

![image](https://github.com/burcia1711/di504-project-face-emotion-recognition/assets/11876117/4f06467a-b008-4bb8-8c3f-c5d409072bf7)

### Transfer Learning with VGG16

![image](https://github.com/burcia1711/di504-project-face-emotion-recognition/assets/11876117/1c88b257-811c-438d-aef7-bf3521912c80)

### Transfer Learning with ResNet50

![image](https://github.com/burcia1711/di504-project-face-emotion-recognition/assets/11876117/1c798ec0-2f19-459c-b270-b2cff5dc5571)
