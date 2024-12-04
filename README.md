# On-Edge Mobile Diagnosis of Malaria Parasites using Machine Learning.

This project aims towards optimizing machine learning models for Malaria Parasities diagnosis and localization through on-edge devices. The general methodology followed focuses on attempting to deploy an accurate machine learning model on a mobile device while maintaining an acceptable application size given IOS and Android limitaions of ~100MB maximum size. The application developed comes with two options; classification and object detection through a user-friendly interface. The methodology followed in this work is shown below.  

![System Diagram](Images/Methodology.png)

The qunatization methods used include floating point 16 (FP16), Integer Qunatization using representation learning (INT-REP), and Qunatization Aware Training (QAT). All obtained models are available at models folder. The release version of the application developed is available under mobileapp folder. The project report is available at the main branch. 
