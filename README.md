# Bird-detection
Detection of bird using Tiny Yolo and GoogleNet Architecture.

The birds application is a bird recognition and classification program. It uses both the NCS along with TinyYolo and GoogLeNet to take an image and first get bounding boxes for birds in the image and then uses GoogLeNet to further classify the birds found. It depends on the caffe/TinyYolo and caffe/GoogLeNet appzoo examples. The provided Makefile does the following:

    Builds both TinyYolo and GoogLeNet from their repective directories within the repo.
    Copies the built NCS graph files from TinyYolo and GoogLeNet to the current directory.
    Downloads some images for the program to use
    Runs the provided birds.py program that creates a GUI window which cycles through all the .jpg images in the current directory and shows the birds and all their classifications using the networks using the Neural Compute API
