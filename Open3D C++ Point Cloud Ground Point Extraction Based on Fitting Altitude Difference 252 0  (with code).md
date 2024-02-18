##  First, the principle of the algorithm 

###  1. Overview of the principle 

  Under normal circumstances, the difference between the elevation of a certain ground point in the point cloud and the fitting elevation obtained by fitting its adjacent points is small, while the fitting difference of non-ground points is large. By setting a reasonable width value, the fitting difference of each point Gao can be used as the basis for the separation of ground points and non-ground points, so as to complete the filtering. The fitting elevation of the point is obtained by using the method of surface fitting, which is different from the measured elevation to obtain the fitting elevation difference, and a reasonable threshold is set to separate the ground point and the non-ground point. Surface fitting generally uses least squares quadratic polynomial processing to obtain the fitting elevation of the point and calculate the fitting elevation difference. The quadratic polynomial surface fitting model is: 

In the formula: the plane coordinates of the point, is the fitting distance of the point Gao, called quadric surface fitting coefficient. Obtain the fitting elevation of the point, and then get the fitting height difference. Set the height difference threshold, greater than the threshold is defined as a non-ground point, less than the threshold is defined as a ground point. 

###  2. References 

>  Feng Maolin. Building Contour Extraction from Airborne Lidar Point Cloud under Tree Occlusion [D]. Southwest Jiaotong University, 2017. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534075
 ```  
##  III. Display of results 

###  1. Primitive point cloud 

![avatar]( 099b395e94544221b90034a9ee6d2073.png) 

###  2. Extract the results 

![avatar]( 88fdd57eebe943c1b3c05f06931bf201.png) 

##  IV. Relevant links 

