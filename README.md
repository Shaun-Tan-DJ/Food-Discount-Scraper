# Food-Discount-Scraper

Data are scraped from mulitple post from Facebook pages, processed and cleaned using NLTK, spaCy and basic RegEx
Text data (facebook post) are cleaned through the following
# - remove emojis
# - remove website links
# - remove all \n formatings
# - remove all other non- alphanumeric data (excl. space)

# Text data is processed through the following
# - Remove all stopwords
# - snowballstem all words
# - converted into n-gram and tfidf format

# Text classifier is done using MulitnomialNB, Linear SVC and RandomForestClassif
