# MIT-futuremakers
day 1 - i learned how to put together my github account. i also downloaded jupyter notebook, the lab, python and experimented with different libraries. i really enjoyed the introduction session that occured at the beginning of the day. 


day 2 - i learned how to put together an interesting story and capture attention of my listeners. i later watched another video that showed similar techniques and backed up the information i learned the day. 


day 3 - i learned the different structure of AI and all the subsections.
i.  what is the difference between supervised and unsupervised learning?
- supervised learning uses labeled data to train algorithims into classifying data and predict outcomes. under supervised learning there is classication(algorithim to accurately assgin test data into specific categories; decision trees and linear classifiers) and regression(uses an algorithim to unferstand the relationship between dependent and independent variables; predict numerical values (linear regression, logistic regression) 
- unsupervised learning uses machine learning algorithims to analyze and cluster unlabeled data sets. they discover hidden patterns in data without the need for human intervention. under unsupervised learning there is clustering(data mining technique that groups based on their similarities or differences) association(uses different rules to find relationships between variables in given dataset) dimensionality reduction (number of features in a given dataset is too high)
- in supervised learning the algorithim learns from the training dataset while unsupervised learns from random collected data
ii. describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries
- scikit learn is a library of algorithims, it is built based of a few math python libraries which allows it to have so many abilities. without mini data anlysis libraries it is unable to perform those actions

day 4 - today we learned about different datasets that are available for solving differing issues. 
- the dataset that i found was a collection of data from the national hurricane center and central pacific hurricane center. i collected this data so that i could solve the issue of predicting tropical storms and hurricanes. by training systems to recognize patterns prior to the occurence of a storm https://www.nhc.noaa.gov/data/
- the algorithim for predicting these patterns should not be overly complex because the resulting hurricane always remains the same. what should be changing are the factors that go into their creation, wind, humidity, and other weather factors. 
- an additonal algorithim can be developed into predicting how intense the hurricane will be. 


day 7 - 
what are tensors and and what are they used for in machine learning? 
a tensor is a mathematical representation of a physical entity that may be characterized by magnitude and multiple directons. it is represented by a R number in a particular dimensional space. in a N dimensional space scalars will be  represented with 1 number, vectors need N numbers and tensors need N^R. a vector is a one-dimensional or first order tensor and a matrix is a two-dimensional or second order tensor. in the machine learning world tensors allow the design of 3 dimensional shapes
what did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial?
when i ran the first set of code the values did not actually get multiplied out because the tensorflow was lazy in the not interactive environment. i also ran this code through an editor (atom) and then opened it through my terminal, where the values were actually calculated. 

day 8 and 9  - today i learned about the structure of neural networks and how they are built. the session was long, but I learned more by rewatching the sessions. i also took time to explore the kaggle website and look at the code that different people published. it was in great detail with commentary and explanations 

day 10 - 
How do you think Machine Learning or AI concepts were utilized in the design of this game?
In this game the creators utilized the skillsets that recruiters would need to look for when hiring employees. Using these skillsets the AI began to recognize the pattern of what was looked for when hiring workers. The orange workers were also the ones with the best assets. The best workers would go to the front of the line because AI learned thats where I would look first. 
Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model.
An example of a biased machine learning model could be one that predicts test scores from different places around NYC. Because of outside factors like family situation and poverty level students are capable of attending school at differnt amounts. Usually environments with lower class families require students to work more and study less often. However, just because a student is from a certain place does not mean they could easily be an outlier. The model would be predicting straight off the bat that those students would be doing worse 
extra : by collecting more data on faces systems can become better at recognizing them and classifying them. with less data the results are less accurate and potentially more bias. in order to avoid big implications the systems should not be used in crime until it is more accurate

day 11:
Succinctly list the differences between a Convolutional Neural Network and a Fully Connected Neural Network.
the convolutional layer has the main portion of the network's computational load 
in a fully connected network all the nuerons are in connection with each other, in convolutional each neuron is only connected to a few nearby ones.  
a convolutional layer is much more specialized and efficient since every neuron carries the same weight.since there are less connections this makes these layers cheaper in terms of memroy and computed power
convulational layers are typically used for images, use of local connection
a fully connected layer ismore expensive because of an increase in weights and connections

day 12 + 13 (weekend) - caught up on some work and attempted to edit the code that was not working 

day 14 - today we spent some time learning about loss functions, i enjoyed learning how the algorithims are checked so that they are actually deemed effective. how much time or data can be lost before it is considered not effective?

day 15- the rectified linear function allows...
- computational simplicity - trivial to implement, requiring only a max() function. there is no need for exponential computation so it is cheaper
- can output a true zero value - this allows hidden layers to store one or more true zero values, it can accelerate learning and simplify the model
- linear behavior - the neural network is easier to optimize, there is no issue of vanishing gradients as they remain proportional to the node activation 
- deep networks - does not require unsupervised pre training to make accurate predictions.
- it is used so that not all neurons are activated at the same time. this can be used with face recognition as if the value inputed is negative(incorrect) the 0 is automatically returned.

day 16 - ethics in AI - today I learned of the importance of maintaining ethical behavior when creating technology that judges and characterizes people. the data that the models are trained on may include biased labeling and exclusion which is why all research should be fully disclosed. 

day 17 - today we worked on image classification. the class image pre-processing was the biggest step in the cycle, then came detection, feature extraction and training, and classification of an object. 

day 18 - today we learned about the different aspects of regularization.  overfitting is when the algorithim is overtrained with a very slim error. underfiting is when the algorithim is undertraind with a high error percentage. We can use L1, L2, drop out and early stopping

day 21 - today i learned about autoencoders which is a neural network that learns data in an unsupervisd mannner. i learned that autoencoders have the ability to reconstruct data if they have learned the features that came from the input data. even with blurry images this method learns to differentiate them.

day 22 - affective computing - today we learned about the kind of AI that is trained to recognize human emotions. this type of training requires huge amounts of data because every face expresses a particular emotion differently. these models are not yet extremely accurate

day 23 - today we learned about natural language processing which combines language and technology together. however with the somewhat mystery code surrounding this it is hard to tell if bias exists

day 24 - computer vision: i found it really interesting to learn the differences between how I view an image vs the computer that is displaying it.




