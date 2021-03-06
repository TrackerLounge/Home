# Home
Main Menu of Projects

# Tracking
[Three Box Tracking Pit for the Home Shop](https://github.com/TrackerLounge/ThreeBoxTrackingPitForTheHomeShop)
A tracking pit is used to study pressure releases in a track to determine the speed, direction and body position of a individual or animal at that snapshot in time. This page describes a small tracking pit setup ideal when space is limited consisting of 3 boxes containing: hard packed sand, moist soft sand, and dry loose sand.  

[Digital Tracking Pit](https://github.com/TrackerLounge/DigitalTrackingPit)
A collection of tracks (foot prints) 3D models depicting common walking patterns and pressure releases.

[Tracking and Photogrammetry](https://github.com/TrackerLounge/TrackingAndPhotogrammetry)
Convert pictures of a track or foot print into a digital model of the track for further forensic analysis. This can also aid in examining pressure releases. Such a digital model can server as a useful teaching aid.

[Tracking and Edge Detection](https://github.com/TrackerLounge/TrackingAndEdgeDetection)
Computer vision relies on edge detection and object segmentation to make sense of the world. Edge detection on footprints or tracks is very difficult. On this page we will explore/experiment/evaluate some image processing pipelines to find the edge of a track for image segmentation purposes. We will try direct edge detection, thresholding and edge detection, edge detection by segmentation, and edge detection by FFT (Fast Fourier Transform), among others.

[Tracking and Hog Descriptors in Java OpenCV](https://github.com/TrackerLounge/TrackingAndHogDescriptorInJavaOpenCV)
I implemented logic in Java and OpenCV, to create HOG Descriptors for a track. I was curious to see how the process might work with my test images.

[Java OpenCV HOG Image Comparison and Matching](https://github.com/TrackerLounge/TrackingAndHogDescriptorInJavaOpenCV/tree/master/HOGCompare)
I experimented with OpenCV HOGDescriptor - compute(), detect() and detectMultiScale() to see how will it will work when comparing a footprint (track) to a shoe sole. It appears that HOGs are too lenient for this purpose, finding matches on too dissimilar tracks and shoe soles.

[Tracking and SURF Feature Descriptions in Java OpenCV](https://github.com/TrackerLounge/OpenCVSURF)
I show how to compile opencv and opencv_contrib on your local machine to run SURF feature descriptions on a track image. I am curious to see how well this works on different types of track images.

[Experiment in image comparison - Track And Sole Comparison](https://github.com/TrackerLounge/TrackAndSoleComparison)
I experimented with an image of a track and an image of a shoe sole to see if I could match the track to the shoe sole. I tried a number of pre-processing steps to make the image of the track and shoe sole look as similar as possible (e.g. ImageJ bandpass filter, make binary, edge detection, etc.). In the experiment, I did not know what bandpass filter settings were best, so I automated the process to generated many versions of the images by varying the values. I compare resulting images using SURF. The experiment was a failure.

[Experiment with OpenCV matchTemplate()](https://github.com/TrackerLounge/OpenCVTemplateMatch)
Explore OpenCV's matchTemplates() method, to find similar images in a scene image. Draw a bounding box around all matching images above a given threshold. Experiment with rotating and scaling the template to find variations in the scene. Extract these matches and align them all so they share the same degree of rotation and can be compared side by side.

[Experiments with Image Processing, Computer Vision, and Machine Learning and Tracking](https://github.com/TrackerLounge/TrackingAndComputerVision)
Experiment with Machine Learning to identify a footprint as 'right' or 'left'.

Experiment to identify the edge of a track or footprint using edge detection to improve the ability of TensorFlow to identify a foot print as 'right' or 'left'.

Experiment to see if additional pre-processing could improve edge detection on a foot print in sand or dirt. This included coloring the track based on the Z-axis (or by elevation) and adding topographic lines to the track and surrounding surface. 

These techniques were utilized to read and evaluate pressure releases in the track.

# Martial Arts
[DIY Chin Na Joint Lock Training Dummy - Dojo Joe](https://github.com/TrackerLounge/DojoJoe)
A training dummy that can be built at home and used to practice martial art joint locks common to Tai Chi Chin Na, Aikido, Judo, etc. The build process is provided here.

[DIY Wing Chun Training Dummy - Little Wing](https://github.com/TrackerLounge/LittleWing)
A Wing Chun dummy mounted in a door way or door frame, that can be installed in an apartment when space is limited. The build process is provided here.
