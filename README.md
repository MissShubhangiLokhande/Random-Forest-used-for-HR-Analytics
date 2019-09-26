# Random-Forest-used-for-HR-Analytics

Random forest is a collection of decision trees. It uses decision trees as it’s the basic building block. 

In a random forest multiple decision trees are created, each decision tree receives some random subset of features and data. For example, 1 tree will get age and location variables and another tree might get age and gender variables.

If there are n trees then n subsets of variables are created. These subsets may or may not overlap which means that some data can be common in 2 or more subsets. Each tree receives a different subset of data.

With these random subsets of features and data, they predict an outcome. In the case of a classification problem, a majority vote is done to predict the final outcome. For example, if the outcome of 6 out of 10 decision tree is that the candidate will renege, then that is the final decision. In the case of a regression problem mean of all the outcomes is taken as the final result.

Let me help you by giving an example, suppose you want to buy a house, you approach a person and ask him whether the locality is good or not. Based solely on his answer would you decide to take such a big step? You most likely won’t. You would take suggestions from a lot of people by asking different questions to a different set of people. After evaluating all the suggestions you would take an informed and better decision. Random forest works exactly like this.

We have n decision trees. This means we have n number of predictions. The final prediction is calculated by taking a majority vote. Let’s say the majority vote comes out to be that the candidate will renege, then that is the final prediction.

You may ask why precisely is random forest superior to a solitary decision tree? 

Answer is :

 By pooling predictions, we can consolidate substantially more learning than from any one tree. 
Extreme predictions cancel each other out and we get an efficient prediction.
