# Weight-Tracker
**Application Requirements**

1. Log in & Sing in 
  When a user tries to log in, the app checks the user name that has already been signed up in the database and allows    the login. If the user has never logged in, the app allows user to sign up a username so that user can sign in. 

2. Database
  Use SQLite to store goal weight and daily weight and enable CRUD, a basic database processing function.

3. User Permission for SMS notification
  When the goal weight matches the daily weight, the permission for SMS notification is requested to receive text message notifications according to the user's selected option (yes or no).
---
**UI Design**

  The layout of this app consists of a total of 5 screens. The main theme color, green, was used in harmony with the  background color of yellow beige and the point color of orange, so that the overall app was unified. 

  According to the requirements of the app, the sign-in and sign-up buttons were applied to the first layout to meet the requirements. If you press the sign-up button in the first layout, you will be taken to a layout where you can create an account, and if you save your username and password, you will be taken to the main page of the app. On the main page, the user can input data by selecting the goal weight and daily weight, which are buttons shown in the card view.  In the goal weight layout, the user can, of course, input the goal weight or set the sms notification.  In the daily weight layout, the user can input the date of weighing and the weight on that day.

<img width="294" alt="Screen Shot 2022-04-24 at 8 15 40 PM" src="https://user-images.githubusercontent.com/37701529/165002841-65c0691c-348b-430d-9376-7cb93a4b11e0.png">

<img width="294" alt="Screen Shot 2022-04-24 at 8 16 31 PM" src="https://user-images.githubusercontent.com/37701529/165002846-605b38db-483c-4006-9189-2c0e72917781.png">

<img width="294" alt="Screen Shot 2022-04-24 at 8 16 00 PM" src="https://user-images.githubusercontent.com/37701529/165002843-d959ec46-8dc9-4d10-9fd3-9cf6f5d29b57.png">

<img width="294" alt="Screen Shot 2022-04-24 at 8 16 11 PM" src="https://user-images.githubusercontent.com/37701529/165002844-aa20e6ff-80c9-4def-b433-7898321e38dc.png">

<img width="294" alt="Screen Shot 2022-04-24 at 8 16 23 PM" src="https://user-images.githubusercontent.com/37701529/165002845-92c1fc58-08b2-4be8-99bc-83990f6b5611.png">

---
**Approach**

The app's ui elements and layout design were made based on wireframes. After that, the organization of the code had to be done through mvc, but it is still in the maintenance development stage, and the completed code will be updated later.

---
**Testing**

I tested by using Log.d(String, String) to display messages in logcat. This process was very important and useful for finding errors when an app doesn't work properly in Android Studio, because it's the only way to know if your code is working as intended.

---
**Challenges**


I've had a hard time building a database and fetching and using data. In the future development, I will improve the database so that all data entered by the user is displayed in a view within the app.

---
**Successful Componenets of the App**

To be honest, my app doesn't function well except for design. Now that I know about the things that can be improved with this project, I will update the completed code based on this experience.
