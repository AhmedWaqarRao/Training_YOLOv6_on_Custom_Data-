# Training_YOLOv6_on_Custom_Data-
This tutorial is based on the YOLOv6 repository (officially "MT-YOLOv6") by Meituan. This notebook shows training on your own custom objects. Many thanks to Meituan for putting this repository together.

Accompanying Blog Post
We recommend that you follow along in this notebook while reading the blog post on how to train YOLOv6, concurrently.

Steps Covered in this Tutorial
In this tutorial, we will walk through the steps required to train YOLOv6 on your custom objects. We use a public chess pieces detection dataset, which is open source and free to use. (There are 90,000+ more computer vision datasets here.)

To train our detector we take the following steps:

Prepare our dataset in MT-YOLOv6 format
Install MT-YOLOv6 dependencies
Load custom dataset
Run MT-YOLOv6 training
Evaluate MT-YOLOv6 performance
Visualize MT-YOLOv5 training data
Run MT-YOLOv6 inference on test images
OPTIONAL: Deployment
OPTIONAL: Active Learning
Easier Dataset Prep
This dataset was prepared using Roboflow, a set of tools developers use to build better computer vision models quickly and accurately. 100k+ developers use roboflow for (automatic) annotation, converting dataset formats (like to YOLOv6), training, deploying, and improving their datasets/models.
