## 1. Customer Feedback Sentiment Analyzer (n8n)

An automated system built with n8n to collect, analyze, and act on customer feedback using Google Sheets, OpenAI, and email notifications.

 - **Feedback Collection**: Customer reviews about the product details are collected and stored in a Google Sheet.

 - **Sentiment Analysis**: Each review is analyzed using an **Sentimental Analysis** Node using OpenAI model to determine if the sentiment is positive, negative, or neutral.

- **Sheet Update**: The sentiment result is appended to the corresponding row in the Google Sheet

- **Construct a Chart**: And construct a simple chart based on the sentiment result given by the model.

- **Admin Notification**: An email is sent to the admin with the review, sentiment classification, and summary.

![alt text](Images/sentimental.png)