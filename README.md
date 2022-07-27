# Website-Behaviour-Anaysis
Problem: The client is an online ecommerce player. They have shared a user level log data for their browsing behavior (Timestamp, UserId and website section visited). You have been provided with the final conversion data too (Timestamp, UserID, Products Purchased in the transaction, Overall Cart Value).
Task: Based on this data you are required to build features and model on these characteristics of users to calculate a score/rank for conversion probability of that user. These scores will eventually decide the bidding logic used for each user. Your model will be evaluated on these criteria: - 
a.	Feature Engineering (Variable Imputation)
b.	Model Selection Criteria (Basis of choosing the final Technique)
c.	Measurement Criteria (Comparison of Various Models)
d.	Scope for improvement
Expected Outputs:-
1.	The Final code (Python or R) along with proper comments
2.	A summary file (PDF format) stating :
a.	Problem Statement
b.	Approach Taken
c.	Interpretation of Results
d.	Minimal but effective Storyboarding - Consider the final audience of this will be the Business team. You need to bring the actionable insights in this section.

How to Access the Data: Please use the below drive link to download the zip file. After Extracting, Kindly convert the file to Comma Separated File by renaming to (.csv) at the end.
https://drive.google.com/file/d/1TIAgMkjbyDzi3siVCVixIXPVyeyAsWyZ/view?usp=sharing
Hints:
1.)	Import the data in your System using the parameter delimiter='\t' in Pandas.
2.)	Mention the Column Name after importing the data i.e.  
['Timestamp', 'UserID','Website_section_visited']
3.)	Analyze the Data according to User and Make Probabilities as Total Product Purchased by Number of times visited.
4.)	Target Variable will be created by Product of Probabilities and Cart Value.
Evaluation: The project will be evaluated based on requirements and instructions provided above.

