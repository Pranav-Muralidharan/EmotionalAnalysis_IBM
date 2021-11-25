# COMPREHENSIVE EMOTIONAL ANALYSIS FOR MONITORING MENTAL HEALTH OF STUDENTS

Objective:
 To identify the emotional states of students by monitoring facial expressions in high recognition at a 
high frame rate , thereby assisting teachers in helping students with their mental health problems

Abstract:
 Much of the discriminative information that we require to tell apart facial expressions that 
distinguish different emotional states of a person lies mostly in very subtle movements around the 
eye. So, if in a real-time monitoring scenario we are able to accurately map these movements to 
underlying emotional states of a person, we could monitor his/her mental health.
Our proposal conducts a comprehensive spatiotemporal analysis of facial geometries identified in 
images captured by a high-resolution camera and increased frame-rate to map subtle changes in 
facial expressions which could be as minute as a small muscle movement to underlying genuine felt 
emotions. Implementing this proposal in a classroom would help the teacher to identify students 
who are undergoing mental distress and hence help them. This could reform the way in which 
student-teacher relationship pan out.
One prominent challenge we could face in this approach is when students try to fake their 
expressions. But studies have shown that, it is much easier to deduce emotions by observing the 
expressions of young children as compared to those of an adult. Hence the success rate of this 
approach would also be higher when applied to school children rather than adults.

Methodology: 
 The initial step would be to create a model for mapping facial expressions of emotions to 
underlying emotions. There are two methods for doing that. The first is to map facial expressions to 
7 basic emotions which includes anger, contempt, fear, disgust, sadness, happiness and surprise. The 
other would be to use a CNN model to create fake images of a single student and subsequently 
create a database of facial expressions of emotions of that particular student . This would require us 
to detect and generate facial geometries. Spatio-temporal analysis of these would help us map the 
expression to genuine felt emotions.
The next step is to obtain images for testing the model. Since discriminative facial responses are 
short and subtle the images must be captured in high-resolution an increased frame rate for 
behaviour to be distinguished easier. For this purpose we could use either high resolution 
surveillance cameras or set up cameras before the seating arrangements of students.
Next step is isolating faces and extracting features. This is done by feeding the images to CNN 
model which creates a feature space. We also have a database we created using facial geometries. 
While testing the model, we do spatio-temporal analysis. This maps very subtle facial expression 
changes to felt emotions by mapping the changes to feature clusters. 
The result of this classification model is a label that represents the identified emotion. The label 
represents one of the 7 basic emotions 
