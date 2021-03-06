 # Proposal For the Class Remainder
 ## Introduction
 - Our app mainly focus on students to remainded their class timings and room number as per their schedule and list of the classes need to attend in a day.
 
 ## Overview of the Application
 - App contains two screens to display the upcoming classes of student.
 - On first screen recent upcoming class with time and room number is displayed in a rectangular box.
 - User clicks on box to redirect to second screen.
 - Second screen displays list of all upcoming classes with time and room number.
 
 ## Team members and their roles
 
   - [Giridhar Addagalla](https://github.com/giridhar196)
   - [Vyshnavi Tadipaneni](https://github.com/vyshnavi1996)

## Functional Requirements

### Home Screen:
1.	API to get the upcoming class with room number and time.
2.	Button to redirect to list of upcoming classes.
3.	Add class button to add new class (subject, time and date, room number).
### Classes List Screen:
1.	API to display list of all upcoming classes.
2.	Edit button for each class to edit class details.
3.	Delete button for each class to delete a class.
### Login Page:
1.	Text fields to enter username and password.
2.	Button for authenticating into the application.
3.	Forgot password link, to reset the password.
### Header:
1.	Your profile link to navigate to user details.
2.	Logout button to logout of the application.


## Schedule & sprints are set by the GDP semesters (about every 2-weeks = a sprint)

## GDP-1 

#### Sprint 1  (Start Date: 20 September 2021 - 4th October 2021)
- In sprint 1 we work with plan and all the basic reqirements gathering. 

#### Sprint 2  (Start Date: 4th October 2021 - 18th October 2021)
- Enhancing and modifing the requirements and break them into functional requirements.

#### Sprint 3  (Start Date: 18th October 2021 - 1st november 2021)
- Building mockups and basic UI pages using Angular.

#### Sprint 4  (Start Date: 1st November 2021 - 15th November 2021)
- Working with login and Authentication pages.

 End of semester GDP-1

## GDP-2 

 #### Sprint 5  (Start Date: 12th January 2022 - 26th January 2022)
 - Create Database models and schema

 #### Sprint 6  (Start Date: 26th January 2022 - 9th February 2022)
 - Design web APIs

 #### Sprint 7  (Start Date: 9th Fabruary 2022 - 23rd February 2022)
 - Create APIs to fetch data from DB

 #### Sprint 8  (Start Date: 23rd February 2022 - 9th March 2022)
 - Design all the UI pages based on requirements

 #### Sprint 9  (Start Date: 9th March 2022 - 23rd March 2022)
 - Integration with both UI and backend.

 #### Sprint 10  (Start Date: 16th March 2022 - 30th March 2022)
 - Testing and fixing issues

 #### Sprint 11  (Start Date: 30th March 2022 - 15th April 2022)
 - Deployment of the application, and prod fixes.
 
#

## Budget 
| S. No.| Name               | Role                | Hourly Pay             | Hours/ Week  | Estimated Cost/ Week |
|------|---------------------|-------------------- |------------------------| ------------ | ---------------------|
| 1    | Giridhar Addagalla  | Back-end Developer  | $45                    |   9 - 12     |  $405 - $540         |
| 2    | Vyshnavi Tadipaneni | Front-end Developer | $45                    | 9 - 12       | $405 - $540          |

## User Stories/Tasks
 ### Userstory1: User can register module.
 #### Acceptance criteria:
 The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
### User Story2 : User can login in login module.
#### Acceptance criteria:
The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
### User Story3 : User can create a adding schedule to class remainder app.
#### Acceptance criteria:
The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
### User Story4 : User can edit a schedule.
#### Acceptance criteria:
The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
### User Story5 : User can display a single class with timings and room number.
#### Acceptance criteria:
The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
### User Story6 : User can manage his team in user profile module.
#### Acceptance criteria:
The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
### User Story7 : The User should be able to provide list of class for the student and and provide room number and timings of the class.
#### Acceptance criteria:
The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
### User Story8 : User can create  a home page with background image and color.
#### Acceptance criteria:
The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.
### User Story9 : User can create navigation from one page to other using connections.
#### Acceptance criteria:
The RFP is yet to be reviewed by the client.Once it is approved we will work on this task.


## Database Tables
 ### User
    - id
    - name
    - role
    - is_delete
### Class Details
    - id
    - user_id
    - classroom_id
    - start_time
    - end_time
    - is_delete
### Classroom Details
    - id
    - room_number
    - subject
    - is_delete

## Entity-Relationship Diagram
 ![erdiagram](erdiagram.png)

The above diagram speek how our data integrate and basic required fields in order to secure the account.

## Sample Data
  - [Sample_data](sample_data.xlsx)

## Backend language + framework (C#/.NET)

- This work will be targeted on Sprint 6 and sprint 7 as per schedule.

## Backend free app host (Heroku or Our Developer's Own Server)

- This work will be targeted on Sprint 9,10 and 11 as per schedule.

## Data host (Atlas MongoDB and SQL)

- Usage and creation of databases will be started on sprint 5.

## Front-end page plan (Build with CSHTM Not a Single page)

- Sprint 3, 8 qand 9 will cover the UI part.

## Front-end responsive design (Bootstrap)

- Sprint 3, 8 qand 9 will cover the UI part and design perspectives.

## References :
https://getbootstrap.com/docs/5.1/getting-started/download/
