# Budget Tracker PWA
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
## Description
  
A budget tracker app, which works in online and offline mode, utilising Web Manifests and cache APIs as well as IndexDB to store offline generated user data.
  
## Table of Contents
  
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)
  
## Installation

A deployed version can be [found here](https://budgetmylife.herokuapp.com/). Connection to a MongoDB database is required for the functioning of this app. 

```
git clone https://github.com/maria-helbling/budgettracker.git
npm install
npm start. 
```

## Usage

Having a fast anad easy way to track your money is important for good financial health. That information needs to be available any time any where regardless of the availability of an internet connection.  
```
AS an avid traveller 
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection 
SO THAT my account balance is accurate when I am travelling. 
```
### Acceptance Criteria: 

```
GIVEN a user is on the app without an internet connection 
WHEN the user inputs a withdrawal or deposit 
THEN that will be shown on the page, an added to their transaction history when their connection is back online.
```

## License
  
The application is released under the MIT license.
  
## Contributing
  
To contribute to this application, create a pull request. Here are the steps needed for doing that:

* Fork the repo
* Create a feature branch (git checkout -b NAME-HERE)
* Commit your new feature (git commit -m 'Add some feature')
* Push your branch (git push)
* Create a new Pull Request
        
Following a code review, your feature will be merged.
  
## Tests
  
There are no project specific tests provided.
  
## Questions
  
Link to author's [gitHub profile](https://github.com/maria-helbling).

