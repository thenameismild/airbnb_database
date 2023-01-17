# Creating Airbnb Database

### Business Problem

Airbnb is a community-based, two-sided online marketplace that facilitates and connects people who want to rent out their home with people who are looking for lodging in a specific location around the world. On the Airbnb platform, there are 2.9 million hosts worldwide and more than 7 million listings in over 200 countries, with more than 150 million users. This means that their biggest assets are the individuals and the hosts, where their revenue is from:
- Commission host: Everytime guest makes payment, Airbnb takes 10% of the payment amount as commission. 
- Guest Transaction fee: When travelers make payments for stays, they are charged a 3% fee for the transaction.

Knowing Airbnb's business model and revenue stream, we know that Airbnb has to focus on their guests and hosts. We are able to come up with important query questions that we believe would be beneficial for Airbnb’s:
- What are the characteristics that are popular in each state/region?
- What are the popular listings in different location/region?
- How does pricing differ by region?
- What is the availability by region?
- How long is the booking time by region?
- Why do some properties get very few reviews?
- How do prices vary over time by region?
- How does the number of listings vary for each region over time?

### Database and Technologies

We are using Airbnb’s data from the listings in the United States. The data came from Airbnb and posted through Kaggle, with the size of 8.49 GB. The dataset is separated by the state and city the listing is located in. In each city the data is broken down into 4 tables for listing, calendar, reviews and neigbourhoods. We are planning to use mySQL to create a database using the STAR schema.

### Application

Through understanding Airbnb business model, revenue stream and the data collected we will be able to help Airbnb determine how to generate more revenue through advertising popular listings and targeting guests in different areas. By using the queries that we created we will be able to gain insights into pricing, listing popularity, availability, and location-specific details for Airbnb to use to maximize their business reach.

