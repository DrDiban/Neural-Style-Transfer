# Neural-Style-Transfer
Neural style transfer applied to transfer room design

## Description

In this work, neural style transfer was used to transfer a room design to a target room image.

Neural style transfer is based on VGG-19 model which has 19 layers, 16 convulation layers and 3 fully connected layers. Only the convulation layers will be used in Neural style transfer. 

There are mutiple parameters/hyperparameter that can be tuned to obtain different outcome on the target image from neural style transfers. First, the choice of content layer from the 16 convulation layers. Second, the choices of the style layers from the 16 convulation layers. Note that multiple layers can be used here and the impact of each layers on the outcome can be adjusted through changing the fraction of that layer on the overall style cost. Third, the the hyperparameter of alpha (weighting the importance of the content cost) and beta (weighting the importance of the style cost).   

In this first part of this work, the impact of using different style and cost layer on the outcome of the target image will be examined. To simply the scope of the work, only the three layers for content are chosen i.e. Conv1_1, Conv4_2 and Conv5_4. While for the style layer, only single layer rather than multiple layers are considered. All 16 convulation layers were considered for style. The hyperparameters of alpha and beta set at 10 and 30 respectively.

In the second part of this work, the content and style layer identified in the first part that produces the best neural style transfer is used to transfer other room design images.  

## Result

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
