# Algos_FinalProject
 For the final project, I looked into the Consumer Financial Protection Bureau’s consumer complaint data for 2020. I ran classifiers to examine whether the content of consumers’ complaints could predict the problem types they had. The dataset has more than 20 types of issues; I chose ‘Account status incorrect’ and ‘Investigation took more than 30 days’ for a balanced dataset. 

I used the Tfid Vectorizer to learn and count the frequency of words in the data frame ‘Consumer complaint narrative’ column to focus on unusual words. In doing so, I aimed to look for words that could distinguish complaints made regarding incorrect account status and a lengthy investigation.

The Random Forest Classifier showed a 100 percent accuracy rate. Linear SVC and Extra Trees Classifier had an accuracy of between 0.922 and 0.956, which I think performed well. The Extra Tree Classifier had a lower clf.score of 0.89. It predicted 12 times that the cases fell under ‘Investigations that took longer than 30 days’ when they belonged to ‘Accounts status incorrect,” according to the Extra Tree Classifier’s confusion matrix. All but the Random Forest Classifier tripped the most and classified ‘Accounts status incorrect’ as ‘Investigations that took longer than 30 days’. 

