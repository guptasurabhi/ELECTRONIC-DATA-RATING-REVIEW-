# ELECTRONIC-DATA-RATING-REVIEW-


Column Name	Description
id	A unique identifier for each product entry
brand	The brand name of the product
categories	The categories the product belongs to, often separated by commas
colors	The color(s) of the product, standardized to lowercase
dateAdded	The date the product was added to the dataset
dateUpdated	The most recent date the product information was updated
dimension	The dimensions of the product, filled with 'Unknown' if missing
manufacturer	The manufacturer of the product, filled with 'Unknown' if missing
manufacturerNumber	The manufacturer's unique number for the product
name	The name of the product
reviews.date	The date of the review, converted to datetime format
reviews.dateSeen	The date(s) the review was seen, could be multiple dates separated by commas
reviews.doRecommend	Whether the reviewer recommends the product ('True', 'False', or 'Unknown' for missing data)
reviews.numHelpful	The number of people who found the review helpful, with outliers removed
reviews.rating	The rating given by the reviewer, on a scale from 1 to 5
reviews.text	The text of the review
reviews.title	The title of the review
reviews.username	The username of the reviewer
sourceURLs	The URL(s) where the product information was sourced, could be multiple URLs separated by commas
upc	The Universal Product Code for the product
weight	The weight of the product, standardized to a string format

