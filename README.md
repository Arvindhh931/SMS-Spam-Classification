# SMS-Spam-Classification

This dataset was taken from the StatLib library which is maintained at Carnegie Mellon University. The dataset was used in the 1983 American Statistical Association Exposition.

link - [SPAM data (UCI machine learning repository)](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

<iframe src="https://giphy.com/embed/xUOwGhauv1d6nceRbi" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/iphone-mail-youve-got-xUOwGhauv1d6nceRbi">via GIPHY</a></p>

## Data Set Information:
This corpus has been collected from free or free for research sources at the Internet:

A collection of 425 SMS spam messages was manually extracted from the Grumbletext Web site. This is a UK forum in which cell phone users make public claims about SMS spam messages, most of them without reporting the very spam message received. The identification of the text of spam messages in the claims is a very hard and time-consuming task, and it involved carefully scanning hundreds of web pages.
A subset of 3,375 SMS randomly chosen ham messages of the NUS SMS Corpus (NSC), which is a dataset of about 10,000 legitimate messages collected for research at the Department of Computer Science at the National University of Singapore. The messages largely originate from Singaporeans and mostly from students attending the University. These messages were collected from volunteers who were made aware that their contributions were going to be made publicly available.
A list of 450 SMS ham messages collected from Caroline Tag's PhD Thesis
Finally, incorporation of the SMS Spam Corpus. It has 1,002 SMS ham messages and 322 spam messages and it is public available at. This corpus has been used in the academic researches:

| Class        |    count      | percentage |    
| ----------------- | ------------- | ---------- |
| Spam | 747 | 13.41 % |  
| Ham | 4825 | 86.59 % |

## Objective:
Prediction of a SMS into SPAM or NOT A SPAM so that developers come up with the application that can filter messages them based on the prediction

## Limitations:
1) The semantics(exact meanings/context) of words are not taken into account
2) Sometimes/Rarely Model may end up predicting an important message as spam (False positives) 
     when out of the vocabulary word will be encountered.
3) Model needs to be continuously updated to escape out of the bag words, 
4) Model should incorporate the new slangs, spamwords in the emerging social media. 
