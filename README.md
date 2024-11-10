# website-screenshot-stitching
Website screenshot images stitching using OpenCV for my Computer Vision additional grade points.

I learnt and took the code from Adrian Rosebrock on his website (www.pyimagesearch.com) with little changes to fit what I wanted. 
To be detailed, the image stitching from his website is only working horizontally (left-right). However, as we know website screenshot images is taken vertically. In the end, the method he is using will not working for my case. 
So, the little changes are made for stitching images that taken top-bottom (vertical). To make it simple, I rotate the input images. I also added few lines so that user could insert their desired output file name and input folder containing images that they want to stitch.

Credits:

https://www.pyimagesearch.com/2018/12/17/image-stitching-with-opencv-and-python/
https://www.pyimagesearch.com/2017/01/02/rotate-images-correctly-with-opencv-and-python/
