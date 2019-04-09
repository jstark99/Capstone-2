# Capstone-2
A first attempt at NLP with Twitter data

Question: Can we learn anything about company earnings announcements from the content of official company Twitter accounts?

This poses an interesting question because financial markets are so competitive and are generally considered to be efficient. If we are able to learn something about how the markets will react to an earnings announcement from how a company Tweets, we are able to gain an informational advantage. 

Data: This project combines Twitter data, stock level data, and earnings/analyst data. The Twitter data was obtained from the Twitter API by a co-author and contains millions of Tweets that come from official company Twitter accounts. Stock data is obtained from CRSP and provides information about the stock characteristics (size, shares outstanding, price, trading volume, and returns). The earnings data comes from IBES and provides the consensus earnings estimate and the reported quarterly earnings. Details of the data wrangling process are contained within my jupyter notebook.

Initial: Initial results show that we have over 40,000 financial tweets and over 2,000,000 general tweets. The sample covers approximately 1,000 unique companies and is from 2007 - 2014. 
