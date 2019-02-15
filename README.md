# Text-Modelling
Text Mining and Modelling using TF-IDF, Cosine and BM-25

Dataset chosen is from a collection of about 7,000 Yelp reviews from the Yelp Dataset Challenge. Each line corresponds to a review on a particular business. Each review has a unique "ID" and the text content is in the "review" field. I treat each review as a document. Given a query, you need to calculate its TF-IDF score in each review.

TF = number of times word occurs in a document

IDF = log(total number of documents / number of documents containing the word)

IDF has several formulations I have chosen the above for simplicity
