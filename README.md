
# Pneumonia-vs.-Normal-Lungs-X-Rays-CNN-Classification-Model
Deep Learning X-Rays Classification Model based on Convolution Neural Network(CNN) Algorithm.
## Objective:
* Globally, pneumonia is the leading cause of death among children under 5 years old, accounting for 14% of all deaths in this age group. In 2020, an estimated 2.3 million children under 5 died from pneumonia.
* The risk of pneumonia is highest in children under 2 years of age and in children with underlying health conditions, such as malnutrition, HIV/AIDS, or chronic lung disease.
* In adults, pneumonia is the eighth leading cause of death worldwide.
Pneumonia is an infection in our lungs caused by bacteria, viruses or fungi. Pneumonia causes our lung tissue to swell (inflammation) and can cause fluid or pus in your lungs. Bacterial pneumonia is usually more severe than viral pneumonia, which often resolves on its own. Pneumonia can affect one or both lungs. Pneumonia in both of our lungs is called bilateral or double pneumonia.

Many germs can cause pneumonia. The most common are bacteria and viruses in the air we breathe. Your body usually prevents these germs from infecting your lungs. But sometimes these germs can overpower your immune system, even if your health is generally good.

The symptoms of pneumonia can vary depending on the cause, but they often include:

* Cough, sometimes with mucus or pus
* Fever
* Shortness of breath
* Chest pain
* Chills
* Fatigue
* Muscle aches
* Headache
* Nausea and vomiting

The risk of serious pneumonia is higher in young children, older adults, and people with underlying health conditions, such as chronic obstructive pulmonary disease (COPD) or heart disease.

There are a number of things that can help prevent pneumonia, including:

* Getting vaccinated against pneumonia, especially the pneumococcal vaccine
* Getting the flu vaccine every year
* Washing your hands frequently
* Avoiding close contact with people who are sick
* Smoking cessation

**The main objective of this model is to differentiate between, X-Rays images of Pneumonia infected vs. Normal Lungs using CNN algorithm.**




## About Dataset:
This is a binary image classification datatset of two classes: 
**Pneumonia Infected Lungs** and **Normal Lungs**

The chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients aged one to five years old from the Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of the patients' routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low-quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. To account for any grading errors, the evaluation set was also checked by a third expert.

**Total Images:** 5930

**Total Pneumonia infected Lungs, X-ray training images:** 3875

**Total Normal Lungs, X-ray training images:** 1431

**Total Pneumonia infected X-ray validation images:** 390

**Total Normal Lungs, X-ray validation images:** 234

## Algorithm:
Convolution Neural Network(CNN) is a type of Deep Learning neural network architecture commonly used in Computer Vision. CNNs are inspired by the way the visual cortex works in the human brain.

CNNs consist of a series of layers, each of which performs a specific task. The first layer is the convolutional layer, which applies filters to the input image to extract features. The filters are small, 2D arrays of weights that are learned during the training process. The convolutional layer produces a set of feature maps, each of which represents a different feature of the image.

The next layer is the pooling layer, which downsamples the feature maps to reduce the amount of computation required. The pooling layer can be either max pooling or average pooling. Max pooling takes the maximum value from each region of the feature map, while average pooling takes the average value.

The final layer is the fully connected layer, which is a traditional neural network layer that makes the final prediction. The fully connected layer takes the output from the pooling layer and connects it to a set of output neurons, one for each possible class.
## Language and library:

Language: Python 3.11.4

Library: TensorFlow and Matplotlib
