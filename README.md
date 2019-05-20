# Property Buddy

![alt text](frontend-screenshot.png?raw=true "frontend empty")

Welcome to my hobby project that I made to showcase some of the technologies I learned in Codecool, as well as some new ones.

Are you looking to buy property in Budapest? This app is for you. You can follow the price changes on the various properties. Data is gotten from another website that specializes in renting and selling property in the city. I use webscraping to save the property information and periodically add the price data.

The end goal is to implement some sort of predictive analytics to answer questions like what is the overall trend in prices, or which disctrict would be the most lucrative for a real estate investment. I'm still learning most of the advanced math that I want to use, like autoregressive models and heteroskedasticity.

The project includes 3 services at the moment:
<h2>1. Database</h2>
  https://propertybuddy-database.herokuapp.com/swagger-ui.html#/

  This service connects to a heroku postgresql database, and can do CRUD operations using the API endpoints

<h2>2. Webscraping</h2>
  https://github.com/zapathy/webscraping

  This service downloads data from an external website that deals with real estate sales, and sends it to the database service

<h2>3. Frontend</h2>
  https://github.com/zapathy/propertybuddy_frontend

  This is a simple frontend to show the data in the database
