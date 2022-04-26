# Text-Analytics-on-Van-Gogh-Letters
NLP project to carry out Text Analytics on Vincent van Gogh letters data; which is collection of letters written by Vincent Van Gogh primarily to his brother Theo.
# Dataset
There is no readily available dataset for Van Gogh letters.
## Dataset creation
To overcome the lack of dataset, I have created the dataset from scratch by scraping the required dataset from the official website of Vincent van Gogh Letters [1] using web scraping techniques in Python. HTML session is created and a connection is established with the website using the HTMLSession package and required data is extracted by querying underlying HTML DOM elements.
The final dataset created is save to csv: **van_gogh_letters_data.csv**
