# Local webhook
 
Convert local folder into a repository of data that can be transfered via the web from any site that uses webhooks. 

Designed by Camilo Mora and developed by Mohammed Ibrahim


## Perquisites
 Ngrok account authentication token. Refer to next section for how to get the token
 
 
 ## Ngrok 

 1. Create Ngrok account from [here](https://dashboard.ngrok.com/signup)
 2. An email will be sent to you with verification link to verify your account.
 3. Navigate to your dashboard to get auth token.
 
 <img src="https://github.com/Camilo-Mora/LocalFolderWebhook/blob/main/Images/NGrokToken.png" width=50% >
 

 4. Copy your authentication token as we will need it later.
  



## Running the app

1. Download the dist.zip file in this repository, and unzip it.

2. Double click the main.exe file, and a window will pop-up.

3. Click on "Token" button, a pop up window will request your auth token
  
  <img src="https://github.com/Camilo-Mora/LocalFolderWebhook/blob/main/Images/InsertToken.png" width=50% >
  
4. Paste the token from your ngrok dashboard.
  
  <img src="https://github.com/Camilo-Mora/LocalFolderWebhook/blob/main/Images/InsertToken2.png" width=50% >

5. Press Ok, now ngrok will automatically use this account to make the required tunnel.

6. Click on Browse  button, and select the folder you would like to forward the notifications to as .csv

7. Now copy the webhook, which you can now use in any webpage that accepts wedhooks. That webpage can now trasnfer that via this webhook to your local file.
 
 <img src="https://github.com/Camilo-Mora/LocalFolderWebhook/blob/main/Images/Webhook.png" width=50% >


## Important note
Do **not** delete the .env file near the exe. It holds the settings for the app. Also, don't delete ngrok.exe 
The files that are transmited should not include special characters as that is used as the file name, and Windows do not allow special characters.
