rn-assignment4-11135953

Overview

This repository contains the code for a React Native application named Jobizz, developed as part of an assignment. The app allows users to log in with their name and email and then displays their details on a home screen. The home screen features job listings, divided into featured and popular jobs, each implemented as reusable components.

App Functionality

Login Screen

Component: 
LoginScreen

Description:
This screen allows users to input their name and email. Upon pressing the "Log in" button, the app navigates to the HomeScreen, passing the user's name and email as parameters.

Home Screen

Component:
HomeScreen

Description: 
The home screen displays the user's name and email at the top. It also includes sections for featured and popular jobs, each showcasing at least 8 job cards. The job cards display job details such as title, company, salary, and location.

Job Card Component

Component: 
JobCard

Description:
This reusable component displays individual job details. It accepts job information through props and can be used to render job listings in different sections of the home screen.

Screenshots
Login Screen
![Screenshot 1](https://github.com/davidboateng451/rn-assignment4-11135953/assets/151746606/7b655aa6-7781-4ec8-a0b4-b010fe6184d0)


Home Screen
![Screenshot 2](https://github.com/davidboateng451/rn-assignment4-11135953/assets/151746606/222fc478-42a5-45a8-82be-ef947f61919a)

