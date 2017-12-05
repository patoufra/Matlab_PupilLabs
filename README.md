# Matlab_PupilLabs
Basic commands for interfacing Matlab to Pupil Capture via zmq

These commands build on the Matlab-ZMQ binders developed by fagg and available at: https://github.com/fagg/matlab-zmq
The only thing coming on top of that are the 'notifications' that are understood by Pupil Capture and a few of its plugins. On top of the ZMQ binders, you need to serialize the 'notifications' that you want to send using msgpack. This serialization is here performed using the dumpmsgpack() function, which I borrowed from bastibe : https://github.com/bastibe/transplant

If you improve the code or build on it I'm very interested! 

François
