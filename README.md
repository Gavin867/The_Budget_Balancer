# The Budget Balancer

![License Icon](https://img.shields.io/badge/license-GPL3.0-informational.svg)

A deposit and expense tracker which uses Progressive Web Apps to provide optimal budget balancing functionality.

## Table of Contents

- [Location](#locations)
- [Application Summary](#application-summary)
- [Installation](#installation)
- [Testing](#testing)
- [Usage Instructions](#usage-instructions)
- [Future Development](#future-development)
- [Contributors](#contributors)
- [Resources](#resources)
- [Point of Contact](#point-of-contact)
- [License](#license)

## Locations

GitHub Repository Link: https://github.com/Gavin867/The_Budget_Balancer

Heroku Deployed Link: 

## Application Summary

![Landing Page Stillshot](https://github.com/Gavin867/The_Budget_Balancer/blob/main/public/assets/images/readme-images/main-page.png)

The purpose of the Budget Balancer is to track and store all your deposits and expenses. With this application you can do the following:

1. ADD new deposits.
2. ADD new expenses.
3. VIEW list of transactions.
4. VIEW account balance.
5. VIEW interactive chart with dates and balances.
6. App caches data and resubmits requests to the server if network connection is interrupted.

## Installation

No installation is required for running the deployed version of this application. Simply click the '[Deployed Application Link]()' provided in the '[Location](#location)' section to get started.

To run locally follow the following instructions...
1. Install MongoDB Atlas and Robo 3T workbench using the directions outlined in the '[mongoDB Documentation](https://docs.mongodb.com/manual/installation/)' and '[Robo 3T Documentation](https://robomongo.org/)'.
2. Clone the repository to your computer.
3. Connect the repository to your Robo 3T.
4. Open a new terminal instance in the Git SWOL Tracker code file and run "npm i" to install the npm packages needed to run the program.
5. In the Budget Balancer file code terminal, type "node server" and hit ENTER.
6. Copy and paste http://localhost:3000/ into your browser and the application is now running.

## Testing

See usage instructions.

## Usage Instructions

1. To ADD a deposit to the balance, type the name of the deposit and the amount of cash being added in the form boxes, then click "Add Funds".
2. To ADD an expense to the balance, type the name of the expense and the amount of cash being removed in the form boxes, then click "Remove Funds".

## Future Development

Additional goals and application features for future devlopment include:

- Personalize/update the UI/UX design
- Integrating REACT and Handlebars

## Contributors

- Gavin Calkins - https://github.com/Gavin867

## Resources

- Lessons from UW Full Stack Flex Boot Camp.
- Tutoring with Namita Shenai (https://github.com/NVK2016)


## Point of Contact

Have questions? Contact Gavin Calkins at [gavin.calkins@gmail.com](mailto:gavin.calkins@gmail.com?subject=Hi%20Gavin!%20I%20have%20a%20question%20about%20The%20Budget%20Balancer!).
 
## License

    The Git Swol WOD Tracker. A mongoDB application for people who like to lift things up and put them down ...and then take notes about it.

    Copyright (C) 2021  Gavin B. Calkins 

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.