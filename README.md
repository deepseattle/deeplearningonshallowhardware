# Deep Learning on Shallow Hardware

Code and information repo for ["Deep Learning on Shallow Hardware Project"](https://github.com/deepseattle/projects/blob/master/DeepLearningOnShallowHardware.md) group of the [Seattle Deep Learning Meetup](https://www.meetup.com/Seattle-Deep-Learning-Meetup/)


"Main.py" is almost identical to the code from [m.zaradzki's repo](https://github.com/mzaradzki/neuralnets/tree/master/vgg_faces_keras) to test a pretrained VGGFace model on celebrities in Keras . This [article](https://aboveintelligent.com/face-recognition-with-keras-and-opencv-2baf2a83b799) explains the repo and code.

The pre-trained models weights are from:


Load VGG weigths from .mat file
http://www.vlfeat.org/matconvnet/pretrained/#face-recognition

Download from console with :
wget http://www.vlfeat.org/matconvnet/models/vgg-face.mat

Alternatively :
wget http://www.robots.ox.ac.uk/~vgg/software/vgg_face/src/vgg_face_matconvnet.tar.gz



To find the closest celebrity match to a user supplied image, updated the path in line 222 of "Main.py"
