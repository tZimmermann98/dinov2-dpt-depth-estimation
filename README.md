# dinov2-dpt-depth-estimation
This repository contains jupyter notebooks for the training of DPT-Decoder on top of a DINOv2 backbone. It was developed in context of the seminar "advanced topics in deep learning" at the university of münster for the application of predicting LiDAR ground truth from satellite images

# Setup
- install needed packages: ```pip install -r requirements.txt```
- Store the two satelite image areas in the data folder 
- Store the train area LiDAR files in the /data/tran folder
- Store the test area LiDAR files in the /data/test folder
- Add model files to the model folder
