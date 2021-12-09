The following code which is based on experiencor project (https://github.com/experiencor/keras-yolo3). I modified the code tow work with tensorflow 2.4.To train YOLO3 from scaratch you should edit the configuration files and make sure to remove the pretrained weights for backend network. The link to the darknet-53 weights as well as different detetection dataset can be found at original link of eperiencor project. Here are important commands for training and evaluating the model:
- python train.py -c config.json for training
- python evaluate.py -c config.json
- python predict.py -c config.json -i path_to_imageset
