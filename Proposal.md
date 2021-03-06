

# CS301 Group 3
## Project : Character Recognition

## What is the problem that you will be investigating? Why is it interesting?
The problem that we will be investigating is character recognition. This is an interesting problem to investigate because using computer vision to recognize different letters and strings can be very important in many ways. Detecting vehicle license plates, the text on signage and storefronts, or even attempting to read captcha images all make this a very interesting problem to try to come up with a solution for.

## What reading will you examine to provide context and background?
There is a short course on Computer Vision here - https://www.kaggle.com/learn/computer-vision. This will be beneficial to learn how exactly to implement our algorithm. Along with this course, there are very helpful videos on youtube and thorough explanations on the internet when it comes to character recognition.

## What data will you use? If you are collecting new data, how will you do it?
There are various sources of information on this topic on the internet. In order to start our project, we will be using information contained on https://www.kaggle.com/kdnishanth/characterrecognitionfromnumberplate. This link provides a simple training dataset that will allow for us to train our algorithm.

## What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations? You don’t have to have an exact answer at this point, but you should have a general sense of how you will approach the problem you are working on.
This is a classification problem using computer vision. From the algorithms that we have briefly looked at, we will need to create an OCR algorithm. https://www.itransition.com/blog/ocr-algorithm goes into brief detail about how the algorithm is going to be implemented. According to this document there are 5 important steps for the development of this algorithm: Acquision, Preprocessing, Segmentation and feature extraction, Training, Verification and re-training. Along with this, https://labelyourdata.com/articles/ocr-with-deep-learning refers to using a CNN for deep learning OCR. We are still determining the exact method that we will use.

## How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate #and/or compare your results (e.g. what performance metrics or statistical tests)?
Our results will be evaluated by comparing our ŷ values (our prediction) to our y values (our ground truth). We expect there to be some errors, and we will need to determine how much data to feed our algorithm to avoid overfeeding. Optimistically, we expect greater than 90% success rate. We will need to review where our algorithm is failing and make the appropriate modifications. The exact methods are still to be determined.
