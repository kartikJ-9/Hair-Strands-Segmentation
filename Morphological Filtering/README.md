Hair Strands Segmentation has been approached in severeal ways. One such traditional method was to perform Morphological transformation on the image.

3 steps are involved :
Step 1: Convert image from BGR to Grayscale
Step 2: BlackHat filtering
Step 3: Intensify hair contours and apply Inpaint Algorithm

Future Work: 

This model performs poorly with the traditional OpenCV methods. So, Morphological Filtering cannot be used for deployment.
Next approach is applying Unet, a specific type of Convolutional Neural Network, that is specifically used in Biological Images for segmentation

Shoutout: 
The process of Morphological Filtering on Hair Strands Images was implemented by Sunny Shah.
https://github.com/sunnyshah2894/DigitalHairRemoval
