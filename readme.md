**Hello this is my workshop project for my learning of java jsp-servlet with MVC2.**
**I hope my project will helpful for you!**

**The database structure**
- Table User
![image](https://github.com/user-attachments/assets/c0cc237b-54d2-4254-8f67-f8d9b4b8e789)
- Table Product
![image](https://github.com/user-attachments/assets/11f09dc8-edb5-47d4-ab09-377390b43912)
- Table Order
![image](https://github.com/user-attachments/assets/9946d55d-e710-455e-a79d-e9f1479e6a0d)
- Table OrderDetail
![image](https://github.com/user-attachments/assets/8b07aa24-5155-46cd-b269-f45874f4fa61)

**Main Function**
- Login (admin - user).
- user: search product, add to cart, change quantity, remove product, payment.
- admin: CRUD with user account.
- Logout.

**Additional function**
- Encryption password.
- Login with Google Account.
- Google Recaptcha.
- Javax Email.
- VNPay payment. (currently has bug)

**To run the Project in localhost**
- Ensure Java and Apache Tomcat 8.5 are Installed:
- Make sure you have Java Development Kit (JDK 1.8) installed.
- I use NetBean 8.2 IDE.
- Clone or fork the project.
- Resolve library project problem with lib folder.
- Run the Tomcat server and deploy project.
- Main function of project should be work properly.

**To use the Additional function**
- Google Recaptcha: Register Google Recaptcha v2. Get and replace recaptcha sercet key.

- Login with Google Account:
 - Register Google Cloud Console. Create project, get and replace the CLIENT_ID and CLIENT_SECRET.
 - Authorize the project localhost. Ex: http://localhost:8080 and http://localhost
 - Authorized redirect URIs to the CallbackController Ex: http://localhost:8080/PRJ301_3W_1_JSLT/CallbackController

- VNpay payment: not yet.

- Javax Email:
  - Create the Sender Google Account (Unavaiable now).
  - Or use the Google Account registed with Email sender.
  - Get and replace the Email name and Password.
 
Have nice day!
