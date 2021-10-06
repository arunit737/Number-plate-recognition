# number-plate-recognition
Automatically detect car number plates and check language

Using tensorflow object detection api and EASY OCR to detect license plate of cars and finding the language

create new virtual env, install requirements.txt

if using the pre-trained model checkpoints:

Do not run the training lines in notebook
The model checkpoints (3 files) need to be placed in    project folder\Tensorflow\workspace\models\my_ssd_mobnet
The train-test images need to be placed in project folder\Tensorflow\workspace\images

If training model from scratch the notebook will create the required folder structure and install tfod api. The database has been taken from kaggle

