# Face Verification

Problem Statement:
You are working for a company ABC which has decided to automate the attendance capturing system using only the picture of the employee (selfie). However, ABC company only has one or two passport size photographs of their employees in the system for reference.

Your task is to design this image based attendance capturing system using deep learning or computer vision. The system has to match an employee's selfie with the passport size photograph and output either its a match or no match.



----->  In this project I used Tensorflow libraries to build face verification model, Build a deep neural network from scratch.
        This model learn information about object categories from one, or only a few, training samples/images. Therefore to learn information, this model requires only one image of a person which can be used for face verification.
        It uses haar cascade to detect the face and crops the face to remove the unwanted noise from the image and then resize it to (96,96).
        
        Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola  and Michael Jones in their paper, "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.
        
     
     
  ## Dataset Information
  
  Dataset contains 12 folder & in folder 1012 Employees Images are present:- 
                                The total number of selfies are :  3198
                                The total number of script(passport) images are :  1221 
        
## Requirements

TensorFlow==2.4.0
OpenCV==4.1.2
Haar Cascade XML
