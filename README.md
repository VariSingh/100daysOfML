# 100daysOfML

### Day 0: July 6, 2018

**Today's Progress:** Watched youtube video by Josh Gordon on how to build decision tree classifier from scratch.

**Thoughts:** In decision tree classifier you basically take all data with labels and put it in root node and ask question on it. Then based on true or false answer you split the data into two chunks which become next nodes of the tree. This goes on untill there is no further questions left to ask.
Note: This is perhaps the worst way to descript it. lol. I'll keep improving. 

**Link to work:** https://www.youtube.com/watch?v=LDRbO9a6XPU

### Day 1: July 7, 2018

**Today's Progress:** Studied the algorithm in detail and started writing the program in javascript

**Thoughts:** I have written function to find unique values from a column in dataset. Format of my data is different than that mentioned in tutorial so I will have to improvise for the new format. I am studying from here: https://github.com/random-forests/tutorials/blob/master/decision_tree.ipynb 

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch

### Day 2: July 8, 2018

**Today's Progress:** Studied the decision tree algorithm in details. Added function to get unique values from labels

**Thoughts:** I studied Gini impurity and information gain as well. It seems like I now understand these things in isolation but I need to study it more before I can see the big picture of this classifier and write all code out of my head. 

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/6ce7262582a22de56dd6fe016da485b6b2c64638

### Day 3: July 9, 2018

**Today's Progress:** Studied how array can be split by finding gini impurity and information gain.

**Thoughts:** Didn't commit anything to repo. Studied find_best_split() function from below link. I couldn't get the enough workable version to commit. 

**Link to work:** https://drive.google.com/file/d/1gURSnd1VjlaVnbh6rrObirnWlVplOnRZ/view?usp=sharing

### Day 4: July 10, 2018

**Today's Progress:** Worked on function to split data based on best information gain.

**Thoughts:** I had to watch the youtube video by Josh Gorden multiple times before I could understand what the code is doing :p. I feel like I am crawling but finally understood how this works. Added function to split data based on gini impurity and best information gain. The function is not complete yet. 

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/5a8e01dcf583c14d8e5c3580fb2c76efc547f187

### Day 5: July 11, 2018

**Today's Progress:** Updated function to split data and ask question.

**Thoughts:** We pick one value from a feature and apply for loop over it, then compare(ask question) it with every other value of the feature. Those which return true move to right branch. Others go to left branch. I have not tested the code yet. I feel like I am working much slower than expected. Need to speed up.

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/e3fbd5a8e37e70c345583b8188584ab5dcb60e0b

### Day 6: July 12, 2018

**Today's Progress:** Tested functions and fixed bugs.

**Thoughts:** I added index.html file so that I could debug functions. Now row splitting and gini impurity is working. It seems like keeping features and labels in separate arrays is not a good idea. I will keep it like that though.

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/6191bc0c8de9be904a7bdb995bdc2f4fdfbd1801

### Day 7: July 13, 2018

**Today's Progress:** Fixed bug in information gain, update in best_split function.

**Thoughts:** Not much to explain today. Just debugging and bug fixing. I feel like I am spending more time on coding aspects of ML and not really logic thing. Logic is something that goes more in head and less on keyboard. I will spend some time thinking about how to make this better.

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/453dfd3789abbffa5a5bacdefc8ad33aa4b1cdae

### Day 8: July 14, 2018

**Today's Progress:** Added recursive call to classifier function. Now tree is split on each node.

**Thoughts:** When I run function recursively it gives some weird looking response which apparently means I am doing something wrong. I will fix this in next commit.

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/c35eb726b44b3e9a8dd4e11e0f3c0db47e99b0d4

### Day 9: July 15, 2018

**Today's Progress:** Learnt about SVM(Support Vector Machine) from Udacity course "Intro to machine learning".

**Thoughts:** I have put decision tree classifier aside for some time because I felt like I am stuck with one algorithm only. I will come back to it later. So I read about SVMs, kernel trick, how to convert linear SVMs to linear. I have completed 22 chapters from the course on SVMs. Link at the bottom.

**Link to work:** https://in.udacity.com/course/intro-to-machine-learning--ud120-india

### Day 10: July 16, 2018

**Today's Progress:** Read about Naive Bayes Classifier from Udacity course "Intro to machine learning".

**Thoughts:** I couldn't understand most part of it. Even though I watched most of the videos, I seriously didn't get anything from the theory part (Bays Rule Diagram or Cancer test quiz). Really disappointed.

**Link to work:** https://in.udacity.com/course/intro-to-machine-learning--ud120-india

### Day 11: July 17, 2018

**Today's Progress:** Read about probability, Bayes Theorem.

**Thoughts:** I found out that I can't proceed with SVM's practical samples on Udacity because a part of it is in Naive Bayes lecture and I couldn't do that because I couldn't understand the theory part. So I jumped to very basics - probability theory. I am studying probability from Khan Academy.

**Link to work:** https://www.khanacademy.org/math/statistics-probability

### Day 12: July 18, 2018

**Today's Progress:** Probability continue.

**Thoughts:** Still reading probability from Khan Academy. Watched more lectures in order to understand it better.

**Link to work:** https://www.khanacademy.org/partner-content/wi-phi/wiphi-critical-thinking/wiphi-fundamentals/v/bayes-theorem

### Day 13: July 19, 2018

**Today's Progress:** Studied addition rule of probability, sets.

**Thoughts:** It seems like I'm back into school and studying things that I thought I would never study again but this is interesting. I need to study this anyway so that I understand fundamentals.

**Link to work:** https://www.khanacademy.org/math/statistics-probability/probability-library

### Day 14: July 20, 2018

**Today's Progress:** Studied multiplication rule for dependent and independent events.

**Thoughts:** Doing lot of theory. I have the urge to actually code but I won't really understand what I am doing untill I know how this stuff works. One aspect of that is probability. Udacity theory videos by Sebastian Thrun are really hard to understand until I know basics of probability.

**Link to work:** https://www.khanacademy.org/math/statistics-probability/probability-library

