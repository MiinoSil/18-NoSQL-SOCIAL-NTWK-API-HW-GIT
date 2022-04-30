# 18 NoSQL: Social Network API with Walkthrough using INSOMNIA

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Links

[GitHub Repo](https://github.com/MiinoSil/18-NoSQL-SOCIAL-NTWK-API-HW-GIT)

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [NPM requirements](#npm-requirements)
- [Usage](#usage)
- [Walkthrough](#walkthrough-videos)
- [Credits](#credits-and-author)
- [License](#license)
## Description

MongoDB is a flexible database that works with unstructured data in large quantities and speed. This backend API is a social network web application where a user can share thoughts, react to other users' thoughts, create a friend list. It uses Express.js, MongoDB, and Mongoose. A video walkthrough displays interaction with API using INSOMNIA. 

### User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

### Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## NPM requirements
| NPM Package | code to run |
| ----------- | ----------- |
| Express.js | ```npm i express``` |
| Mongoose | ```npm i mongoose``` |

If cloned from REPO with package.json, just run the following code:
```
npm install
``` 
OR 
```
npm i
```

## Usage

1. Install required NPM packages
2. Via command line or terminal:
```
npm start
```

## Walkthrough Videos

| Description | Video |
| :---------: | :---: |
| Install NPM and starting server</br>[Screencastify Original](https://drive.google.com/file/d/1ljFNsnr1s3ZIov4TlwfHI4gpJchrnHdd/view) | <img src="./Assets/18-nosql-start-server-demo.gif" alt="Install NPM, start server" width="1000"> |
| POST, GET, PUT, DELETE: Adding users, getting all users, getting a single user, updating username by Id, deleting user by Id</br>[Screencastify Original](https://drive.google.com/file/d/1MnW8zB7kVesegw82L8GYglRb6pr6N_jT/view)  | <img src="./Assets/18-nosql-POST-GET-PUT-DELETE-USER-demo.gif" alt="POST, GET, PUT, DELETE USER" width="1000"> |
| POST, GET, PUT, DELETE: Adding thoughts, getting all thoughts, getting a single thought, updating thoughts text, deleting thoughts</br>[Screencastify Original](https://drive.google.com/file/d/1p5q1TUwaffRGY30WSHwzWzL3JLEO2qsO/view) | <img alt="POST, GET, PUT, DELETE Thought" src="./Assets/18-nosql-POST-GET-PUT-DELETE-thoughts-demo.gif" width="1000"> |
| POST, DELETE: Adding and deleting reactions</br>[Screencastify Original](https://drive.google.com/file/d/12qujef1F87G37CjkyZgsHHVW5yBczqhi/view) | <img src="./Assets/18-nosql-POST-DELETE-reaction-demo.gif" alt="POST, DELETE a reaction" width="1000"> |
| POST, DELETE: Adding and deleting friends</br>[Screencastify Original](https://drive.google.com/file/d/1RezAispmbstNgtcC7R7tbsJ52lnltZfP/view) | <img src="./Assets/18-nosql-friendsList-POST-DELETE-demo.gif" alt="POST, DELETE friends list" width="1000"> |

## Credits and Author

[GitHub Profile](https://github.com/MiinoSil)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[LICENSE](./LICENSE)