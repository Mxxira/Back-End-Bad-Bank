# Back-End-Bad-Bank

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This Bad Bank application is my MIT capstone project with front-end, back-end, and database. The Bad Bank name refers to the idea that the application is not secure and doesn't have any security attatched. However, we will be using firebase authentication and authorization to create many types of authorization to turn our Bad Bank into a "better" bank. This project was created for me to learn more about full-stack deve3lopment and take the the information I have gathered thorugh the course and use it to create a multi-tier application, using all of the fundamentals of coding that was taught to me by MIT Pro.


### Built With
* [Firebase authentication](https://firebase.google.com/)
* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/en/)
* [Docker](https://www.docker.com/)
* [MongoDB](https://www.mongodb.com/)
* [Bootstrap](https://getbootstrap.com/)



<!-- GETTING STARTED -->
## Getting Started

Bad Bank is hosted by google cloud services. You can navigate to the url below to see the most recent published version. To download and make edits to the code, see Prerequisites and Installation.

### Prerequisites


* npm
  ```sh
  npm install npm@latest -g
  ```


### Installation
To edit and run locally on your machine

1. Clone the repo
   ```sh
   git clone 
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Run the Node server
   ```sh
   node index.js
   ```
4. Navigate to [http://localhost:3000/](http://localhost:3000/) to run the application


<!-- USAGE EXAMPLES -->
## Usage
Create Account - allows you to create a new users for the bank (you can see the users you've created in the AllData tab) <br />
Login - allows you to login to your bank account <br />
Deposit - allows you to deposit money into your account <br />
Withdraw - allows you to withdraw money from your account <br />
Balance - displays account balance <br />
AllData - for the admin users of the bank - will show all data of all the users of the application <br />
<!--
Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_
-->


<!-- ROADMAP -->
## Roadmap

Front end modifications

A Node.js server 

A MongoDB database and data abstraction layer

API integration

Connection of the front end and back end

Authentication 

The application deployed to Mongo DB

Development of additional features:
* Roles for all different users, such as  bank employees versus any customer
* Money transfer between users
* Account types, such as checking vs savings accounts
* Assignment of random account numbers to new accounts
* User profile updates that are persistent
* Check deposit by taking a picture of the check
