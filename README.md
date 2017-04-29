# 
## Pickle files:

https://transfer.sh/fF29A/review_cleaned_d.p
* The reviews that are less than 90 days before the last review date of each business are removed
* The cleaned reviews data are stored in a dictionary and dumped in review_cleaned_d.p
* Structure of the dictionary: {key:business_id, value: {key: Review Date, value: list of review text}}



-Dataframe of yelp businesses: {row:business_id, column: features}
