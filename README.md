<<<<<<< HEAD
# Intelligent ChatBot for Better Hotel Experience

## Online URL: [Hotel Chatbot](http://hotel-agent.herokuapp.com)


## Basic Requirement
#### Local deployment only supported on Mac OS X, might not work for other operating systems.


## Installation
#### 1. Download the project
`git clone https://github.com/HotelChatbot/ChatBot_for_Hotel.git`
#### 2. Enter the project directory
`cd ChatBot_for_Hotel`
#### 3. Download all the dependencies
`npm i`
#### 4. Open another console to activate the database(if haven't)
`mongod`
#### 5. Go back to original console and load the datacase documents
```mongoimport -d hotel-chatbot -c restaurant --type csv --file public/restaurant.csv --headerline```

```mongoimport -d hotel-chatbot -c hotel_facility --type csv --file public/hotel_facility.csv --headerline```

```mongoimport -d hotel-chatbot -c room_facility --type csv --file public/room_facility.csv --headerline```

```mongoimport -d hotel-chatbot -c tourist_spot --type csv --file public/tourist_spot.csv --headerline```

## Activation
#### 1. Activate the database(if haven't)
`mongod`
#### 2. Open another console and start off the server
`npm start`
#### 3. Open a browser and visit the URL
`http://localhost:8080/`


## Simple tips for using
1. The **blue microphone button** at the left-bottom of your browser is clickable to enable/disable speech recognizer, please click to activate the button when speaking. Feel free to disable it when the chatbot is idle.
2. The **message textbox** at the left-middle of your browser allows text input to replace speaking if you like. It provides alternative availability for user who is under the circumstance that is not speak-convenient.
3. The **mode button** at the left-middle of your browser is for developer to test their server availability. Please be reminded that it is not for user intention.
=======
#Intelligent Hotel Assistant
##Introduction
This project aims to build an interactive chatbot specialized in hotel services, such as answering general question about the hotel services, searching and using the service of the restaurants nearby, to name but a few.
>>>>>>> 0b90449d3ef00a69cecc8ac675df243c23a6d8dd
