# Group_3
Sara Egan, Gabriel Plaza, Milosz Lewandowski

<br>

## Description of the application (what it is used for)
Our project is an app that allows the user to find new events in Frankfurt. When you first run the app you will be able to see all events that are currently happening in Frnakfurt.\ 

Once you register a new account or sign into an existing account, you will be able to enter a private area. This area will include your private information such as your name and username. You will also be able to see your wishlist of events. You can only see this information when you are signed in.\

The user is able to add and delete events from their wishlist. The user can also update their password.

<br>

## Description of the database (ER-model & dump-file)
Our database has 3 tables: event, user and wishlist.

Event contains information on the concerts that are taking place. It holds attributes such as the artist name, the date and location that they are playing and a description.

The user table contains information on registered users. It holds the following attributes: first name, last name, username and password.

The wishlist table stores the events that a user has saved to their account. It contains the userID and stores the eventID. The userID is also the primary key of this table as each user of our application will have their own unique wishlist. A user can store as many events as they like to their wishlist.

The following is the relationships between our tables: User has a one to one relationship with wishlist. This is because each user can only have one wishlist and a wishlist can only belong to one user. Event has a one to many relationship with wishlist. This is because one event can belong to many wishlists and a wishlist cannot have duplicate events.


# ER Plan
![erd draft](https://user-images.githubusercontent.com/98482460/236885911-50131a49-f8fa-4fbe-bf11-78b667ecff7f.png)

# Final ER Model
![saraerd](https://user-images.githubusercontent.com/98482460/236886518-4e014e60-ec7a-4929-aa4e-2355f88a59f6.png)

<br>

## Instructions "how to install the application, so that a new developer can start to work"

Task	Points
Task 1	x
Task 2	x
Task 3	x
Task 4	x
Task 5	x
Task 6	x
Task 7	x
