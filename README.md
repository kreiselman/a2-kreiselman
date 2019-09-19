Assignment 3 - Persistence: Two-tier Web Application with Flat File Database, Express server, and CSS template
===



## Class Height Chart
This application is used to record students' names, class years and height in inches. The data and login information is stored in a database using lowdb.
The user will first create an account or log in to the webpage. Afterwards the user will input a student's data into the field on the left side and click submit. The fields are for the student's name, class year,
and height in inches. If a user would like to remove a student from the list they would need to input the student's name into the right side text box and click on delete. It will only delete the proper field if 
the name is typed exactly as shown in the table, ie capitalization and spelling.
The table has been prefilled with info of three students. The table will appear when data is added to it and when the page loads if previous data is stored.

- This application is used to record the following information of students: name, class year and height in inches.
- Challenges faced in this application are working with passport, and project planning. Passport was the major problem for me in this application. I was confused on how to implement it
  at first but then I found this helpful tutorial online that went into more details of how to implement passport locally: https://github.com/passport/express-4.x-local-example.
  I also had a problem with project management. I restarted this project three times due to being confused with how to implement passport locally and with cookies. I did not have a plan going into
  the assignment and got overwhelemed. On my third restart I slowly approached it with a plan and was successful (in my opinion).
- I used a local passport authentication because I was told in class that it was easier to implement and I followed a tutorial online as seen above. I used lowdb because that was covered in class
  and was relatively easy to use.
- I used the Bootstrap 4 CSS Framework for my application because it was recomended to me by a friend and various websites on the internet. I did not make any modifications to the framework.
- The five express frameworks used are:
  Passport: Passport was used to authenticate users to allow for access to the 


CSS changes include moving the table to the center of the webpage, placing the input and delete fields side by side around the table and modifying the buttons to appear larger.


Justin Kreiselman (jkreiselman)
https://a3-kreiselman-justin-kreiselman.glitch.me

## Technical Achievements
- **Tech Achievement 1**: Used express js (https://expressjs.com/) to streamline get/post requests and functions. This can be seen in server.improved.js in the .get and .post functions as well as in scripts.js for the getData()
    and clearData() functions.
    
- **Tech Achievement 2**: Used jquery (https://jquery.com/) to help with manipulating the data to display it in the table. This can be seen in scripts.js in the getData() function.


