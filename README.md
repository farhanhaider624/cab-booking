
# Cab Allocation System
### Link: https://cab-booking2.onrender.com/
### Moveinsync |  Assignment | Farhan Haider | IE2021020 | haiderfarhan671@gmail.com
## Authors

- [@Farhan Haider](https://www.github.com/farhanhaider624)

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
![Screenshot 2023-04-03 015413](https://github.com/user-attachments/assets/289b6720-e0cb-4061-9f28-a5e974224d90)

### 2. Search Cab
###### If user has choosen a particular Source then that choosen location will not visible in Destination.
![Screenshot 2023-04-03 015503](https://github.com/user-attachments/assets/056330a5-4c49-47f4-b4d8-859cf3588512)
![Screenshot 2023-04-03 015551](https://github.com/user-attachments/assets/755433d8-3924-40f5-84d6-6e28a83c628f)


### 3. Available cabs
###### In this page User will be shown the source and destination point and the Ideal time that is the shortest distance between the two points.
###### Also 5 different cabs with different pricing and different arriving time will be shown.
![Screenshot 2023-04-03 015650](https://github.com/user-attachments/assets/652ce7b4-2759-4ee9-b7b3-dcd737836dee)


### 4. Book Now Button
![Screenshot 2023-04-03 015818](https://github.com/user-attachments/assets/68d6cad7-6d0a-47cc-a222-329c97d52138)

### 5. Confirmation Message
![Screenshot 2023-04-03 015858](https://github.com/user-attachments/assets/ec1a65c8-5ac1-40df-8f19-3ef8384d5e57)



### 6. Track Booking
All bookings from a particular email will be shown.

### 8. Admin Dashboard
![Screenshot 2023-04-03 020314](https://github.com/user-attachments/assets/d310c28d-e965-4155-9949-f320045aa2df)


