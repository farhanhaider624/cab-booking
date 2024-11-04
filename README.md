
# Cab Booking System
### Link: https://cab-booking2.onrender.com/
### CU x Scaler | SDE Internship Assignment | Md Mehran Akhtar | 20BCS7123 | mehran.akhtar88@gmail.com
## Authors

- [@Mehran Akhtar](https://www.github.com/mehran236)

This project is a cab booking web application built using React and Tailwind CSS. The aim of the project is to provide a platform for users to book a cab from a source location to a destination location while being able to select from a variety of cabs with different pricing options. The application calculates the shortest possible time and the estimated cost of the ride based on the cab selected and the distance between the source and destination. The web application also allows for the tracking of cab bookings, and users can view and edit the available cabs and their pricing. The application is designed to be responsive and user-friendly, making it easy for users to navigate and book their rides. The project has been developed with modularity and code quality in mind, ensuring that the application is easy to maintain and update in the future.

## Frontend
* React
* Java Script
* Tailwind

## Backend
* Mongo-Db
* Node.js
* Express.js

## Deployed On:
Render
## API Used
EmailJs -> For sending emails to users.

## Steps for Running on Local machine.
* In the app.js file change the **app.use(cors({ origin: 'https://cab-booking2.onrender.com' }));** to **app.use(cors({ origin: 'http://localhost:3000' }));**
* In every Frontend file change the link to **'http://localhost:5500'**
* Now write `npm start` in the terminal to start the frontend.
* Then `cd .\backend\`
* Then `node app.js` to start the Backend.
* Now you are ready to use the React app on the Localhost.

# Screenshots:
### 1. Home Page
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20015413.png?raw=true)

### 2. Search Cab
###### If user has choosen a particular Source then that choosen location will not visible in Destination.
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20015503.jpg?raw=true)

![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20015551.jpg?raw=true)

### 3. Available cabs
###### In this page User will be shown the source and destination point and the Ideal time that is the shortest distance between the two points.
###### Also 5 different cabs with different pricing and different arriving time will be shown.
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20015650.jpg?raw=true)

### 4. Book Now Button
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20015818.jpg?raw=true)

### 5. Confirmation Message
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20015858.jpg?raw=true)

### 6. Email
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20015957.jpg?raw=true)

### 7. Track Booking
All bookings from a particular email will be shown.
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20020225.jpg?raw=true)

### 8. Admin Dashboard
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20020314.jpg?raw=true)

### 9. Editing Cab-Details
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20020434.jpg?raw=true)

Following things are edited, shown below.
* Sedan Cab-> Sedan Cab-v1.0
* rate: ₹0.79-> ₹0.52
* Time to Arrive: 6->4

![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20020521.jpg?raw=true)

### 10. DataBase (MongoDb Atlas)
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20020716.jpg?raw=true)

### 11. E-Mail Service
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20020757.jpg?raw=true)

### 12. Deployment (Render)
![Home](https://github.com/mehran236/cab-booking-system/blob/master/Screenshots/Screenshot%202023-04-03%20020859.jpg?raw=true)
