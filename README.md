# Object-Detection-and-Image-Segmentation-for-Autonomous-vehicle
This project effectively built and trained a model that can produce a top-down view of the surrounding area of an ego car by

(1) locating and classifying objects on the road from images captured by six cameras on the car and 
(2) generating the road map layout by semantic image segmentation.

- **configs** : Enable modification of all preset variables within single directory (consisting of one or many config files for separate tasks)
- **data** : Include example a small amount of data in the Github repository so tests can be run to validate installation

## Setup
Clone repository and update python path
```
repo_name=Image-Recognition-for-Autonomous-Driving.git
username=Evaaaaaaa
git clone https://github.com/$username/$repo_name
https://github.com/Evaaaaaaa/Image-Recognition-for-Autonomous-Driving/
cd $repo_name
echo "export $repo_name=${PWD}" >> ~/.bash_profile
echo "export PYTHONPATH=$repo_name/src:${PYTHONPATH}" >> ~/.bash_profile
source ~/.bash_profile
```
1. Please run train.py to generate two model paramter files.
2. The image folder is ../data. Might need to change to actual path. 
3. A pretraining script on Resnet is provided, but is not used by default.
