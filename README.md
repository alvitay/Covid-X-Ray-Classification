# **COVID-19 Chest X-Ray Classification**

-------------------
## **Context:**
-------------------
The Coronavirus Pandemic (also called COVID-19) needs no introduction, having become one of the deadliest pandemics in recorded history since the identification of its first known case in December 2019. Patients diagnosed with this condition suffer from variable symptoms, such as fever, cough, headache, loss of smell, and loss of taste. Although most patients only develop mild-to-moderate symptoms, a significant percentage of the population suffers from severe-to-critical level symptoms. The disease has not only claimed millions of lives all over the globe, but has fundamentally changed the ways in which each of us relates to and navigates the world, having impacted  the human health, financial standing and work-life behavior of nearly every nation's economy in some way or the other. <br>

In response to the acute medical challenges associated with the outbreak, **Deep Learning algorithms have started being employed for medical image classification to help with COVID-19 diagnosis.** Convolutional Neural Networks (CNN) are one such solution used to identify COVID-19 directly from Chest X-Rays, to assist radiologists in medical analysis of the lungs by classifying patients depending on whether they're healthy, have viral pneumonia, or are affected by COVID-19.

------------------
## **Objective:**
-----------------
The project aims to **build a Convolutional Neural Network to differentiate an X-ray image of a person affected with COVID-19 from that of a healthy person or a person who has viral pneumonia (fever).**

------------------------
## **Data Description:**
----------------
- This dataset contains training set images of 3 classes which are converted into Numpy arrays.
- The dataset comprises of 3 classes:
    - COVID-19: Patients who are COVID-positive.
    - Viral Pneumonia: This is a viral fever that has similar characteristics and symptoms to COVID but is not as severe.
    - Normal: A healthy Person with no symptoms of COVID or fever.
- The data file names are:
    - CovidImages.npy
    - CovidLabels.csv

