# EMOTION BASED MUSIC RECOMMENDATION
This web based app written in python will first scan your current emotion with the help of OpenCV & then crop the image of your face from entire frame once the cropped image is ready it will give this image to trained MACHINE LEARNING model in order to predict the emotion of the cropped image.This will happen for 30-40 times in 2-3 seconds, now once we have list of emotion's (contain duplicate elements) with us it will first sort the list based on frequency & remove the duplicates. After performing all the above steps we will be having a list containing user's emotion in sorted order, Now we just have to iterate over the list & recommend songs based on emotions present in the list.



