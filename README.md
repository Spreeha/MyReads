[![Depfu](https://badges.depfu.com/badges/ffc18d5b7061ef25e962a4f34bfc50e5/status.svg)](https://depfu.com)
[![Depfu](https://badges.depfu.com/badges/ffc18d5b7061ef25e962a4f34bfc50e5/overview.svg)](https://depfu.com/github/dimikara/react-my-reads?project_id=11514)


# MyReads Project


# Table of Contents

* [Overview](#overview)
* [Specification](#specification)
* [How to run the project](#how-to-run-the-project)
* [Important](#important)
* [App Functionality](#app-functionality)
* [Credits & Helpful Links](#credits-&-helpful-links)
* [Screenshots](#screenshots)



## Overview

In the MyReads project, a bookshelf app is created that allows the user to select and categorise books they have read, are currently reading, or want to read. This projct will use React to build the application and provide an API server and client library.


## How to run the project

To run the project, download or clone the repository in your computer:

    $ git clone <Git URL>

and follow the instructions below.

In the repository folder: 
* install all project dependencies with 

        npm install
* start the development server with 

        npm start

Please note that the backend server -against which the web app was developped- was provided by Udacity. The provided file [`BooksAPI.js`](src/BooksAPI.js) contains the methods I used to perform necessary operations on the backend:

* `getAll`
* `update`
* `search`

For more information on how these methods are used exactly, please refer to the original [Udacity repository](https://github.com/udacity/reactnd-project-myreads-starter).



## App Functionality

In this application, the main page displays a list of "shelves" (i.e. categories), each of which contains a number of books. The three shelves are:
* Currently Reading
* Want to Read
* Read

Each book has a control that lets the user select the shelf for that book. When the user select a different shelf, the book moves there.

The search page has a text input field that may be used to find books. As the value of the text input changes, the books that match that query are displayed on the page, along with a control that lets the user add the book to their library.



## Important

The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [**SEARCH_TERMS.md**](SEARCH_TERMS.md). That list of terms are the **only terms** that will work with the backend.

