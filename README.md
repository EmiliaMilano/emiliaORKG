# emiliaORKG
screening-task-posting31

In order to create a research problem extraction system with the dataset provided in the NCG challenge I would use Sentence-BERT (Reimers and Gurevych, 2019). After installing it on the python environment, I would launch the Sentence-BERT transformer code with the available training set. As a further step, I would measure similarity of the three layers into which the set is divided, through cosine similarity. 

As a second part, I would apply the resulting model to the test dataset and then create a confusion matrix with the obtained results. From these data, I would measure precision, as to quantify the true positive predictions over the amount of all the positive predictions made, and recall, as to quantify the true positive predictions over the amount of all the positive instances in the test dataset. After obtaining these results, I would use them to compute the F1 measure, as the double product of precision and recall scores divided by the sum of precision and recall scores. 
