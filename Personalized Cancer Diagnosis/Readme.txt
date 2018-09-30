personalized-cancer-diagnosis problem statement

When a patient seems to have a cancer ,we take a cancer tumor from the patient and we go through genetic sequencing of DNA of tumor.Once sequenced ,a cancer tumor can have thousands of genetic mutations.Here briefly a ‘mutation’ is small change in gene which causes cancer.One more important thing is for every gene there is a variation associated with it.Now with the help of gene and variation we have to classify which class(total we have 9 classes) it belongs to.Only some classes belongs to cancer.

Let us go workflow more clearly.

Source:https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462

A molecular pathologist selects a list of genetic variations of interest that he/she want to analyze

The molecular pathologist searches for evidence in the medical literature that somehow are relevant to the genetic variations of interest

Finally this molecular pathologist spends a huge amount of time analyzing the evidence related to each of the variations to classify them.

Here going through 1 and 2 steps can be done easily and with less time.But Step 3 is very time consuming.Our goal is to replace Step 3 with machine learning model.

So,the problem statement is to classify genetic variations based on evidence from the text based clinical literature or research papers .

As we said to classify genetic variations which means it is a classification problem.As there are 9 classes it is a multi class classification problem

Knowing business constraints of the problem is most important .If we don’t know business constraints, we will train models which cannot be put in production.