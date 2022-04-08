# Vertical-Search-Engine-Development
This Vertical Search Engine is similar to Google scholar but it only retrieves papers/books published by a member of Coventry University.

The search engine receives a search query and publication metadata obtained by a bespoke web crawler, designed to scrape information about certain fields of each Coventry University staff members’ publications. The search engine converts the search query to tokens of words, creates a list of indexes for each word, and then uses the indexes to return publications based on the number of times the tokens appear in the publication text.
