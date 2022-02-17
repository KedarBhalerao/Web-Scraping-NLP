# Web-Scraping-NLP

Instructions:
1.	 the input.xlsx file. The file contained two columns ie. URL_ID and URL. URL column was containing some URLs which I had to scrape.
2.	Only Title and the paragraph content was expected to be extracted from all URLs
3.	Decided to automate the scraping process of 170 URLs.For that Purpose I created a new csv containing only URLs from input.csv. Code for that will be in Converting to URLs.csv
4.  wrote the code to scrape the data and save it into a csv as I needed it for Text Analysis. 
5.	The code for that is written in Scrape to csv.ipynb and scraped the data to Cleaned.csv
6.	Then I started doing my Text Analysis and used Some NLP libraies like TextBlob , nltk , re along with pandas.
7.	For removing all the stopwords I used the stopwords.txt from this resource https://sraf.nd.edu/textual-analysis/resources/.
8.	I did Sentiment analysis with the help of positive_score,negative_score,polarity_score and subjectivity_score.
9.	Also did some Analysis of Readibilty like:
    Average Sentence Length, Percentage of Complex words,Fog Index,Average Number of Words Per Sentence,Complex word count,Word count,Syllable count per word,Personal                 Pronoun, Average Word length.
10. Final Output is Stored in TextAnalysisOutput.csv in the same format asked in Objective.


