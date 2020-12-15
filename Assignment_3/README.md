# Assignment-3

## Main Assignments:
1. Assignment_3a_Finetuning_with_simclrv2.ipynb

## Extra Credit Assignments:
1. ExtraCredit_Assignment_3_Part_A.ipynb
2. ExtraCredit_Assignment_3_Part_B.ipynb
3. ExtraCredit_Assignment_3_Part_D.ipynb



# Requirements
a) Use tensorflow hub model of simclr v2 and finetune and do supervised classification using simclrv2. Also compare the results with non simclr v2 method (regular resnet finetuning without simclr v2) 

Sample colab :  https://colab.sandbox.google.com/github/google-research/simclr/blob/master/colabs/finetuning.ipynb#scrollTo=BxhfMmVdHoZM (Links to an external site.)  (note : the actual colab starts at

"step : .....Load tensorflow datasets: we use tensorflow flower dataset as an example - rest all you can use as utility function)"

Expected amount of effort - 4 hours 

 

 

Optional assignments for people who want to learn tensorflow 2 more and implement code ------>


b) Optional : Advanced topic (extra credit - optional - not mandatory - only for people who have
some time to work on.) : semi supervised training with simclr -v2

implement simclr-v2 in tensorflow 2 from scratch (using utility functions) and show it performs well in small data set

(imagenet-5 categories)

Hint : use https://github.com/sayakpaul/SimCLR-in-TensorFlow-2 (Links to an external site.) as example

c) Optional : Advanced topic (extra credit - optional - not mandatory - only for people who have some free time to work on) - "supervised contrastive loss training"

 

Implement supervised contrastive training in tensorflow 2 using existing utility functions on three data sets
- flowers, imagenet and pets - showcase the clusters are formed of embedding properly

 

Hint : use :https://github.com/sayakpaul/Supervised-Contrastive-Learning-in-TensorFlow-2 (Links to an external site.) as example

 

c) Optional : Knowledge distillation with kera (knowledge distillation practice - student-teacher training)

Write a colab to do knowledge distillation in keras (student/teacher model) - Hint : https://github.com/sayakpaul/Knowledge-Distillation-in-Keras (Links to an external site.)

 

d) Optional : State of art semi supervised training using noisy student paper 
Write a colab for semi supervised training (using existing utility functions) main flow  Hint : https://github.com/google-research/noisystudent (Links to an external site.)

 
