This tutorial discusses how to configure the Tensorflow Object Detection API in windows and how implement custom object detection.
Here we are customizing a pre trained model.

step 1:

Download the files from this repository : (https://github.com/tensorflow/models)

step 2:

Open the Anaconda Prompt and install the dependencies for windows,

pip install tensorflow==2.4.1
pip install Cython
pip install contextlib2
pip install pillow
pip install lxml
pip install jupyter
pip install matplotlib
pip install tf_slim
pip install opencv-python

3. Download codes folder
4. Copy and paste ```protoc.exe``` file in the path ```models-master\research``` from the codes folder
5. Open the Commmand Prompt in ```models-master\research``` and copy and run the command included in ```protoc command.txt```
6. You can use own own images and videos for testing.
