
## Airbnb Listings in Amsterdam Project 

**Project description:** Real Estate Investors are planning to purchase several rental properties in various citites arounf the world over the next few years. They want to list these rental properties on Airbnb and decided their first purchase will be in Amsterdam, Netherlands. Before they pursuit their purchase, they would like clear data about Airbnb property performance in Amsterdam. Their objective is to get information in respect to which location to buy and how much annual income they may be able to earn. I was provided with two datasets and their 

### 1. Suggest hypotheses about the causes of observed phenomena

The question that frames the objective is "Which  

```javascript
if (isAwesome){
  return true
}
```

### 2. Assess assumptions on which statistical inference will be based

```
SELECT listings.id, listings.listing_url, listings.availability_365, listings.room_type,listings.accommodates, listings.guests_included, listings.extra_people, listings.property_type,listings.bed_type, listings.neighbourhood, listings.city, listings.security_deposit, listings.price,listings.minimum_nights, listings.maximum_nights, listings.cleaning_fee, ratings.review_scores_rating, ratings.number_of_reviews,listings.reviews_per_month, (listings.reviews_per_month * 2)
AS bookings_per_month,
(CASE WHEN minimum_nights > 3.9 THEN minimum_nights
WHEN maximum_nights < 3.9 THEN maximum_nights
ELSE 3.9
END)
AS days_per_booking,
(CASE WHEN accommodates = 1 then 1
  WHEN accommodates >1 THEN 2
  ELSE 2
 END)
 AS guests_per_booking
FROM listings
LEFT JOIN ratings
ON listings.id = ratings.id
WHERE neighbourhood NOT LIKE 'Centrum-oost' AND neighbourhood NOT LIKE 'Centrum-West'
AND room_type = 'Entire home/apt'
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
