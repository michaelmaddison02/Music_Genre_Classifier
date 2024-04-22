## Action Recognition - Binary Classifier for Juggling Balls

\## Author: Michael Maddison  
\## Collaborators: Lindsay Harris

In this project, I build a Binary Classifer to classify JugglingBalls videos as positive and all other videos as negative. I then build a multi-class classifier for all 30 action classes.

**Description of Video Data:** We extracted features from the InceptionV3 model that has been pre-trained on the ImageNet-1k dataset. Frames are extracted from each video, and the pre-trained was used to obtain a 2048-D feature vector for every frame. We store the feature vectors for the first 20 frames. For example, you will find an array of shape (2355, 20, 2048) for train_feature, where the array contains features for 2,355 videos. Each video is represented by 20 frames, and each frame is encoded by a 2048-dimensional feature vector.
