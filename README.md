# Restaurant-Review-EDA

## Problem Statement
Analyse the given data having user reviews and other information of restaurants. Perform an EDA to find out useful insights to improve overall restaurant experience in Bengaluru.


## Dataset Understanding and Cleaning
I took a note of the following observations:
1. Data Shape: There are 2069 rows and 15 columns, each representing a datapoint for restaurants in Bangalore.
2.Null values: Columns that have null values are:
● rate with 299 null values
● rest_type with 17 null values
● dish_liked with 1107 null values
3.Data types: Data types of all the columns.
While performing the EDA, I made two fo these columns type from object type to float type. These two columns are approx_cost(for two people) and rate
4. Duplicate entries: There were no duplicate rows
5. Unique restaurants: There are 1665 different types of restaurants


## Data Visualization
1.I looked at how the “cost for two people” contribute to the rating:
![Rest](https://user-images.githubusercontent.com/50451550/103549634-b19c3a00-4ecd-11eb-9497-d48afa5fef7a.png)
From the above plot, it is seen that restaurants in the cost range of 0 to 1200 have all
kinds of ratings.Restaurants in the cost range of 1500 and above do not have ratings
less than 3.7.

2.Number of restaurants with poor, average and excellent ratings (in percentage):
![2](https://user-images.githubusercontent.com/50451550/103549816-f7590280-4ecd-11eb-8b54-12056a11fbcc.png)
48% of restaurants have very good ratings (above 3.7) and only 6.7% have poor ratings. So it is very uncommon to get low ratings.

3.Number of restaurants in different locations:
![3](https://user-images.githubusercontent.com/50451550/103549896-16f02b00-4ece-11eb-83a0-728612a778f9.png)
BTM has the highest number of restaurants, followed by HSR, JP Nagar and Kormangala 5th Block.
Some of the least popular places for restaurants are Kanakapura Road, Rammurthy Nagar and Infantry Road.

4.Number of types of restaurants:
![4](https://user-images.githubusercontent.com/50451550/103549988-3dae6180-4ece-11eb-9492-fb3483db0fd6.png)
The most popular types of restaurants are Dineout and Delivery.

5.Number of restaurants offering online delivery:
![5](https://user-images.githubusercontent.com/50451550/103550060-56b71280-4ece-11eb-81aa-b9f9e41d56d8.png)
Ratings based on availability of delivery services:
![6](https://user-images.githubusercontent.com/50451550/103550145-7817fe80-4ece-11eb-80d5-dd1e410d212a.png)

6.Restaurants providing Table booking facility or not:
![7](https://user-images.githubusercontent.com/50451550/103550596-2623a880-4ecf-11eb-8e66-fd4821ca2cce.png)
Ratings based on the availability of table booking:
![8](https://user-images.githubusercontent.com/50451550/103550633-36d41e80-4ecf-11eb-887e-779c1a22679f.png)

7.Looing at delivery availability based on the type of restaurant:
![9](https://user-images.githubusercontent.com/50451550/103550639-39cf0f00-4ecf-11eb-96e0-9a464561c2c7.png)
A majority of delivery type of restaurants provide delivery services.

8.Ratings based on location of restaurant:
![10](https://user-images.githubusercontent.com/50451550/103550648-3c316900-4ecf-11eb-9fc6-68054b8f46ee.png)

9.Popular cuisines:
![11](https://user-images.githubusercontent.com/50451550/103550652-3e93c300-4ecf-11eb-8da4-09454d22d407.png)
The most popular cuisines appear to be pasta, pizza and cocktails. Whereas the least
popular cuisine type include brownie and mutton biryani.

10.Ratings based on location:
![12](https://user-images.githubusercontent.com/50451550/103550661-40f61d00-4ecf-11eb-8fdb-3ad943b90df9.png)


## Suggestions:

Following are some of my suggestions to the improve overall restaurant experience in
Bengaluru based on the EDA performed:
1. Cost does not matter much:  Ratings do not depend much on the average cost of
the dishes for two people. So restaurants should price their dishes fairly.
2. ”North Indian” cuisine is popular: Majority of restaurants are of “North Indian”
cuisine. Restaurants in this section would gain more popularity.
3. Popular places for business: New businesses should consider BTM, HSR, JP
Nagar and Kormangala 5th Block to open restaurants and avoid setting up new
restaurants at Kanakapura Road, Rammurthy Nagar and Infantry Road.
4. Make delivery services available:​ Delivery availability and ratings do not have a
direct relationship but restaurants offering delivery had ratings above 3.3. So
restaurants should make delivery options available.
5. Making table booking service available: Restaurants having table booking available
have much higher ratings compared to the ones that do not. So all restaurants must
have booking facilities available for a better rating/
6. Popular dishes: Most popular dishes in the city include Pasta, Pizza and Cocktails.
So it is advised that restaurants that do not fall under these categories of cuisines
should also serve these foods to get higher ratings. It is also important to note that
restaurants with cuisines brownies and mutton biryanis should be avoided as they are
the least popular.
7. Popular type of restaurants: Dineout and Delivery type of restaurants are the most
popular.Cafes, Desserts, Pubs and Bars and other categories should consider making
delivery options available to increase their ratings.
