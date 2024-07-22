<a id="readme-top"></a>

<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
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
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

Tracking job applications can be very stressful. Jobster is an app built to solve this problem. Create an account and get started!

The live deployed site can be found at 


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![React][React.js]][React-url]
- [![Redux][Redux.js]][Redux-url]
- [![Node.js][Node.js]][Node-url]
- [![Express][Express.js]][Express-url]
- [![MongoDB][MongoDB]][Mongo-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Install npm on your local machine

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/ItsKader/Job-Tracking-App.git
   ```
2. Create a MongoDB Cluster, set DataBase Access, set Network Access and get the MONGO_URI connection link by connecting to the Cluster through drivers (if you don't have an account yet, you first need to create one at https://www.mongodb.com/).
3. Create a .env file in the main project folder and setup your environment variables.
  - Add your MONGO_URI link (name and password must be replaced with the credentials of a user with DataBase Access).
  - Add your JWT secret (a secure generated key is recommended).
  - Add the lifetime of the JWT token (e.g: 30d).

   ```js
    MONGO_URI=
    JWT_SECRET=
    JWT_LIFETIME=
   ```
4. To run the entire application (front-end and back-end) Install NPM packages in the project main folder and start the server.
   ```sh
   npm install && npm run dev
   ```
5. (Optional) You can populate the database with prop jobs for the demo user to see how insights would look like.
   ```sh
   node populate
   ```
6. To just run the fron-end, navigate inside client, install NPM packages and start the React development server.
   ```sh
   cd client && npm install && npm start
   ```




<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->

## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->


[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Node.js]: https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white
[Node-url]: https://nodejs.org/
[Express.js]: https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white
[Express-url]: https://expressjs.com/
[MongoDB]: https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white
[Mongo-url]: https://www.mongodb.com/
[Redux.js]: https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white
[Redux-url]: https://redux-toolkit.js.org/
