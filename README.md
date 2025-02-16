# RestaurantDiscover

## Overview
A mock food app feature built in Kotlin involving retrieving API endpoint based on a set of coordinates. The product will cycle through 9 sets of coordinates and display up to 15 restaurants based on the location. Each restaurant will have its name, short description, an image and a favorite button. Users will be able to favorite the restaurant they want, and their liked restaurant will be saved when the app reopens. At the top there are three tabs: Discover, Favorite, and Search. The app starts with the Discover tab, and users can switch to Favorite to see all their favorited restaurants. Search tab hasn't been implemented.

This was a challenging but rewarding project. The Favorite tab feature was added later but the Discover Tab was completed within 14 days of me learning Kotlin.

## Example
<h4>App Feature Discover and Favorite</h4>
<img src="https://i.imgur.com/b3qzGPx.gif" width="250">
<h4>Screenshot Discover 1</h4>
<img src="asset/RestaurantDiscover1.png" width="200">
<h4>Screenshot Discover 2 with a favorite restaurant</h4>
<img src="asset/RestaurantDiscover2.png" width="200">
<h4>Screenshot Discover 3 Favorite Tab</h4>
<img src="asset/RestaurantDiscover3.png" width="200">

## Features
- Retrieving API endpoints with coordiantes
- Clean Architecture for scalablity
- Saving the state of Liked for each restaurant, pairing with its restaurant ID

## Architecture
- Codes were separated into three layers: Domain, Data, and Presentation.
- Domain: the layer that stores the data retrieved from API, this layer should be as isolated as possible, so if the database changed, the core logic stays the same
- Data: this is where the core logic and getting the data is placed
- Presentation: this layer just have the most basic set up of composables. It should be as simple as possible of taking the data from domain and put in the composable.

## Possible Updates
Things that I am looking to update this project with is the Search Tab and using my current location. 

## Note:
This project is an application task, so no codes are provided. 
