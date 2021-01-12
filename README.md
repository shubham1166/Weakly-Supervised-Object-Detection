# Weakly-Supervised-Object-Detection
The following repository consists of a course project(IE-643) that  I did in my Masters in IIT Bombay. The project has been under the guidance of Prof. P Balamurugan. 

We know that in case of fully supervised object detection algorithms, convolution neural network plays an important role in region proposals network but in case of weakly supervised object detection algorithms, we are mainly dependent on standard region proposal networks like selective search. This project is
based on a paper[(link)](https://openaccess.thecvf.com/content_ECCV_2018/html/Peng_Tang_Weakly_Supervised_Region_ECCV_2018_paper.html) which propose a weakly supervised region proposal network which has two stages and is dependent on only image level annotations. The first stage evaluates the objectness score of the initial bounding boxes and choose the bounding boxes with high objectness scores and the second stage
refines the bounding box from the first stage using a region based CNN network. The methods used, results, conclusions and the future work has been explained broadly in th report.

## Dataset
The dataset that has been used in the project is Google Open Images Dataset V4. The images are very diverse and often contain complex scenes with several objects (8.4 per image on average) and the data-set is annotated with image-level labels spanning thousands of classes. We have taken a subset of data-set for the simplicity. The data-set that has been used in the project has having images from only three categories: car, phone, person, with each of the category having 100 image each. The data is given in csv format with the link to the corresponding images and annotation for bounding boxes. An example of image from the data-set is shown in the figure below.
**![](https://lh3.googleusercontent.com/i4u_trbDzs0H1-pdrEYJH2MRvHfsvEIUMK_cqomGjsJUa4t0CbYF7-OJ3NKSOpOBSgxIzIYFDjbGam8jGLHGfBS-40Lzhn7kVmr1uR_uxGPjReeuUweQBymS7jr1DDop0Tknx7lg)**

