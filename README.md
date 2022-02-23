# Final_Project_7

## Selected Topic
We were hired by Mexicana Aviacion to implement a machine learning model in order to help them predict whether people purchesing tickets will become loyal customers or not. The purpose of this analysis is to help them better allocate resources into rewards programs dedicated to loyal customers, over those who are disloyal to the brand.

## Reason why they selected their topic 
We selected this topic because we are frequent flyers and traveling is a common interest between all team members. We believe there are many interesting insights that can be made from analysing this topic, especially in current COVID-19 times. 

## Description of their source of data 
We obtained data from kaggle.com (https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction?select=test.csv). This data set contains an airline passenger satisfaction survey with columns such as Age, Gender, Type of Travel, among many others.

## Questions they hope to answer with
We hope to answer the question "Can we predict the type of customer (loyal vs disloyal) a ticket purchaser will become? What factors are highly correlated to the decision to become a loyal customer?

## Description of the communication protocols
We plan to maintain open communication and active listening to prevent minor conflicts from being blown out of proportion. We will also meet after every class for 1 hour, as well as extra time on Saturdays or Sundays (depending on every member's availability). Lastly, our main tools for communication are Slack and Google Meet.

### Team Roles
- Square (Repository) = Ruth
- Circle (Data base) = David 
- Triangle (Machine Learning) = Jesus  
- X (Technologies for each step) = Grisell


### Database
The dataset contains an airline passenger satisfaction survey, the factors that lead the customer satisfaction for an Airline. The dataset contains 25,976 rows for the test and 103,904 rows for training.

| Column | Data Type | Description |
| ------------- | ------------- |  ------------- |
| **Gender** | VARCHAR(6) | Gender of the passengers (Female/Male)  |
| **Customer_Type** | VARCHAR(32)  | The customer type (Loyal customer/Disloyal customer)  |
| **Age** | INT | The actual age of the passengers |
| **Type_Travel** | VARCHAR(32) | Purpose of the flight of the passengers (Personal Travel/Business Travel) |
| **Class** | VARCHAR(16) | Travel class in the plane of the passengers (Business/Eco/Eco Plus) |
| **Flight_distance** | INT | The flight distance of this journey |
<<<<<<< HEAD
=======
| **Inflight_WiFi_service** | SMALLINT | Satisfaction level of the inflight WiFi service (0:Not Applicable; 1-5) |
| **Departure/Arrival_time** | SMALLINT | Satisfaction level of Departure/Arrival time convenient (1-5) |
| **Ease_Online_booking** | SMALLINT | Satisfaction level of online booking (1-5) |
| **Gate_location** | SMALLINT | Satisfaction level of Gate location (1-5) |
| **Food_and_drink** | SMALLINT | Satisfaction level of Food and drink (1-5) |
| **Online_boarding** | SMALLINT | Satisfaction level of online boarding (1-5) |
| **Seat_comfort** | SMALLINT | Satisfaction level of Seat comfort (1-5) |
| **Inflight_entertainment** | SMALLINT | Satisfaction level of inflight entertainment (1-5) |
| **On_board_service** | SMALLINT | Satisfaction level of On-board service (1-5) |
| **Leg_room_service** | SMALLINT | Satisfaction level of Leg room service (1-5) |
| **Baggage_handling** | SMALLINT | Satisfaction level of baggage handling (1-5) |
| **Check_in_service** | SMALLINT | Satisfaction level of Check-in service (1-5) |
| **Inflight_service** | SMALLINT | Satisfaction level of inflight service (1-5) |
| **Cleanliness** | SMALLINT | Satisfaction level of Cleanliness (1-5) |
| **Departure_Delay** | SMALLINT | Minutes delayed when departure (1-5) |
| **Arrival_Delay** | SMALLINT | Minutes delayed when Arrival (1-5) |
| **Satisfaction** | BOOLEAN | Airline satisfaction level (Satisfaction/neutral or dissatisfaction) |

>>>>>>> 90e10896df947fd61c884d4b21e8b9b3d85e48c9

### Machine Learning Model - Initial proposition

#### Supervised Learning Model

Machine learning is the use of statistical algorithms to perform tasks such as learning from data patterns and making predictions.

Supervised learning is an approach to creating artificial intelligence, where a our algorithm is trained on input data of Airline Passenger Satisfaction,that has been labeled. The model will be trained until it can detect a relationships between the input data and the output labels.

In this project we are determining the satisfaction for a future customer. 

![Graph](images/MLM.png)


### Technologies

- **Jupyter Notebook** -  https://jupyter.org/

An open source and practical platform that allows coding in multiple languajes and it is able to include text, images and so on, through the execution of the code in the kernel. 
This source will help us to manipulate the data, in uses such as: cleaning, conversion,modeling the data, among other functions. 

- **PostgreSQL** - https://www.postgresql.org/

An open source relational database management system. It will allow us to define, create, and control the database.

- **RStudio** - https://www.rstudio.com/

An integrated development environment or add on of R, that indeed takes the R software and add it to a graphical interface.  
It will help us to plot, debugg, and manage our data, mainly to find correlation between our inputs from the database. 

- **Tableau** - https://www.tableau.com

Visualization software of interactive data that will help us to show the results in a better comprehensive way. 

