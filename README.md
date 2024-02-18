##  First, the main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574510793
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574510793
 ```  
##  III. Display of results 

![avatar]( 73957c404aff4bf49376313dd076139f.png) 

![avatar]( b6ab79839d7446929e1e177a3a388dc6.png) 

![avatar]( 03fb3618140b48d38f7aa8610a6ba6e8.png) 



--------------------------------------------------------------------------------

##  I. Overview 

  A use case for color-differentiated depth functions in Open3d. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574514253
 ```  
##  III. Display of results 

![avatar]( f33f8f3e2d064a408f05e27b23837786.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

See: PCL point clouds are equally sliced along the coordinate axis 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574536467
 ```  
##  III. Display of results 

![avatar]( 876a2e6674594a119fa4de1ee14cd272.png) 

##  IV. Relevant links 

[1] PCL 点云切片 [2] matlab 点云沿坐标轴进行等距切片 [3] Open3D 点云沿坐标轴进行等距切片 



--------------------------------------------------------------------------------

##  I. Overview of algorithms 

  Point cloud grid partitioning is a specific application case of point cloud two-dimensional grid. Similar to Open3D (C++) using point cloud to create digital elevation model DEM, the points in each grid can be saved as point clouds separately to complete the partitioning. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574558329
 ```  
##  III. Display of results 

![avatar]( ee85fa5797fd468fa81d48f4b1fa7642.png) 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

![avatar]( 53935cde2b9c4dec83c88b1d3201a009.png) 

  This article was originally created by CSDN Point Cloud Man, and the original link. Crawler websites respect themselves, treat themselves as individuals, and crawl incomplete and misleading others. Is it interesting??? 

##  First, the principle of the algorithm 

###  1. Overview of the principle 

  In the road scene, the pavement point cloud is the main plane feature, and the road point is fitted to the plane, and the point within a certain threshold range from the plane can be considered as the ground point. 

###  2. References 

>  Feng Maolin. Building Contour Extraction from Airborne Lidar Point Cloud under Tree Occlusion [D]. Southwest Jiaotong University, 2017. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574557372
 ```  
##  III. Display of results 

###  1. Primitive point cloud 

![avatar]( 792a53179fda4f118f97bbed571022c8.png) 

###  2. Extract the results 

![avatar]( 63658e0fd3f4435fbefafe848d00f8cc.png) 

##  IV. Relevant links 

[1] Open3D(C++) Ransac拟合平面分割点云 [2] Open3D(C++) 计算点到平面的距离 [3] Open3D(C++) Ransac拟合平面(详细过程版) 



--------------------------------------------------------------------------------

##  Introduction to the algorithm 

###  1. Overview 

  Calculate the Mahalanobis distance from each point to the nearest neighbor, and finally render the color according to the Mahalanobis distance. For a detailed introduction to Mahalanobis distance, see: Baidu Encyclopedia - Mahalanobis distance. 

###  2. Main functions 

  ComputeMahalanobisDistance function in Open3D calculates the Mahalanobis distance from each point to its nearest neighbor. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574521417
 ```  
For more details on Mahalanobis distance, see: https://en.wikipedia.org/wiki/Mahalanobis_distance 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574521417
 ```  
##  III. Display of results 

![avatar]( 42b9a7cafe594f1aa41aaa77ba78f4f5.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

See: PCL Point Cloud Mirror Transformation 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574558407
 ```  
##  III. Display of results 

![avatar]( b6ceb97565f04cd0a3d6b28e06e2c238.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

   Given the spherical center and spherical radius of a spherical sphere in space, the coordinates projected onto the spherical surface at any point in space are: In the formula, the distance from the point to the origin is expressed.  

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588492
 ```  
##  III. Display of results 

![avatar]( 01f1fb05b9e144f5944334c83f21f6d7.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Cylinder equation 

![avatar]( 20210530162828422.png) 

 The cylindrical equation can be expressed as follows: The following figure is a schematic diagram of a cylindrical space.  

   Among them, a point on the axis of the cylinder, the direction vector of the axis of the cylinder, and the radius of the cylinder, these seven parameters can determine a cylindrical equation. 

###  2. Projection principle 

>  1. Project the point outside the cylinder onto the cylindrical axis; 2. Translate the projection point onto the cylindrical surface according to the relationship between the projection point and the cylindrical surface. 

![avatar]( aa0e496ed9104eb792bb2a919b4d0af3.png) 

  The coordinates of the projection point from the outer point of the cylinder to the axis of the cylinder are: 

 Equation (1) is: Calculate the point-to-point direction vector: translate the projection point along the projection direction to the cylindrical surface:  

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574514147
 ```  
##  III. Display of results 

###  1. Primitive point cloud 

![avatar]( e50538e810ba4f15890cbde81621870f.png) 

###  2. Projection results 

![avatar]( 5120a3af1ae24179a90185c620eeb0c2.png) 

##  IV. Reference link 

[1] PCL 点云投影到圆柱 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Algorithm overview 

  The general equation of the three-dimensional space plane is: assume that the coordinates of the three-dimensional space that is not on the plane are, and the coordinates of the projection point on the plane are. Because the projection point to the current point is perpendicular to the plane, according to the vertical constraint condition, the following conditions are satisfied: Substituting (2) and (3) into (1) can be solved: substituting (4) into (2), (3), we can get: 

  Projection coordinates from three-dimensional point to plane are obtained. 

###  2. References 

>  [1] JIA Dingfan, XIE Xiaoyao, LIU Song. Point cloud feature extraction method based on normal vector and projection plane [J]. Journal of Chongqing University of Science and Technology (Natural Science Edition), 2021, 23 (03): 84-88. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574546
 ```  
##  III. Display of results 

![avatar]( 59e6040ce67d4a62aaec84f57107820d.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

  There are three representations of straight line equations: general formula, point-to-point formula, and parametric formula. PCL uniformly adopts the point-to-point formula. The point-to-point equation of a straight line is: Among them, the direction vector, the known point. The coordinates of the projection point from a point outside the line to the line are: In formula (2), it is:  

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577091
 ```  
##  III. Display of results 

![avatar]( 5e5fbba3310240cfaaf8fc2ccbf617b5.png) 

 Red is the original point cloud, and green is the projection result.  



--------------------------------------------------------------------------------

##  I. Overview of algorithms 

  Given the number of sampling points, downsample to a fixed number of points. Among them, the code uses a large number of functions C++ 11 STL standard library. This code is not Open3D's own calling function, just for my practice of learning C++ standard library. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574558406
 ```  
##  III. Display of results 

![avatar]( 62cce4c888ad4decb4ff98270b72eed7.png) 

##  IV. Python code 

Open3D point cloud random sampling to a fixed number of points (detailed process version) 



--------------------------------------------------------------------------------

##  I. Overview 

  The range of colors in Open3D is [0.0, 1.0]. The function rand () in the C++ can be used to generate random numbers, and its return value is an integer. To generate floating-point numbers between 0.0 and 1.0, it must be converted. First generate a random number of 0-N, and then divide it by N + 1 converted to floating-point numbers to get the random number generator we want. Where N can adjust the range of precision we want, and when N = 99, keep two decimal places. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574541029
 ```  
##  III. Display of results 

![avatar]( f5ad3893e2ff4ce3904056db69c1f0d7.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

![avatar]( 758fc05b10274ed6936208c646571b6b.png) 

###  1. Overview of the principle 

  The point cloud registration accuracy adopts the root mean square error RMSE. The smaller the root mean square error, the higher the registration accuracy. The root mean square error is defined as: 

 In the formula, it is the number of corresponding point pairs, the Euclidean distance between the corresponding points after registration, and the true value of the Euclidean distance between the corresponding points. In the absolute ideal state, the distance between the corresponding points after complete registration is 0, so the true value of the Euclidean distance between the corresponding points is 0. 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574563354
 ```  
###  3. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574563354
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574563354
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574563354
 ```  


--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

![avatar]( 4c0f94c6182b45d59d131b016209cb2f.png) 

###  1. Overview of the principle 

  The root mean square error of the distance from the point to the plane where the corresponding point is located. 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574554484
 ```  
###  3. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574554484
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574554484
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574554484
 ```  


--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview 

  Visualize the connection between matching pairs in the source and target point clouds, which is helpful for point cloud registration, especially during coarse registration, to see mismatches. 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574512453
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574512453
 ```  
##  III. Display of results 

![avatar]( d4d66c96c8264c86b10c422e35846814.jpeg) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview 

  It is known that the vector before rotation is, and after rotation is. You can calculate the rotation matrix according to the vector and transform the point cloud. There are many calculation methods and the existing code on the Internet is very complicated, such as: PCL - do point cloud rotation according to the vector, PCL introduction < 4 > do point cloud rotation according to the vector, etc. This article does not have too complicated implementation process, one line of code can be realized. 

###  2. References 

>  Zhang Weiwei, Yu Zhengzheng, Lei Weiwei. The basic concept of quaternions and the Euler formula of vector rotation [J]. Journal of Geodesy and Geodynamics, 2020, 40 (05): 502-506. DOI: 10.14075/j.jgg. 2020.05.012. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574572992
 ```  
##  III. Display of results 

>  Green before rotation, red after rotation. 

![avatar]( 6ee723452c9e4c5a9a64aaea02a75150.png) 

##  IV. Relevant links 

[1] 根据两个向量计算它们之间的旋转矩阵 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview of the principle 

![avatar]( a707adf13e014978b9adb721ed74ba4d.png) 

   The covariance matrix of a point cloud coordinate is represented by the principal component of its eigenvectors, which form an orthogonal basis. The associated eigenvalues correspond to the variance in the direction of the eigenvectors. Assuming the eigenvalues are arranged in descending order, the third eigenvector is the least squares estimate of the normal vector of the adjusted plane. The square root of the third eigenvalue can be used as a measure of the reliability of the normal vector. This value corresponds to the standard deviation of the selected point from the estimated plane, and can therefore be interpreted as a measure of the roughness of the adjusted plane.  

###   2. References 

>  [1] Glira P , Pfeifer N , Briese C , et al. A Correspondence Framework for ALS Strip Adjustments based on Variants of the ICP Algorithm[J]. Photogrammetrie - Fernerkundung - Geoinformation, 2015, 2015(4):275-289. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574586828
 ```  
##  III. Display of results 

![avatar]( b3c570ae09014202995e52715f7c726e.png) 



--------------------------------------------------------------------------------

##  First, the surface curvature 

  if 

     The greater the delta, the greater the fluctuation of the neighborhood. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574519643
 ```  
##  III. Display of results 

>  Blue is the point with the lowest curvature. 

![avatar]( 1293349249974112a5936057a5bcc0df.jpeg) 



--------------------------------------------------------------------------------

