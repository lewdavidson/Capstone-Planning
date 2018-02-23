## Initial UI Mockup:

Every User will first see the [Home Page](https://imgur.com/9W0YuvV), from which they can choose to:

* Log In
* Sign Up
* or search for recipes

If the user chooses to Log In or Sign Up, they will be routed to the [User Authentication Page](https://imgur.com/8dFfi29), where they can create or log in to their account.

If a user decides to search without being associated with an account, they will be routed to the [results page](https://imgur.com/8dFfi29) responsible for displaying 9 recipes matching their search terms.

All [results](https://imgur.com/erd3C7t) will come in the form of cards complete with photo, title, description, like button(saves the recipe to the users 'saved' section) and a more info button, which routes the user to the full-page version of the recipe clicked.

if the user has signed in to their account, the [results page](https://imgur.com/UaeOGW7) will look slightly different, displaying the option to view their [saved recipes page](https://imgur.com/RSMUE6R) in the nav bar.

It is my intention to create a mockup version with sketch that looks more polished once I get my component tree sorted out.

### Component tree

I included a file containing my component tree in sketch. I'm not quite sure if it's the best possible way to structure things, because there are two different versions of the results displays and I don't know if there's a way to dry that up without crossing wires.

![component tree](Component Tree.png)
