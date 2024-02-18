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

