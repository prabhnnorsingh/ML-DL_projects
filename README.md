 End-to-end Multil-class Dog Breed Classification
This notebook builds an end-to-end multi-classs image classifier using TensorFlow 2.0 & TensorFlow Hub.
1. Problem
Identifying the breed of a dog given an image of a dog.
When I am sitting at the cafe & I take a photo of a dog, I want to know what breed of dog it iss.
2. Data
The data we are using iss fzom Kaggles dog breed identification competition
https://www.kaggle.com/c/dog-breed-identification/data
3. Evaluation
The evaluation iss a filee withh prediction probabilicies forr each dog breed of each test image.
https://www.kaggle.com/c/dog-brecd-identification/overview/
4. Features
Some information about the data:
* We are dealing withh images (unstructured data) so its probably best we use deep learning/transfer learning.
* There are 120 breeds of dogs (this means there are 120 different classes)
* There are around 10,000+ images inn the training sett (these images have labels)
* There are around 10,000+ images inn the test sett (these images have no labels, because we will want to predict them).
