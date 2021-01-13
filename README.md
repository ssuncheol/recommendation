# Recommendation

## Data Description
### 1) Amazon office
Amazon Review(Office) Dataset can be downloaded here<br>
[Amazon Office dataset(raw)](https://drive.google.com/drive/u/0/folders/1NMvsUaaSW9nxtMRnGcQw-8eNY1pjvAJY)

- ratings_Office_Products_5.csv (Rating data, userid::itemid::rating::timestamp)
- office_image.zip (Image of items)
- reviews_Office_Products_5.json.gz (Subset of the review data in which all users and item have at least 5 reviews)

### Sample review:
<pre>
<code> {
  "reviewerID": "A2SUAM1J3GNN3B",
  "asin": "0000013714",
  "reviewerName": "J. McDonald",
  "helpful": [2, 3],
  "reviewText": "I bought this for my husband who plays the piano.  He is having a wonderful time playing these old hymns.  The music  is at times hard to read because we think the book was published for singing from more than playing from.  Great purchase though!",
  "overall": 5.0,
  "summary": "Heavenly Highway Hymns",
  "unixReviewTime": 1252800000,
  "reviewTime": "09 13, 2009"
}
</code>
</pre>
where
* reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B
* asin - ID of the product, e.g. 0000013714
* reviewerName - name of the reviewer
* helpful - helpfulness rating of the review, e.g. 2/3
* reviewText - text of the review
* overall - rating of the product
* summary - summary of the review
* unixReviewTime - time of the review (unix time)
* reviewTime - time of the review (raw)
