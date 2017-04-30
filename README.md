# 
## Pickle files:

https://transfer.sh/fF29A/review_cleaned_d.p
* The reviews that are less than 90 days before the last review date of each business are removed
* The cleaned reviews data are stored in a dictionary and dumped in review_cleaned_d.p
* Structure of the dictionary: {key:business_id, value: {key: Review Date, value: list of review text}}

https://transfer.sh/GDlPx/bus+review_df.p
* Joined the business and reviews data in dataframe and stored it in "bus+review_df.p"
* Method of reading the joined dataframe: major_df = pickle_load("data/bus+review_df.p")
* Column ['review_count'] is updated (we have removed the reviews which are less than 90 days before the last review date)
* Created the column of ['reviews'] which stores all the reviews of a given business_id. Reviews are separated with " "


-Dataframe of yelp businesses: {row:business_id, column: features}
