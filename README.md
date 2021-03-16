# Food-Discount-Scraper

### Data are scraped from mulitple post from Facebook pages, processed and cleaned using NLTK, spaCy and basic RegEx. Final data are used to train and fit into text classifier models.

#### Text data (facebook post) are cleaned through the following
- remove emojis
- remove website links
- remove all \n formatings
- remove all other non- alphanumeric data (excl. space)

#### Text data are processed through the following
- remove all stopwords
- snowballstem all words
- converted into and tfidf format

#### Text classifier is done using MulitnomialNB, Linear SVC and RandomForestClassif
- GridSearchCV to fit optimal param for tfidf, MulitnomialNB, Linear SVC and RandomForestClassif
