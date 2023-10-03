# AS_RTSLD
Aco Shopov Real Time Sign Language Detection with Tensorflow Object Detection and Python and Deep Learning

Using Tensorflow Object Detection API, Python, pre-trained model SSD MobNet V2, created datasets (labeled with LabelImg).
Includes detection of 7 gestures : Da, Nadevanja, Stemneto, Sonce, Sili, Istorija, Pet i Sedumnaeset

## Scripts and Description:
- path_names.py - Includes paths of whole directory for easier usage in code
- collect_images.py - Collects images from web-cam and creates data set, then you label images with labelImg, and divide them in
                      train and test set
- label_map.py - Creates label map
- generate_tfrecord.py - Generates TF records (train.record and test.record)
- update_config_for_learning.py - Updates pre-trained pipeline config to our parameters
- load_model.py - Loads specified model (Includes checkpoints from 1k to 10k epochs of trained model)
- test_picture.py - Predicts image from test set
- test_video.py - Main script that predicts Sign Language in real time
- text files - include all instructions and commands to train model, evaluate model, and create the TF Records

## Results:

Demo Video : https://www.youtube.com/watch?v=HuW4YDxdDJE&ab_channel=NikolaDinevski

![2023-09-17 16_17_39-Window](https://github.com/ndinevski/AS_RTSLD/assets/61565298/ad39ce3c-a700-40a1-bb86-255aa4dbb9ef)
![2023-09-17 16_16_06-Window](https://github.com/ndinevski/AS_RTSLD/assets/61565298/f7ce3bec-aced-46f0-927e-4d0cc4473dbd)
![2023-09-17 16_18_10-Window](https://github.com/ndinevski/AS_RTSLD/assets/61565298/ce12840f-04a4-4cb7-a7ab-8aa7e5a85d0d)
![2023-09-17 16_18_28-Window](https://github.com/ndinevski/AS_RTSLD/assets/61565298/4b0449c1-9889-4a21-a0a1-28035c9fe9c7)

## Developed by:
-Petar Atanasovski
-Nikola Dinevski
