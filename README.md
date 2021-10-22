# Panorama

Out of 2 or more images create a panorama.

1. Find matches between the 2 images: using cv2 detectAndCompute and match
2. Find homography from the matches: using cv2.findHomography 
3. Get image corners of image 1 and 2: size of the images 
4. Get bounding corners: apply the homography to the images and find the top-left and bottom-right corners coordinates 
5. Combine using linear alpha blending: smooth transition from one image to the other

Assingment for Georgia Tech - Computational Perception class. 
