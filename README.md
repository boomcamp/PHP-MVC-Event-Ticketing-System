# PHP - MVC (Event Ticketing System)

This is a comprehensive test of all of your skills as a PHP developer and to get you practice on how to develop using mvc applications, you'll be expected to implement each specified feature to the best of your abilities. Along with working features, attention will be paid to how you organize your application code.

# Design and Layout

* Bootstrap or Foundation

# Database Design

These are the expected various entities and relations that you should implement in your event ticketing application

<details>
<summary> Database name : ticketing_db </summary>

```
`roles`

* id 

* name Enum(admin = 1,guest = 2) = Enumeration of the role types

`users`

* id

* username = holders the username of the users

* password = hods the passwords of the users

* role_id = the role type of the users (Admin or Guest)

`events`

* id

* name = The name of the event (Eraserheads Reunion Concert)

* price = The ticket price of the event

`Guests`

* id

* user_id = Foreign key of the guest from `users` table

* fullname = The complete name of the attendees

* email = Contact email of the guest

* address = Contact address of the guest

* contact = Cellphone number of Phone number of the guest


`event_guest`

* id

* event_id = Foreign key of the `events` table

* guest_id = Foreign key of the `guests` table

* quantity = How many tickets ordered

* total = Total price of the ticket
```

</details>



# Requirements

### Login / Registration Page:

When a user first navigates to your application they should be greeted with a Login / Registration page.

* New Users - Should have the ability to register to use your Address Book application

* Existing Users - Should be able to login to the application with a username and password combination.

The login form should have username and password as required fields.

Form field errors should be displayed to the user with a useful message.

If login fails, a message notifying the user of the failure should be shown.

When registered or authenticated the user should then be directed to the main "Main Dashboard" page.

# Tests

* Should have atleast `5 passing tests`.


# Main Dashboard 

This is the main landing page of your application, and your application should have this following features:

Guest : 

* Guest must have an option to book an event

* Guest must have an option to cancel/delete his event.

* Guest must have an option to view his events


Admin : 

* Admin must have an option to view/update event reservations

* Admin can reports (atleast one)

* Admin can automate sending email confimations (bonus) 


> Bonus Feature: having a responsive layouts


# Finished

Submit a link of your github repository to the Google Classroom assignment related to this project.

### Good Luck!

