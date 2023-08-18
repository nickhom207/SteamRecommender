# CSGO-Clans
## Setup Guide
1. Clone the CSGO-Clans Package
2. Open the root directory of the CSGO-Clans Package
3. Open a terminal and run the command: npm install
4. Also run the command: npm run setup
5. When prompted, type in your postgres password. This will setup the database.
6. Open the env.json file in the root directory
7. Change the password value to your postgres password
8. Change the api_key value to the steam api_key 
9. Cd into the app directory and run the command: node server.js