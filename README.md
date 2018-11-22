# rideshare9

> rideshare9's webapp

## Browser Support
**Make sure adblockers are turned off**

**IE**: ?

**Safari**: Ok (with CORS enabled)

**FireFox**: Ok

**Chrome**: Not working (Fleet Overview excepted)

**Opera**: Ok

## Ranking Overview

This view shows the ranking of all Drivers and Passengers, based on how many trips they have involved in 
a specific time interval. The view also ranking of the most popular routes in this time interval, based on
how many advertisements have choose this route. 


## Fleet Overview 

This view shows the Active Trips (ones that have yet to be completed) along with all Drivers and Passengers. 

The Fleet Overview is divided into three columns: Trips, Drivers, and Passengers.
#### Trips
- List all currently active trips created on the RideShare App.
- Case-insensitive searching.
- Trip status filtering (All, Registering Passengers, Registration Complete, On Route).
- When a trip is clicked on, a panel displaying information on the trip becomes visible.
#### Drivers and Passengers
- Lists all currently active drivers and passengers signed up on the RideShare App.
- Case-insensitive searching.
- When a driver or passenger is clicked on, a panel displaying information on the trip becomes visible.

Information | Active Trips | Drivers | Passengers
------| ------ | ------ | ------ 
Title | Trip Title | Username | Username
Upon Click | Driver, Date and Time, Start Location, End Location, Seats Remaining, Status, Vehicle Information, Stops | Status | Status

Trip Statuses: All, Registering Passengers, Registration Complete, On Route

Driver and Passenger Statuses: On ride, standby

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
