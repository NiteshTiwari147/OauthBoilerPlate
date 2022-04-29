# OauthBoilerPlate
This is an OauthBoilerPlate repository which authenticate user using Google Oauth service and save users data on mongo DB. It is depolyed on Heroku 

## To Start App 
### local 
  > npm install . <br /> 
  <br />
  
  > npm run dev
### production 
  > heroku open

## Productionaise steps 

### Dev
  *  Create new MongoDB cluster
  * Generate MONGO_URI
  * Create new project on https://console.cloud.google.com/apis/dashboard
  * Add Oauth Consent Screen Info 
  * Create Credentials using OAuth Client ID 
  * Generate Client ID and Client ID
  * Create dev.js file inside config folder
  * Copy Mongo_URI,Client ID and Client ID and add them into config/dev.js file 

### Production 
  * Create new MongoDB cluster 
  * Generate MONGO_URI
  * Create new project on https://console.cloud.google.com/apis/dashboard
  * Add Oauth Consent Screen Info 
  * Create Credentials using OAuth Client ID 
  * Generate Client ID and Client ID
  * go to terminal and run command :  > heroku create, it will return URL
  * Go to https://dashboard.heroku.com/apps and click on newly generate app 
  * Go to settings
  * Click on reveal env variables and add  Mongo_URI,Client ID and Client ID 
  * go to terminal and run command, heroku open, it will open landing page of the app

> ### NOTE: set cookie_key to any arbitarary string containing only characters


