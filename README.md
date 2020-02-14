# Neural-Style-Transfer
Neural style transfer applied to transfer room design

## Description

In this work, neural style transfer was used to transfer a room design to a target room image.

Neural style transfer is based on VGG-19 model which has 19 layers, 16 convulation layers and 3 fully connected layers. Only the convulation layers will be used in Neural style transfer. 

There are mutiple parameters that can be to tuned to obtain different outcome from neural style transfers. First, the choice of 

In this first part of this work, the

| Style | Content Conv1_1 | Content Conv4_2 | Content Conv5_4 |
| --- | --- | --- | -- |
| Conv1_1 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv1_1.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv1_1.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv1_1.jpg" width="300">|
| Conv1_2 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv1_2.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv1_2.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv1_2.jpg" width="300">|
| Conv2_1 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv2_1.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv2_1.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv2_1.jpg" width="300">|
| Conv2_2 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv2_2.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv2_2.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv2_2.jpg" width="300">|
| Conv3_1 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv3_1.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv3_1.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv3_1.jpg" width="300">|
| Conv3_2 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv3_2.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv3_2.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv3_2.jpg" width="300">|
| Conv3_3 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv3_3.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv3_3.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv3_3.jpg" width="300">|
| Conv3_4 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv3_4.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv3_4.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv3_4.jpg" width="300">|
| Conv4_1 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv4_1.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv4_1.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv4_1.jpg" width="300">|
| Conv4_2 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv4_2.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv4_2.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv4_2.jpg" width="300">|
| Conv4_3 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv4_3.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv4_3.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv4_3.jpg" width="300">|
| Conv4_4 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv4_4.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv4_4.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv4_4.jpg" width="300">|
| Conv5_1 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv5_1.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv5_1.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv5_1.jpg" width="300">|
| Conv5_2 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv5_2.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv5_2.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv5_2.jpg" width="300">|
| Conv5_3 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv5_3.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv5_3.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv5_3.jpg" width="300">|
| Conv5_4 |<img src="Images/Style1/C-Conv1_1/c-conv1_1_s-conv5_4.jpg" width="300">|<img src="Images/Style1/C-Conv4_2/c-conv4_2_s-conv5_4.jpg" width="300">|<img src="Images/Style1/C-Conv5_4/c-conv5_4_s-conv5_4.jpg" width="300">|
