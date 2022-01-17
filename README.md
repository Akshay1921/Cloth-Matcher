# Clother-Matcher
Hello everyone this repository  contains the required files and code to deploy Cloth-Matcher on any system with the custom Detectron2 model (https://drive.google.com/file/d/1tozvVavKOkn0v0jR0VpJ3rVM2qmNz38Z/view?usp=sharing)

In the Clothe-Matcher.ipynb, we implied a Detectron2 model (Faster R-CNN) to extract cloth images from PDFs and/or any other sources containing .jpeg,.png etc , using a tensorflow model (VGG16-imagenet) we extract features of the  images in the main directory  and store them temporirily while the program is running , this information is then used to  analyze it with the image  given by the user to find the most matching  10 images  from the catalog.

The .ipynb file  has UI based on tkinter  

