# A-feature-selection-based-machine-learning-models-for-the-diagnosis-of-Autism-Spectrum-Disorder
Autism Spectrum Disorder, often known as ASD, is aneural and generative state that makes noticeable impact on how persons behave, interact, and connect with others.
Children with autism frequently exhibit symptoms before theage of three. Studies reveal that there is no one aetiology for autism, even though the root cause is
still unclear. Autism may be brought on by a genetic disorder as well as environmental elements like having elderly parents or being underweight at birth. People 
with ASD might have a range ofabilities. While some might not speak at all, others might have highly developed communication skills. While some people may need
assistance from others on a daily basis, some people can work and live on their own. “ASD affects 31% of kids intellectually (intelligence quotient [IQ] <70),
25% are borderline ([IQ] 71-85), and 44% have IQs that areordinary to above average ([IQ] >85)” [14]. Children with autism spectrum disorders may struggle with
basic social interactions. Some signs and symptoms include:
- Engaging and connecting with others seems challenging
* Having trouble making eye contact
+ Having difficulty in comprehending what other people are thinking or feeling
- Using a distinctive tone or rhythm when speaking
* Fails to responds to his or her name.
  
The goal of this project is to evaluate the performance of implementing backward feature selection-based ML algorithms such as “SVM”, “Random Forest”, “Logistic
Regression”, “Naive Bayes”, and “K- Nearest Neighbor” on two datasets such as child and adults each of which contains 21 features.Logistic Regression performs better
both before and after the use of feature selection.

The project consists of mainly three parts:
- Exploratory Data Analysis.
* Training Machine learning Models.
+ Feature Selection.

# The results of the asd screening for children.
Before implementing feature selection, various machine learning models on the dataset for diagnosing ASD children found accuracy ranging from (81.36% - 100%).
KNN produced the lowest accuracy, 81.36%, whereas random forest and logistic regression both produced 100% accuracy. The accuracy attained after feature selection 
and training ML models with these picked features is between (83.05% - 100%)

# The results of the asd screening for adults.
Before implementing feature selection, various machine learning models on the dataset for diagnosing ASD children found accuracy ranging from (79% - 100%). 
Random Forest produced the lowest accuracy, 79%, whereas Logistic Regression produced 100% accuracy. The accuracy attained after feature selection and 
training ML models with these picked features is between (97.87% - 100%).
