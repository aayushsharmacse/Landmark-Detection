#Landmark Detection
(The data source is private)
##Abstract
I tried to use two types of models and tried tuning them for different parameters. First one was a simple one, sequential model and second I tried transferring the knowledge of first second layers together with ongoing layers to last layer, i.e with functional api in tensorflow.

I tried functional api model since I thought that the model might benefit from refreshing of memory.

##Data Analysis/Preprocessing
The analysis necessary was that some images were of different sizes so they needed to be resized.

##Model Architecture
Functional API keras + ANNs did the job.

##Exprimental setting
I used kaggle as a platform (private mode not made the data public) which helped me by providing free gpu computation.

##Key findings
Memory refreshing indeed helps.

##Future works
In future data augmentation could be tried and hyperparameters can be tuned.
