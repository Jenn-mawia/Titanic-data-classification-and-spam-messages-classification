# Titanic-data-classification-and-spam-messages-classification

## Contributors
Jenipher Mawia

## Description
This analysis contains two sections: 
- brief analysis that was done on The famous Titanic Shipwreck data 
- spam and non-spam messages classification

### 1. Titanic data classification
On April 15, 1912, the Belfast built RMS Titanic sank after colliding with an iceberg, killing over 1,500 passengers and crew on board out of the estimated 2227 people on board. Although Titanic had advanced safety features, such as watertight compartments and remotely activated watertight doors, it only carried enough lifeboats for 1,178 people—about half the number on board and many passengers died. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others. For instance, A disproportionate number of men were left aboard because of a "*women and children first*" protocol for loading lifeboats. The first-class accommodation was designed to be the pinnacle of comfort and luxury, with a gymnasium, swimming pool, libraries, high-class restaurants, and opulent cabins. 

It is for this reason that this project seeks to find “what sorts of people were more likely to survive?” using passenger data (i.e. in terms of age, gender, socio-economic class, etc)

The aim here was to classify/predict the survival rate of a passenger that onboard based on features such as Sex, Age, Number of family members aboard, the Passenger Class etc.
Modeling was done using the K-Nearest-neighbors classifier to classify passengers as either Survived or Did not survive. 


### 2. Spam messages detection
For this section, the main aim was to classify an e-mail as either spam or not spam. The data used was obtained from UCI Machine Learning website and had already undergoe through preprocessing states such as: tokenizing which includes stemming and Term Frequency Inverse Document Frequency, more known as tf-idf. Therefore, data cleaning and preprocessing needed to be done was very minimal.

With the improvement of technology, spam messages have also increased. Spam are irrelevant or unsolicited messages sent over the Internet, typically to a large number of users, for the purposes of advertising, phishing, spreading malware etc. It is therefore imperative to try and detect these messages as some of them are usually a way to lure victims into cyber crimes such as trojan horses that introduce viruses in a victim's machine without knowledge and hence backdoors, giving/submitting their personal and sensitive information to unsolicited users and sometimes even lead to masquerading. 

Modeling here was done using the Multinomial Naive Baye's Classifier to classify a message as either spam or not spam based on features that have been engineered into forms such as:

- whether a particular word or character was frequently occuring in the e-mail
- the sum of length of uninterrupted sequences of capital letters
- length of longest uninterrupted sequence of capital letters etc.



## Complete Setup / Installation Requirements
To open and view the notebook, you will need Jupyter Notebooks or Google Colaboratory. Do have a look at it.😊

## Technologies used
I used Python 3 in this project

## Contributing / Bug / Feature Request
Pull requests are welcome for contribution. For major changes, please open an issue first to discuss what you would like to change.

If you find a bug (or undesired results) do not hesitate to reach out


## License
[MIT](https://github.com/Jenn-mawia/Hypothyroidism-Classification/blob/main/LICENSE)


Copyright (c) [2020] 








