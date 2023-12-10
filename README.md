# TibaMe_OpenCV_Homework
Submit the code for video effects in TibaMe OpenCV Homework  
YouTube link: https://youtu.be/LG9ukzYDE7o?list=PLuGDqpYxpDe8kKx9F9x81eMg45STeYOaz  

# Mario’s coin matching
Test and verification results of Mario’s coin matching.  
The effects of version v0: https://youtu.be/eJ6jYpOXroM  
Confirm the effect of matchTemplate detection.  

The effects of version v1: https://youtu.be/m6Sz7Ak6VVE  
Modify the problems of version v0:  
Modify the issue of duplicate bounding boxes.  
Display the number of bounding boxes on the image.  

# TW's coin matching
The effects of version v0: https://youtu.be/D19HQsGbVKA  
Using OpenCV's matchTemplate to Recognize Taiwan Dollar_v0 Version  

The effects of version v1: https://youtu.be/F-7UIlNt1y4  
Changing the v0 version of the photo results in an inability to recognize, even if it is changed to the same size as the original image, it cannot be recognized. Changing different matching methods is also unrecognizable. The video has detailed test results. The response from Bing Chat is as follows: 

# TW's coin findContours  
The effects of version v0: 
Based on v0 and v1, both use matchTemplate to compare photos, but they cannot get the correct number of coins when using different cameras or formats. v0 changes to use the area method to compare.

--------------------------------
When using OpenCV's matchTemplate for template matching, you may encounter some issues that prevent correct recognition of the coins in the image when changing the image. Here are some possible reasons:

1. **Lack of scale and rotation invariance in template matching**: If your coins have different sizes or rotation angles in different images, template matching may fail.

2. **Quality and clarity of the image and template**: If your template or image is of low quality, or if there are issues such as blurring or occlusion, this may affect the matching result.

3. **Color and brightness differences between the image and template**: If there are significant differences in color or brightness between your image and template, this may affect the matching result.

4. **Choice of template matching method**: OpenCV provides several template matching methods, such as `cv2.TM_CCOEFF`, `cv2.TM_CCOEFF_NORMED`, `cv2.TM_CCORR`, etc. Different methods may have different effects under different circumstances.

5. **Bit depth of the image and template**: According to OpenCV's documentation, the image and template must have the same bit depth, i.e., 8-bit or 32-bit.

If you have considered the above factors but still cannot solve the problem, you may need to consider using more complex image recognition methods, such as training a convolutional neural network. I hope this information is helpful to you!
--------------------------------

Perhaps I should try using a convolutional neural network for recognition.
