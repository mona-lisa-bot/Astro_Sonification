# Astro_Sonification
Image to Audio conversion.

**<h2>Step1: Extracting RGB Data of Galaxy Images</h2>**
Given a data set of galaxy images in .npy format. I have used OpenCV, Matplotlib libraries to extract the RGB values and visualize them. 
The RGB values have been stored in a csv file.

**<h2>Step2: Mapping the RGB values to audio elements such as pitch, duration, volume</h2>**
The rgb values are mapped to audio elements and thus the images are now converted into audio. The result has been stored in .wav files.
