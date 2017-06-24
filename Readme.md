# Exploratory Data Analysis of Enron Scandal

![alt text](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/Extras/Enron.jpg)


## What exactly the Data is?
### Enron Email Dataset
This dataset was collected and prepared by the CALO Project (A Cognitive Assistant that Learns and Organizes). It contains data from about 150 users, mostly senior management of Enron, organized into folders. The corpus contains a total of about 0.5M messages. This data was originally made public, and posted to the web, by the Federal Energy Regulatory Commission during its investigation.


## How can one obtain the Data?
One can download the dataset using the following link:

https://www.cs.cmu.edu/~./enron/enron_mail_20150507.tgz


## How is the Data stored?
CMU ENRON Dataset 1.82 GB of email data from all the employees of ENRON starting from December 1999 to November 2001. The dataset consists of 517,431 messages that belong to 150 users, mostly senior management of the Enron Corp, organized into folders. Although the dataset is huge, folders of particular users are often quite sparse.

The dataset here does not include attachments, and some messages have been deleted "as part of a redaction effort due to requests from affected employees". Invalid email addresses were converted to something of the form user@enron.com whenever possible (i.e., recipient is specified in some parse-able format like "Doe, John" or "Mary K. Smith") and to no_address@enron.com when no recipient was specified.


## Analysis:
We can see when the meeting emails were sent [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Distribution%20of%20meeting%20emails%20sent%20over%20time.csv)

We can see when the casual emails were sent [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Distribution%20of%20casual%20emails%20sent%20over%20time.csv)

We can see when the core emails were sent [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Distribution%20of%20core%20emails%20sent%20over%20time.csv)

We can see when the process related emails were sent [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Distribution%20of%20process%20emails%20sent%20over%20time.csv)

We can see list of emails Jeffrey Skilling interacted the most with [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Skilling%20interaction%20email%20frequency.csv)

## Conclusion:
From the outputs seen above we can understand number of meeting related emails, casual emails, process related emails and core business related emails and when they were sent. We can analyze that most of the enron emails consisted of Business Process. Casual meeting related emails were more than official meeting, which can be a result of fraudulent activities carried on within Enron. There were moderate number of core business related emails sent. If we observe carefully there is a huge spike in core business emails towards the end, maybe to hide their fraudulent activities. 

Also we have analyzed top 10 emails whom Jeffrey Skilling, the CEO of Enron, who was involved in the scandal interacted with. Further investigation can be carried out on these emails.
