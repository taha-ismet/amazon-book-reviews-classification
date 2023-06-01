# amazon-book-reviews-classification
In this project, I wanted to classify number of stars of reviews using text of the review. Reviews are scraped in every book category in www.amazon.com. Since
scraping with just one machine takes too much time, I have divided the task to 10 parts and used multiple Goggle Collab notebooks at the same time to scrape the data. I have stored the data in my Google Drive. With one gmail account, one can run at most 5 different Google Collab instances at the same time. So I ran the 5 notebooks twice. These notebooks are essentially copy of one other. Only difference between them is MACHINE_NUM parameter (Which have takes numbers 1-10 in different runtimes).
Here is one of these notebooks:
https://colab.research.google.com/drive/1j9kgs50EZqA2XLmdCoj9mBfy4elcSYgS?usp=sharing
Later used analysed this data and used several learning algorithms to classify reviews by the number of stars given it has, using the text
of the comments. Since the data was too little and number of stars given are so unbalanced, traditional
algorithms worked very little. So I have used a lot of dimensionality reduction algorithms to better the
results. Here is the notebook:
https://colab.research.google.com/drive/11pXAv8KyK5cLtdOKXaQ4Q6OE0R2A1sQl
