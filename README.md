# MERN-book-search-engine

Deployment URL :https://shielded-anchorage-66124.herokuapp.com/
Repo URL : https://github.com/UofTL/MERN-book-search-engine.git

## Description

🔍 A MERN stack application using Google Books API that allows a user to login, search books and save favorites.
💻 Below is a screenshot of the application:
![image](https://user-images.githubusercontent.com/84641285/141398352-063539bb-2f50-417c-bb93-6ca60f20dc0f.png)
![image](https://user-images.githubusercontent.com/84641285/141398421-9901fb68-34f0-4482-8b05-c85414b1766f.png)
![image](https://user-images.githubusercontent.com/84641285/141398573-f01807a7-970e-451c-9e25-3678b928d5dc.png)
## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

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
## Build With
- CSS
- GitBash
- GitHub
- JavaScript
- NPM package:
    - @apollo/react-hooks
    - @testing-library/jest-dom
    - @testing-library/react
    - @testing-library/user-event
    - apollo-boost
    - apollo-server-express
    - bcrypt
    - bootstrap
    - concurrently
    - if-env
    - graphql
    - graphql-tag
    - jsonwebtoken
    - jwt-decode
    - mongoose
    - nodemon
    - react
    - react-bootstrap
    - react-dom
    - react-router-dom
    - react-scripts
## Install

Clone the repo.
Run the following line of code in your terminal to install all the needed packages for server, client and app folder: 
```
npm i
```
## Usage
- Once all the packages have been installed, open terminal and run the following code in command line : 
  - npm run develop
  ## Github Repository
[Github](https://github.com/UofTL/MERN-book-search-engine.git)
### Contributor
Eleonore Caclard  | [Github](https://github.com/UofTL)