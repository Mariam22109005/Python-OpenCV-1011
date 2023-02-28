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

