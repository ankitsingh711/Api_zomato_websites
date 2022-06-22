Page No.1

#List of City
>https://ankit-zomato-data-data.herokuapp.com/location
>https://localhost:9700/location

#List of Restaurants 
>https://ankit-zomato-data-data.herokuapp.com/restaurants
>https://localhost:9700/restaurantsdata

#List of Restaurants wrt City
>https://ankit-zomato-data-data.herokuapp.com/restaurant?stateId=1
>http://localhost:9700/restaurants?state_id=4

#List of MealType
>https://ankit-zomato-data.herokuapp.com/quicksearch
>https://localhost:9700/mealtype



//Page No. 2
#List of Restaurants on the basis of meal
>https://ankit-zomato-data.herokuapp.com/restaurant?mealtype_id=
>

#Filter on basis of cuisine
>https://ankit-zomato-data.herokuapp.com/filter/4?cuisine=1

#Flter on basis of cost
>https://ankit-zomato-data.herokuapp.com/filter/1?hcost=1000&lcost=500

#Sort(Low to High)

//Page No.3
#Details of restaurants
>https://ankit-zomato-data.herokuapp.com/details/1
>https://ankit-zomato-data.herokuapp.com/618776b162a1816f885956bf

#Menu on basis of restaurants
>http://localhost:9700/menu?restId=8

//Page No.4
#Menu on basis of items selected(POST)> localhost:9700/menuItem (body)> [1,4,6]

Place Order (post) > localhost:9700/placeOrder (body) > { "name":"Aakash", "email":"aakash@gmail.com", "address":"Hno 23,Sector 1", "phone":97876733, "cost":431, "menuItem":[34,26,17], "status":"Pending" }

#Place Order

//Page 5
#See all order place
>localhost:9700/viewOrder Get Order on basis of emailId
>localhost:9700/viewOrder?email=aakash@gmail.com

//update order (put) localhost:9700/updateOrder/62514d42f5aec503b2e0f2a9 (body) { "status":"In Transit", "bankName":"Axis Bank" }

#Get order on basis of emailId
>

