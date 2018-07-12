# 100daysOfML

### Day 0: July 6, 2018

**Today's Progress:** Watched youtube video by Josh Gordon on how to build decision tree classifier from scratch.

**Summary:** In decision tree classifier you basically take all data with labels and put it in root node and ask question on it. Then based on true or false answer you split the data into two chunks which become next nodes of the tree. This goes on untill there is no further questions left to ask.
Note: This is perhaps the worst way to descript it. lol. I'll keep improving. 

**Link to work:** https://www.youtube.com/watch?v=LDRbO9a6XPU

### Day 1: July 7, 2018

**Today's Progress:** Studied the algorithm in detail and started writing the program in javascript

**Summary:** I have written function to find unique values from a column in dataset. Format of my data is different than that mentioned in tutorial so I will have to improvise for the new format. I am studying from here: https://github.com/random-forests/tutorials/blob/master/decision_tree.ipynb 

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch

### Day 2: July 8, 2018

**Today's Progress:** Studied the decision tree algorithm in details. Added function to get unique values from labels

**Summary:** I studied Gini impurity and information gain as well. It seems like I now understand these things in isolation but I need to study it more before I can see the big picture of this classifier and write all code out of my head. 

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/6ce7262582a22de56dd6fe016da485b6b2c64638

### Day 3: July 9, 2018

**Today's Progress:** Studied how array can be split by finding gini impurity and information gain.

**Summary:** Didn't commit anything to repo. Studied find_best_split() function from below link. I couldn't get the enough workable version to commit. 

**Link to work:** https://drive.google.com/file/d/1gURSnd1VjlaVnbh6rrObirnWlVplOnRZ/view?usp=sharing

### Day 4: July 10, 2018

**Today's Progress:** Worked on function to split data based on best information gain.

**Summary:** I had to watch the youtube video by Josh Gorden multiple times before I could understand what the code is doing :p. I feel like I am crawling but finally understood how this works. Added function to split data based on gini impurity and best information gain. The function is not complete yet. 

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/5a8e01dcf583c14d8e5c3580fb2c76efc547f187

### Day 5: July 11, 2018

**Today's Progress:** Updated function to split data and ask question.

**Summary:** We pick one value from a feature and apply for loop over it, then compare(ask question) it with every other value of the feature. Those which return true move to right branch. Others go to left branch. I have not tested the code yet. I feel like I am working much slower than expected. Need to speed up.

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/e3fbd5a8e37e70c345583b8188584ab5dcb60e0b

### Day 6: July 12, 2018

**Today's Progress:** Tested functions and fixed bugs.

**Summary:** I added index.html file so that I could debug functions. Now row splitting and gini impurity is working. It seems like keeping features and labels in separate arrays is not a good idea. I will keep it like that though.

**Link to work:** https://github.com/VariSingh/Decision-tree-classifier-from-scratch/commit/6191bc0c8de9be904a7bdb995bdc2f4fdfbd1801

