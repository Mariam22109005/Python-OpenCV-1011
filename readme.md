Transforming involves using rules to turn certain graphics into something else. Transformations come in a variety of forms, including translation, rotation, scaling up or down, and shearing. A transformation is referred to as a 2D transformation when it occurs on a 2D plane.

In computer graphics, transformations are crucial for resizing, rotating, and repositioning the graphics on the screen.

Identical Coordinates:

We must follow a sequential approach to accomplish a series of transformations, such as translation, rotation, and scaling.

Put the coordinates in translation,
To finish the composite transforma
We must add an additional dummy coordinate W to the 3*3 matrix.

This method of representing the location by three integers rather than two is known as a homogenous coordinate system. In this system, matrix multiplication can be used to describe all transformation equations. P' can transform any Cartesian point PX,Y into homogeneous coordinates (Xh, Yh, h).

Translation

A translation changes the location of an object on the screen. By adding the translation coordinates (tx, ty) to the initial coordinates X, Y, you can translate a point in two dimensions to become X′,

![image](https://user-images.githubusercontent.com/125149919/223958641-71380100-7d9f-48cb-8fc1-09273c957202.png)

From the above figure, you can write that −

X’ = X + tx

Y’ = Y + ty

The pair (tx, ty) is called the translation vector or shift vector. The above equations can also be represented using the column vectors.

P=[X][Y]
 p' = [X′][Y′]
T = [tx][ty]

We can write it as −

P’ = P + T

Rotation:
In rotation, we rotate the object at particular angle θ theta
 from its origin. From the following figure, we can see that the point PX,Y
 is located at angle φ from the horizontal X coordinate with distance r from the origin.

Let us suppose you want to rotate it at the angle θ. After rotating it to a new location, you will get a new point P’ X′,Y′

![image](https://user-images.githubusercontent.com/125149919/223958995-bffc8091-8231-4795-a1c4-ce7c3c9c8810.png)

Using standard trigonometric the original coordinate of point PX,Y
 can be represented as −

X=rcosϕ......(1)
Y=rsinϕ......(2)
Same way we can represent the point P’ X′,Y′
 as −

x′=rcos(ϕ+θ)=rcosϕcosθ−rsinϕsinθ.......(3)
y′=rsin(ϕ+θ)=rcosϕsinθ+rsinϕcosθ.......(4)
Substituting equation 1
 & 2
 in 3
 & 4
 respectively, we will get

x′=xcosθ−ysinθ
y′=xsinθ+ycosθ

Representing the above equation in matrix form,

[X′Y′]=[XY][cosθ −sinθ
           sinθ cosθ]OR
P’ = P . R

Where R is the rotation matrix

R=[cosθ −sinθ 
sinθ cosθ]

Scaling
To change the size of an object, scaling transformation is used. In the scaling process, you either expand or compress the dimensions of the object. Scaling can be achieved by multiplying the original coordinates of the object with the scaling factor to get the desired result.

Let us assume that the original coordinates are X,Y
, the scaling factors are (SX, SY), and the produced coordinates are X′,Y′
. This can be mathematically represented as shown below −

X' = X . SX and Y' = Y . SY

The scaling factor SX, SY scales the object in X and Y direction respectively. The above equations can also be represented in matrix form as below −

(X′Y′)=(XY)[Sx00Sy]
OR

P’ = P . S

Where S is the scaling matrix. The scaling process is shown in the following figure.

![image](https://user-images.githubusercontent.com/125149919/223959967-e336e0a3-0d3a-4dac-b3f1-7e279b88be10.png)

![image](https://user-images.githubusercontent.com/125149919/223960180-7104e2fe-b2ef-42a6-89f4-132ea573c0a3.png)

Reflection
Reflection is the mirror image of original object. In other words, we can say that it is a rotation operation with 180°. In reflection transformation, the size of the object does not change.

The following figures show reflections with respect to X and Y axes, and about the origin respectively.
![image](https://user-images.githubusercontent.com/125149919/223960386-15b6de29-e9c0-4641-aa67-be300e94e35e.png)

![image](https://user-images.githubusercontent.com/125149919/223960462-8a355f14-a5f7-4480-b541-f235d8ee6f90.png)

Source: <a href = "https://www.tutorialspoint.com/computer_graphics/2d_transformation.htm#:~:text=Transformation%20means%20changing%20some%20graphics,%2C%20rotation%2C%20shearing%2C%20etc">Image Transformation</a>
