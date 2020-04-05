# Advance Lane Lines Detection
### Udacity - Self-Driving Car NanoDegree

**Author:** Bryan Rosales<br>
**Date:** August 17th, 2017


Overview
---

The scope is to detect lane lines using an advance technique of computer vision. The pipeline uses a picture of the road and then apply images processing and perspective transformation to obtain a clear vision of the lanes lines. Then, applying binary transformation, it is possible to identify the pixels on every lane line and using poly() function to build a polinomial degree 4 that model the line of the lane. Having the polynomial, the algorithm is able to extrapolate some point to build a solid line and security area where the vehicle can move forward. For more detail of the project please see [WriteUp P4.html]().


Files
---
- [P4.ipynb](https://github.com/brosales8/Advance_LLines_Detection/blob/master/P4.ipynb) Jupyter Notebook file providing the code with advance techniques to detect lanes lines.
- [WriteUp P4.html](https://github.com/brosales8/Advance_LLines_Detection/blob/master/WriteUp%20P4.html) Step by step explanation of the process followed to reach the scope of the project.
- [/test_images](https://github.com/brosales8/Advance_LLines_Detection/tree/master/test_images) Images used to develop the solution.
- [/output_images](https://github.com/brosales8/Advance_LLines_Detection/tree/master/output_images) Output images delivered for the pipeline with lane lines detection.
- [/trans_images](https://github.com/brosales8/Advance_LLines_Detection/tree/master/trans_images) Samples of images transformed. 
- [/videos](https://github.com/brosales8/Advance_LLines_Detection/tree/master/videos) Videos used to develop the solution showing the original video and final video with secure moving forward area.


