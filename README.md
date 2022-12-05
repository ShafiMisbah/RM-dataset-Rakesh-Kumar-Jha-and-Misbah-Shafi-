# RM-dataset-Rakesh-Kumar-Jha-and-Misbah-Shafi-
RM Dataset prepared by Dr. Rakesh Kumar Jha and Dr. Misbah Shafi.
It is a security based dataset that consists of the attributes defined for 5G and beyond 5G wireless communication network.
The dataset is meant for the categorization of the communication network on the basis of trust levels in order to enhance the security.


Breaches extend the pathway for attackers to target more users in the communication network. The designation 0 indicates that there is no breach history estimate for the user and 1 indicates that the user has a breach history. Therefore, the breach history with respect to the HD attack, bandwidth spoofing attack, UAV attack, and high-speed handover attacks are defined.


Solving time of captcha: It is defined as the total time spent by the user to successfully solve the captcha once in a particular time interval. It also includes the time spent by the user during its failed attempts if it occurred before the successful attempt. Captcha acts as an additional measure of security to detect bots, and spammers and prevents the insertion of malicious frivolous code. 


Successful Captcha Rate (SCR): It is defined as the ratio of the total number of successful captcha(s) submitted to the total number of captchas submitted.
OTP submission time: It is defined as the time taken by the user to submit an OTP successfully once.
Successful OTP Rate (SOR): It is estimated as the ratio of the total number of successful OTP attempts to the total number of OTP attempts.


Nature of signature: This attribute defines the extent of identity matching of a valid user. For simplicity, in our proposed RM dataset we have reduced the matching to 0 or 1. The 1 denoted that the identity is matched and 0 indicates that the identity is not matched.
Time complexity of attack:It is defined as the estimated computational complexity of an attacker to successfully attack a valid user. It depends on various parameters such as the nature of the attack, the signal strength of the user, and the complexity of the attack. 


Distance: Distance from the BS is considered to be an important parameter for signal strength and spoofing attacks.
Secrecy capacity: It is an important concern in the field of security. It estimates the secure transmission of the WCN. Using the wireless wiretap theory, it is defined as the difference between channel capacities of valid user and the intruder.



**Trust rank model estimation: **


The dataset is required to be prepared for the analysis, for that data preprocessing is performed.
Data preprocessing:It is defined as a technique of preparing the data that transforms the raw, disparate, and intricate data into organized, consistent and clean data.
Then the whole RM dataset is divided into testing dataset and training dataset.


preprocessing is followed by the training of the RM dataset.


Training : It is specified as the process of providing a learning algorithm with training data as the target attribute for learning purposes. The learning algorithm determines the pattern in the RM training dataset by incorporating the mapping of input data features to the target values such that the target output is obtained from the captured patterns. Based on the trained data the model attempts to predict new data input. 


To evalaute the performance of the prediction model, testing is performed on the RM dataset
Testing: The testing process determines the prediction performance of the fully trained model on the RM testing dataset. It involves explicit checks for the expected behavior patterns of the model, such that the nodes are distinguished based on the five trust ranks.
