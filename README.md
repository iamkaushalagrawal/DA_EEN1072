This repository contains the dataset used for a college project submitted as part of the Data Analysis And Machine Learning Module at Dublin City University.

The dataset includes information about PASCAL VOC 2012 Segmentation dataset for object detection. The dataset contains color images labeled for the presence of 20 object classes. 
Each image may contain one or more of these objects, making it a multi-label classification problem.
Data Source:
•	The dataset was sourced from the official PASCAL VOC 2012 dataset.
o	http://host.robots.ox.ac.uk/pascal/VOC/voc2012/
o	https://public.roboflow.com/object-detection/pascal-voc-2012

•	Accompanied by a CSV file that maps each image filename to a 20-dimensional binary label vector.
Dataset Structure:
•	Training set: 12,321 images
•	Validation set: 3,422 images
•	Test set: 1,369 images

Label Information:
•	20 object categories: aeroplane, bicycle, bird, boat, bottle, bus, car, cat, chair, cow, diningtable, dog, horse, motorbike, person, pottedplant, sheep, sofa, train, tvmonitor.
•	The label format is binary (1 = present, 0 = absent) for each object class.
