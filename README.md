Team Members:

Saumya Shah - [Saumya Shah - LinkedIn](https://www.linkedin.com/in/saumya-shah-9b2579273/)

Bhavin Baldota - [Bhavin Baldota - LinkedIn](https://www.linkedin.com/in/bhavin-baldota-103553234/)

Aditya Chavan - [Aditya Chavan - LinkedIn](https://www.linkedin.com/in/aditya-chavan-5117aa268/)

Sharvari Korde - [Sharvari Korde - LinkedIn](https://www.linkedin.com/in/sharvari-korde-85b993268/)

Introduction

Heat treatement of bearing components involves multistage operations, where the parts are taken at inlet section and processed with various treatments. There is a need to monitor the incoming and outgoing parts in the furnace. In case of parts coming out are less than that of inlet few parts are stuck in various section of the multistage process. The missing parts which are stuck at different locations in the multistage operation unit , results in interior quality loss of material.

Objective

- To develop a computer vision system for real time counting of parts at inlet and outlet sections of the multistage heat treatment furnace.
- To use AI-YOLOv8 model for achieving 99.9% accuracy.
- To deliver optimum perfomance in the harsh industry environment.
- To use hardware resources with optimum consideration of cost and reliability.

Challenges

Here are following challenges in implementation of the real time part counting system:
- Size of the part is smaller (25-75 mm).
- Working environment has presence of dust, vibrations and maximum temperature upto 70°C.
- The conveyer moves the parts at inlet section with different velocities depending on size of the part.
- The part movement at outlet of the system is random and unpredictable. There are cases, where the parts are overlapping and get stuck along the conveyer.

Results/Findings

- Perfect Classification: The matrix shows perfect classification with a diagonal matrix where both 'Ring' and 'background' classes are correctly predicted with 100% accuracy (values of 1.00 along the diagonal).
- No Misclassification: There are no off-diagonal elements, indicating that there were no misclassifications between the 'Ring' and 'background' classes.
- Model Performance: This result indicates an excellent model performance on the test set, with no false positives or false negatives.
- Balanced Dataset: The normalized matrix suggests that both classes have been handled well, assuming the dataset is balanced.
- Overall, the confusion matrix demonstrates the model's effectiveness, accurately classifying the given image classes.
