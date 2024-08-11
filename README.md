# Project Airbnb Rio - Price Prediction/Pricing Tool for Private Property Owners

<h5 style="color: red">Dataset in the repository contains only 1000 rows</h5>

### Context

On Airbnb, anyone with a room or property of any kind (apartment, house, chalet, inn, etc.) can offer it for rent on a nightly basis.

You create your host profile (person who makes a property available for nightly rental) and create the listing for your property.

In this listing, the host must describe the property's features as thoroughly as possible to help renters/travelers choose the best property for them (and make your listing more attractive).

There are dozens of possible customizations for your listing, from minimum stay duration, price, number of rooms, to cancellation policies, extra guest fees, requirement for renter identity verification, etc.

### Our Goal

To build a price prediction model that allows an ordinary person who owns a property to know how much to charge per night.

Additionally, for the regular renter, given the property they are looking at, help them determine if the property is priced attractively (below the average for properties with similar features) or not.

### Available Data, Inspirations, and Credits

The datasets were sourced from Kaggle: [Airbnb Rio de Janeiro Dataset](https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro).

They are available for download below the lesson (if you pull the data directly from Kaggle, you may get different results from mine, as the datasets may have been updated).

If you're looking for another solution, we can refer to the solution by Kaggle user Allan Bruno in the notebook: [Helping Regular People Price Listings on Airbnb](https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb).

You’ll notice similarities between the solution we’ll develop here and his, but also some significant differences in the project construction process.

- The datasets contain property prices and their respective features for each month.
- Prices are given in Brazilian Reais (R$).
- We have datasets from April 2018 to May 2020, except for June 2018, which has no data available.

### Initial Expectations

- I believe seasonality might be an important factor, as months like December tend to be quite expensive in Rio de Janeiro.
- The property’s location should significantly impact the price since, in Rio de Janeiro, the location can completely change the area's characteristics (safety, natural beauty, tourist attractions).
- Amenities/Extras might have a significant impact, as there are many old buildings and houses in Rio de Janeiro.

Let’s discover how much these factors impact pricing and whether there are other, less intuitive factors that are extremely important.

### Deployment with Streamlit

- The user fills in the characteristics of the property located in Rio de Janeiro/RJ.

![image](https://user-images.githubusercontent.com/65472072/146680760-1048eedf-ab62-4de1-9b3d-b83f75bc884a.png)
![image](https://user-images.githubusercontent.com/65472072/146680779-a36ec810-e9ea-44d5-8bed-cf6efe55b1f5.png)
![image](https://user-images.githubusercontent.com/65472072/146680797-af018da2-58da-4d0d-a2f5-1b1006abbe94.png)

#### Libraries Used

- All libraries used in the project are listed below.

1. pandas -> Dataframes
2. pathlib -> Local directory management
3. numpy -> Numerical operations and calculations
4. seaborn -> Data visualization
5. matplotlib -> Data visualization
6. plotly -> Interactive visualizations
7. sklearn -> Machine Learning
8. streamlit -> User deployment
9. joblib -> Model serialization for deployment

For access to the dataset used or for any questions, please contact me at carvalhodouglaspereira@gmail.com.
