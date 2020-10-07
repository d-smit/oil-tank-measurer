# oil-tank-measurer

This is a work in progress project exploring the possibility of estimating oil tank capacites through images alone, by considering the shadows inside and outside an oil tank. Using Python with NumPy and OpenCV, it is possible to measure these shadows. With knowledge of the sensor resolution, we can use these measurements with the tank geometries to estimate current oil capacity. 

We implement this for a refinery in Cushing, Oklahoma, seen below. 

 ![](storage_tanks_2.jpg)

## To Do
 
- Finalise storage calculation. 
- Explore Hough transforms for tank radius calculation.
