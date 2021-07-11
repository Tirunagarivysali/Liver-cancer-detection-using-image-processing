# Liver-cancer-detection-using-image-processing

Code is completed written in python . Liver MRI is taken as input . For image enhancement  or for noise removal ,Otsu's method is used .Marker controlled watershed segmentation method is used for image segmentation. It segments the MRI image and marks them with red color . Active contour model is also added to enhance the segmented image. It detects all the unique segments and marks with green circles . Dice similarity score is calculated for the segmented image after applying watershed segmentation method and also after applying active contour model and are compared. Dice similarity score is increased from 0.019 to 0.024. 
I am attaching the input image taken and code for all the three methods .
The result images are also attached in this.
