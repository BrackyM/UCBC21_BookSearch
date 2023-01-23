

# Braxton M | UCBC21_BookSearch | README


This project incorporates the use of `graphql`, `Express.js`, `Apollo Server`, `bcrypt`, `jsonwebtoken`, and `MongoDB Atlas` 


The BookSearch application takes the use of RESTful AOI and works on refactoring to a Apollo/graphQL depenedent application.
Users are able to sign up, log in, search a category of google api books, and add them to a saved book collection on their account. This is done
by using mutations, typeDefs, resolvers, and individual queries.



## Acceptance Criteria


  ```md
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
```


## Installation


- Clone the repository
- Run `npm i` in your terminal to install the dependencies
- Download `MongoDB` and connect it to your `MongoDB Atlas`
- run `npm run develop` to run in a development setting
- Test queries are working in Apollo Server
    



## Usage


Use this project to learn more about Mutations and refactoring RESTful API to Apollog/graphQL servers.



## Screenshots

- Screenshot 1: Homepage

![App Screenshot](/assets/screenshot1.JPG)

- Screenshot 2: Example Signup of a User

![App Screenshot](/assets/screenshot2.JPG)

- Screenshot 3: Saving a Book

![App Screenshot](/assets/screenshot3.JPG)

- Screenshot 4: Saved Books

![App Screenshot](/assets/screenshot4.JPG)




## Deployment


- [Live Site](https://ucbc21-book-search-engine.herokuapp.com/)
- [Github Project Repository](https://github.com/BrackyM/UCBC21_BookSearch)




## Contributing


- UC Berkely Activities & Office Hours
