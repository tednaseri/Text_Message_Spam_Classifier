# Text Message Spam Classifier
<p align="justify">Nowadays, spam detection is one of the major applications of Machine Learning. As an example, email service providers use this technique to detect spam emails (or junk emails) and prevent them to be accessed in male boxes. Like email services, we can use spam detection techniques for analyzing short message service (SMS) as well. Before getting into the project, let us first define what is a spam message. They are unwanted or unexpected messages that shown up on the user's cell phone. Normally, they are not only annoying but also can be dangerous too. For instance, they can contain some links that lead to phishing websites or similar websites that are hosting malware. Since the spam messages are sent from unknown phone numbers, they are trying to be more eye-catching than usual messages. For example, it is likely to have words such as win, chance, prize, and so on. To detect spam messages, we can take advantage of supervised machine learning algorithms if we have enough labeled records in a given dataset. <br>
In this project, I have designed and implemented a machine learning model that can efficiently predict if a text message is spam or not. Finally, this project is also implemented in form of a <strong>machine learning web application.</strong></p>

# Files and Folders in this Repository:
### Machine_Learning Folder:
There are three files inside this folder:
1) Utils_Spam_Classifier: This file includes common functions for tasks like data manipulation or data visualization. These functions will be called by two other files.
2) Preprocess_EDA_Spam_Classifier: This file including all the preprocessing steps and explanatory data analysis on the dataset. It also prepares the dataset for machine learning.
3) Modeling_Spam_Classifier: This file applies machine learning modeling to the dataset.

### Web Folder:
The contents of this folder are for machine learning web application. Inside this folder, we have one file and two other folders. 
1) Flask_Web_Application: This file includes python codes for a web application. 
2) Static/css/style.ss: This file includes a CSS file for the interface of the website.
3) templates folder: Inside this folder, there are 4 HTML files for the web pages.

### Model Folder:
The optimized model is saved in this folder.

### Data Folder:
There are three datasets in this folder:
1) SMSSpamCollection: It is the original dataset that can be download from the UCI GitHub repository.
2) df_new: It is one of the modified versions of the dataset that I made.
3) df_source: It is one of the modified versions of the dataset that I made.

# More Details:
<p>More details is provided in my personal website at https://www.tednaseri.com/spam_classifier</p>
