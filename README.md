# Books-rating-predictions
Nowadays with so many books available, it can be hard to select the best ones to read. The
dataset provided is a curation of [Goodreads Datasets] (https://www.goodreads.com/) books based on real user information. It can be
used for many tasks like predicting a book’s rating or recommending new books.
Below is the information you have regarding the dataset attributes:
	1) bookID: A unique identification number for each book.
	2) title: The name under which the book was published.
	3) authors: The names of the authors of the book. Multiple authors are delimited by “/”.
	4) average_rating: The average rating of the book received in total.
	5) isbn: Another unique number to identify the book, known as the International
	Standard Book Number.
	6) isbn13: A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.
	7) language_code: Indicates the primary language of the book. For instance, “eng” is
	standard for English.
	8) num_pages: The number of pages the book contains.
	9) ratings_count: The total number of ratings the book received.
	10) text_reviews_count: The total number of written text reviews the book received.
	11) publication_date: The date the book was published.
	12) publisher: The name of the book publisher.







Here are additional resources that may be helpful for the project. These resources are not
mandatory to use but are meant to give you ideas on enriching the data or analysing the
attributes in the dataset.
● Goodreads Datasets[Goodreads Datasets](https://www.google.com)
● Recommending Goodreads Books using Data Mining


![alt text](https://www.google.com/imgres?imgurl=https%3A%2F%2Flucidbooks.com%2Fwp-content%2Fuploads%2F2018%2F05%2Fgoodreads.jpg&imgrefurl=https%3A%2F%2Flucidbooks.com%2F8-ways-authors-can-use-goodreads-to-promote-their-books%2F&tbnid=bbjkFoESivqDRM&vet=12ahUKEwjcnOm93cv4AhXL44UKHRdnD-EQMygCegUIARCwAQ..i&docid=gGgADsDO64SqLM&w=580&h=388&q=goodreads%20&client=firefox-b-d&ved=2ahUKEwjcnOm93cv4AhXL44UKHRdnD-EQMygCegUIARCwAQ)

The results of our data exploration involving a thorough understanding of all the features of the dataset are summarized in the DataExploration.ipynb notebook.
 We have created three (3) models: 
-AdaBoost
-Linear Regression
-Ridge Regression 
and predicts the average score of test set cases using the same.
we answered some important business questions by further exploring the dataset and finding more insights.