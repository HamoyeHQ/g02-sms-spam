# SMS Spam Collection Dataset #

*Collection of SMS messages tagged as spam or legitimate*

**About**

This project aimed at building an SMS spam classifier that can be precise when differentiating spam from non spam Nigerian texts. The model was deployed on streamlit and hosted on heroku. Click [here](https://sms-pa.herokuapp.com/) to view the app, to check the authenticity of your SMS:


**Spam** refers to unsolicited messages sent out in bulk to recipients for the purpose of advertising, spreading malware, etc. Spam occurs through various mediums including SMS, emails, WhatsApp, and other text messaging platforms.

**Dataset**

The data used for this project can the found in the data folder. It was acquired from [kaggle](https://www.kaggle.com/uciml/sms-spam-collection-dataset) and has 5,574 SMS in English which were classified into ham (nonspam) and spam. However, since the application of this project is in Nigeria, we sourced for more data and got some local dataset from [Data Science Nigeria (DSN)](https://drive.google.com/drive/folders/1gividY9zzjjfaOLR8VOJT2JsZHiukFbB). They were 440 spam messages (comprising job and financial spam).

The files contained one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text. 

**Task**

To use the combined spam and Nigerian SMS datasets to build a prediction model that will accurately classify texts according to different categories of spam (Job interview spam, promo sales spam, grow finance spam) and nonspam messages.

**Citation**

- Data Science Nigeria (DSN), who worked on something more advanced [the Na-Lie App](https://www.datasciencenigeria.org/ai-commons-na-lie/)
