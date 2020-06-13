# Restaurant Reviews
Restaurant Reviews was built in Node.js, Express and mongoose. Uses can search restaurants and check their detailed information. Administrators can add and modify the data of the restaurants with user authentication included.

## Requirements

+ Node.js v10.16.0
+ Express v4.17.1
+ Express-handlebars v3.1.0
+ method-override : v3.0.0
+ mongoose : v5.6.0

## Install
1. Download
```
$ git clone https://github.com/moonshade/restaurant_reviews.git
```
2. Install packages via npm 
```
$ npm install
```
3. Run the project
```
$ npm run dev
```
4. Hit the Restaurant Reviews website
```
http://localhost:3001
```

## Notes
+ Show the complete list of restaurants：http://localhost:3001
+ Show the details of a specific restaurant：http://localhost:3001/restaurants/:restaurant_id
+ Search restaurants：http://localhost:3001/search?keyword=yourkeyword
+ Add new restaurant
+ Modify restaurant data
