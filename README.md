# Count-number-of-Lemons-using-Machine-Learning

## Objective: 
To segment and count all the lemons present in an image given by the user


## Explanation
Here, I developed a python based tool to read an image given by the user, segment and count the number
of lemons in the image. Accept the image input by the user and display the result along with
each lemon segmented separately, count of lemons in the image and time taken for code to
execute. Generalize the thresholds in your code so as to detect and count lemons in a variety of
images.


## Used
##### contour detection and Watershed. 
##### Open CV and skimage.


## Steps Involved/approach:
##### 1. Read an image
##### 2. Convert to HSV
##### 3. Threshold it
##### 4. Blur it
##### 5. Remove extra / unwanted area
##### 6. Draw contours over original image and print both together
##### 7. Use watershed to detect touching contours
##### 8. Take avg of watershed and contours detection to give satisfactory results.
