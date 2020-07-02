# The Battle of Neighborhood: Japan Hostels


## 1. Introduction
### 1.1 Background
As someone who loves travelling, finding ways to save money and travel low-cost is essential. There's little to save while booking flights and I'd rather pay more to traveling comfortably on a 16Hr flight than try to save and wear myself down even before the trip begins! But we can always save a few bucks on accomodation.

A hostel is a low-budget accommodation shared among travelers. Staying at hostels is an extremely affordable option for travelers. Not only that, It also gives you a chance to expereince which you would never at a hotel. I've found that experiencing hostel life one of the best ways to travel the world on a budget and here’s why:
1. You'll save a lot of money trust me.
2. Meet other like-minded travellers and make new friends around the world!
3. Most hostels organize lot of social activites
<br>
<br>

### 1.2 Business Understanding/Problem Description:
Hostel accomodation is a booming industry with the latest rise in tourism worldwide, especially in Asia. Over 20% of the total tourists worldwide are aged between 19-25. And around 80% of them prefer to spend less on accomodation by opting for hostels. This means the demand for hostels is only going to grow further and more people would want to get their legs in the game. 
- How should a new business person decide where to open a hostel?
- What factors should he look at before investing?
- Which neighborhood venues affect a user's rating for *location* of hostel?

At the same time, it is difficult for a travellers, especially first-timers, to select a hostel from among many options. Hostel reviews are subjective and differ from person-to-person and one cannot solely depend on them to make a decision. It is especially important to consider other aspects like price and neighborhood, which can greatly influence one's experience of the city/country.
I will try to answer the following questions 
- How does price vary with location?
- Where are the <i>'value of money'</i> hostels located?
- How does proximity to transportation affect hostel rating?
- Which hostels are most secure and where are they located?
- Suggest similar hostel but which cheaper price

Tourism in Japan in on a rise. It is expected that the number of foreign tourists coming to Japan will be increasing till 2020 when Olympic will be held in Tokyo. Hence, for this project, we will be looking at hostels in Japan, in particular, Tokyo.
<br>
<br>

### 1.3 Target Audience
This project will serve two groups of audience:
1. **Travellers:** Help them make an informed decision while choosing a hostel by providing an in-depth analysis of hostels and their neighborhood.
2. **Business Person:** Provide useful information and models which can help them where to open their first/next hostel.
<br>
<br>

## 2. Data Requirements
I analysed in this project : **Tokyo**.
Following are the datasets used in the project:

1. [Japan Hostel Dataset](https://www.kaggle.com/koki25ando/hostel-world-dataset)
2. [Hostel Neighborhood](https://developer.foursquare.com/docs/api)
3. [Tokyo Land Price](https://utinokati.com/en/details/land-market-value/area/Tokyo/)

#### 2.1 Japan Hostel Dataset:
The original dataset on kaggle has the following columns:
- hostel.name: Hostel Name
- City: City name where hostel is located in
- price.from: Minimum Price for 1 night stay
- Distance: Distance from city center (km)
- summary.score: Summary score of ratings
- rating.band: Rating band
- atmosphere: Rating score of atmosphere
- cleanliness: Rating score of cleanliness
- facilities: Rating score of falicities
- location: Rating score of location
- security: Rating score of security
- staff: Rating score of staff
- valueformoney: Rating score of value for money
- lon: Longitude
- lat: Latitude


Below is a snapshot of the dataset:<br>  
![Hostel Dataset](images/hostels_df.png)
<br>
<br>

#### 2.2 Hostel Neighborhood:
This dataset contains all the neighborhoods or venues within 500m radius of a Hostel. It has the following columns:
- HostelName: Name of the hostel
- VenueName: Name of the venue
- Category: It is the primary category of the venue, for eg. Café, Train Station, Restaurant.
- VenueLatitude, VenueLongitude: Coordinates of the venue.


Below is a snapshot of the dataset:<br>  
<img src="images/venues_df.png"  width="80%">
<br>
<br>


#### 2.3 Tokyo Land Price:
This dataset contains the locality name and the average price of land per square meter. Below is a snapshot:<br>  
<img src="images/tokyo.png"  width="25%">
<br>
<br>


## 3. Methodology:
