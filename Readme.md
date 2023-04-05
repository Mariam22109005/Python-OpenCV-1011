Histogram equalization is a method in image processing of contrast adjustment using the image’s histogram.This method usually increases the global contrast of many images, especially when the usable data of the image is represented by close contrast values. Through this adjustment, the intensities can be better distributed on the histogram. This allows for areas of lower local contrast to gain a higher contrast. 
![image](https://user-images.githubusercontent.com/125149919/221768011-18caa140-f0d8-4263-a488-76e568e2dec3.png)

Histogram equalization accomplishes this by effectively spreading out the most frequent intensity values. The method is useful in images with backgrounds and foregrounds that are both bright or both dark.
![image](https://user-images.githubusercontent.com/125149919/221767563-cb51b548-7298-48bb-949e-23a5dd86d7a5.png)

OpenCV has a function to do this, cv2.equalizeHist(). Its input is just grayscale image and output is our histogram equalized image.Image Blurring refers to making the image less clear or distinct. It is done with the help of various low pass filter kernels.
![image](https://user-images.githubusercontent.com/125149919/221768200-97e4a384-d06e-4048-9b00-142c8adec902.png)
Advantages of blurring:
It helps in Noise removal. As noise is considered as high pass signal so by the application of low pass filter kernel we restrict noise.

It helps in smoothing the image.

Low intensity edges are removed.

It helps in hiding the details when necessary. For e.g. in many cases police deliberately want to hide the face of the victim, in such cases blurring is required.

Important types of blurring:
Gaussian Blurring:Gaussian blur is the result of blurring an image by a Gaussian function. It is a widely used effect in graphics software, typically to reduce image noise and reduce detail. It is also used as a preprocessing stage before applying our machine learning or deep learning models.
E.g. of a Gaussian kernel(3×3) 

![image](https://user-images.githubusercontent.com/125149919/221768519-5b6153da-ea34-44ea-a8b3-80b817ea762b.png)

Median Blur: The Median Filter is a non-linear digital filtering technique, often used to remove noise from an image or signal. Median filtering is very widely used in digital image processing because, under certain conditions, it preserves edges while removing noise. It is one of the best algorithms to remove Salt and pepper noise.

![image](https://user-images.githubusercontent.com/125149919/221768772-466e2c2a-0eef-480a-8f78-860b67fd6e25.png)

Bilateral Blur: A bilateral filter is a non-linear, edge-preserving, and noise-reducing smoothing filter for images. It replaces the intensity of each pixel with a weighted average of intensity values from nearby pixels. This weight can be based on a Gaussian distribution. Thus, sharp edges are preserved while discarding the weak ones.


<div align="center">
      <h1> <img src="https://viso.ai/computer-vision/opencv/" width="80px"><br/>Python Opencv</h1>
     </div>
<p align="center"> <a href="#" target="_blank"><img alt="" src="https://img.shields.io/badge/Website-EA4C89?style=normal&logo=dribbble&logoColor=white" style="vertical-align:center" /></a> <a href="https://twitter.com/MariamA26920464" target="_blank"><img alt="" src="https://img.shields.io/badge/Twitter-1DA1F2?style=normal&logo=twitter&logoColor=white" style="vertical-align:center" /></a> <a href="https://www.facebook.com/mariam.akter.7169/" target="_blank"><img alt="" src="https://img.shields.io/badge/Facebook-1877F2?style=normal&logo=facebook&logoColor=white" style="vertical-align:center" /></a> <a href="#" target="_blank"><img alt="" src="https://img.shields.io/badge/Instagram-E4405F?style=normal&logo=instagram&logoColor=white" style="vertical-align:center" /></a> <a href="https://www.linkedin.com/in/mariam-akter-674507256/}" target="_blank"><img alt="" src="https://img.shields.io/badge/LinkedIn-0077B5?style=normal&logo=linkedin&logoColor=white" style="vertical-align:center" /></a> </p>

# Description
#

# Features
#
# Screenshots
 <img src="#"> <img src="#"> <img src="#"> <img src="#"> <img src="#">
# Tech Used
 ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
      
# Add More Details:
Anything else that you want to add for users? You can write it here in markdown and see preview in real time. You can add anything that you want, for example

### You can add How to Setup:
- Step 1: this is step 1
- Step 2: do this, do that

### You can add API references
| Syntax | Description |
| ----------- | ----------- |
| AndroidX | Refactored versions of the Android APIs that are not bundled with the operating system. |
| AndroidX Test | Includes APIs for testing your Android app, including Espresso, JUnit Runner, JUnit4 rules, and UI Automator. |

### You can add 
[Links](https://itsvg.in)
 
![](https://img.shields.io/badge/IMAGES-4298B8.svg?style=for-the-badge&logoColor=white)
# If you don't want to add this section, just clear all the text written here.

      
<!-- </> with 💛 by readMD (https://readmd.itsvg.in) -->
    
