# Top_Sales

**What is this project?**
The Top_Sales project is a project I created that highlights user authorisation, security implementations, encryption and data visualisations using Angular, C#, HTML, CSS, JavaScript and SQL. It allows a user to register to a website
after which they may login to view pie charts that represent the product count by brand and product type.

**IMPORTANT NOTES FOR INSTALLATION**:
**FRONT-END SETUP**
1. Using visual studio code, open the frontend_angular folder (The root project folder)
2. Open a new terminal and run npm install. Make sure you are connected to the internet and wait for the required packages to install.

**BACK-END SETUP**
4. Open and run the assignment3dData.sql file. This will create a db called Assignment 3 along with its tables. I'd recommend using Microsoft SQL Server Management Studio (SSMS).
5. Using Visual studio, Navigate to backend_api > Assignment03 and run the Assignment03.sln file. This is the API
6. When the application has opened head to the appsettings.json file. Look for the "DefaultConnection:" Setting. Change the server from "DESKTOP-FL5451D" to the name of your PC.
7. Install the Mailkit Nuget Package.
8. Head to the AuthenticationController file. Under the login replace "senderemail@gmail.com" with your own email. On line 92 add your email address to the second argument of the MailboxAddress function. Replace "password" with the app specific password for your Gmail account.

**RUNNING THE APPLICATION**
1. Open and run the API (Backend_api)
2. Open the angular application. Make sure you are in the root folder.
3. Open a new terminal and type "ng serve". Wait for the Angular development server to run and open the link on Google Chrome.
   
