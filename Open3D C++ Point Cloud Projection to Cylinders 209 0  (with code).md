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

