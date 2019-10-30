# enron
Dataset used: Enron email dataset :https://www.cs.cmu.edu/~enron/ http://info.nuix.com/Enron.html

Given Description: Multi-folder structured dataset for 150 users. Each user directory consists of folders taken from its Email box containg folders like: inbox,sent,deletes,all_docs and several other user created folders. The corpus contains around 0.5 millions email messages.


Code files and description:
File 1: enron_emails_analysis.ipynb is used to explore various prelimnary analysis, corpus creation and social network/link analysis purpose. Corpus thus created is saved and is further utilized in next analysis tasks.

File 2: topic_analysis.ipynb is used for understanding underlying topics in text part of email corpus (created and saved in previous file). Used LDA model for exploring underlying topics in exisiting email messages. 


Analysis tasks -
1. Prelimnary data exploration
2. Selection of data for analysis, its structuring, including new columns
3. Data visualizations to see some direct patterns from data
4. Data Cleaning and compression: Duplicate email detection, Alias/Fake user identity identification
5. Email network graph creation - On sent emails: where nodes are unique users(aggregated different identities by a user) and an edge is communication made between two such users.
6. Network graph analysis and visualizations to analyze various communication links between users (employees and non-employees)
7. Topic Analysis from contents of emails

* Please refer to corresponding notebook files for more detailed technical explainations.

* "trained_models" folder contains trained lda models.
message_df_all.pkl consists of unique formatted emails in form of a dataframe.
