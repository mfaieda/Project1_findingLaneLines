# Project1_findingLaneLines

Reflection

1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps:
First, I converted the images to grayscale,
Second, I apply guassian filter to get rid of the noise,
Third, Canny algorithm was employed to detect the edges in the image,
Fourth, I apply some mask to get the region I am interested only, 
Fifth, Hough lines algorithm was used to detect all land lines in the image.

I didn't have much time to modify the draw line function in order to draw a single line on the left and right lanes. But I am very excited and proud with what I did and I will continue working on this project even after the submission.

2. Identify potential shortcomings with your current pipeline

One potential shortcoming would be what would happen when there are many lines as in the challenge video. 

3. Suggest possible improvements to your pipeline

A possible improvement would be to use color detection inside region of interest to get rid of the extra lines.
