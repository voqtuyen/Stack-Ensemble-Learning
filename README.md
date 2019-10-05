# Stacked Ensemble Learning

### 1. How to combine classifiers
There are two approaches for combining models: voting and stacking
- In voting, label that is most often assigned to a particular instance is chosing as the correct prediction. Let's take a real life example of voting. 
  * In our day to day life, when crucial decisions are made in a meeting, a voting among the members present in the meeting is conducted when the opinions of the members conflict with each other. 
  * This principle of “voting” can be applied to machine learning also. In voting scheme, when classifiers are combined, the class assigned to a test instance will be the one suggested by most of the base level classifiers involved in the ensemble
- In stacking, a second-level learner or meta-learner is trained to combine the first-level learners.

### 2. Stacking framework

![Stacking framework](images/stacking-framework.png)






## Reference
[1] http://www2.islab.ntua.gr/attachments/article/86/Ensemble%20methods%20-%20Zhou.pdf
[2] https://www3.nd.edu/~rjohns15/cse40647.sp14/www/content/lectures/32%20-%20Stacking.pdf
[3] https://shodhganga.inflibnet.ac.in/bitstream/10603/7989/15/15_chapter%206.pdf
