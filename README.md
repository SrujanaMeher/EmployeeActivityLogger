# EmployeeActivityLogger
Our project The Employee Activity Logger is typically a Web Application that caters the much needed functionalities of the daily working employees under the Steel Plant hood. 
Not only simply catering the needs but we have taken all the efforts to enhance the efficiency of carrying out their tasks at a comparatively much swifter and flawless fashion.

The present scenario:

a. Employee attends his/her shift and at the end of the day reports the respective activities for the day.
b. The employee’s report consists of all the problems encountered on a day along with his perspective of solving them.
c. This report is inspected by HOD of the respective department.

Through E-A-L:

a. The basic aim of implementing E-A-L(Employee Activity Log) is replacing the handwritten[paper based] reports with a Web Application which holds all the reports and Activity logs of the daily routine of the employees, so that it will be more flexible, both for the employee as well as the HOD.
It reduces paper work and also serves a multidimensional purpose where in all the employees can get the solution to a recurring problem by simply revisiting the previous solution(s) to that problem.
b. This saves time.
c. This Web Application is more reliable and easy to use.

Modules and functionalities:
The actual ingredients of the Employee Activity Logger are as follows:
To start with, the Database used in this project was ORACLE 11g Express Edition. The Oracle Database 11g Express Edition (Oracle Database XE) is an entry-level, small-footprint database based on the Oracle Database 11g Release 2 code base. This is purely a relational database and we had used a total of 3 tables, which sufficiently fulfilled the needs of our project’s data storage.

The tables along with their constraints are illustrated though the following sequence of snippets:

![image](https://user-images.githubusercontent.com/16867941/114113634-bd204800-98a4-11eb-9c41-1cb4fb7fee8f.png)

![image](https://user-images.githubusercontent.com/16867941/114113640-c1e4fc00-98a4-11eb-9919-efd173d47ec8.png)

![image](https://user-images.githubusercontent.com/16867941/114113656-c90c0a00-98a4-11eb-842c-59bc764a1f06.png)

All necessary Database design steps like Normalization, etc. were taken in order to eliminate redundant data and erroneous data retrievals.
Achieving for Platform Independence and higher security we have chosen the Java Enterprise Edition as the programming language for the build of this entire web application.

JavaEE 6.0 have been used and the Java Database Connectivity (JDBC) API has been used for connecting to the database. We have used the THIN Driver (ojdbc6.jar) as the driver for connecting database of oracle.

The front end of this project includes the HTML5 as its crux and Cascading Style Sheets (CSS3). We have always tried to maintain a reasonably rich User-Interface and at the end we almost achieved it.

JQuery has been used in achieving the rich user interface which was a result of JQuery’s effects and its highly functional JavaScript library. The entire Front End validations have been done with the help of JQuery library.

Java Server Pages were used to execute the business logic for the entire application. Our project’s architecture was created more robust so that it would be fit for exhibiting the most wanted feature of scalability.


ARCHITECTURE OF THE EMPLOYEE ACTIVITY LOGGER

![image](https://user-images.githubusercontent.com/16867941/114113374-0d4ada80-98a4-11eb-92a0-ef030530000c.png)

The user initially views a HTML page and is requested to input his mode of Activity.
Here every Employee is authenticated by Registering for the EAL in our ealregister.html page. The following code snippet shows the employee registration page where the employee just enters his/her employee id and the basic details are pre-fetched in order to provide authenticated registration. Then a password matching the required criteria is accepted and the registration would be completed:

![image](https://user-images.githubusercontent.com/16867941/114113434-33707a80-98a4-11eb-8018-6d880cfeb74c.png)

Here there will be no duplicate and proxy registrations whatsoever as we validate the employee id and match with the already present employee database at the RINL-VSP. Every employee is requested to choose a password during his/her registration.
Later the employee Logs in for performing his activities. The following is the snippet showing the EAL’s Log-In page:

![image](https://user-images.githubusercontent.com/16867941/114113895-50597d80-98a5-11eb-965f-1412d222e9b3.png)

The following snippets show the Log Book entry page in the employee workspace.

![image](https://user-images.githubusercontent.com/16867941/114113940-61a28a00-98a5-11eb-91ee-de3a2b319fd8.png)

The next major service being catered by the EAL as a web application is SEARCHING THE PAST ACTIVITIES. The main purpose of this searching is providing the
employees with past observations and solution of a problem for future reference. Searching is done based on two criteria:
1) DATE Period 2) ACTIVITY TYPE

1) Search by DATE:
Searching according to date allows the employee to search for a particular day or for a span of days or for a month, etc. depending on the requirement. On searching by date displays the following results will be displayed along with the captured time of entry of logbook.
The following screenshot clearly depicts the searching activity of the EAL by DATES basis.

![image](https://user-images.githubusercontent.com/16867941/114113989-7aab3b00-98a5-11eb-8e4c-9f376684d45a.png)

2) Search by type of ACTIVITY:
Search by activity allows employees to search by activity confined to their section or zone. On searching all the details relating to particular activity will be displayed along with the date. For each zone there will be different equipment and activities performed.

The searched data can also be further sorted according to the date, equipment, activity, observations, and modifications in a sequential manner. And the most useful function is Search within a Search which allows employees to search for a particular keyword in a search result.
The following screenshot clearly depicts the searching activity of the EAL by ACTIVITY basis:

![image](https://user-images.githubusercontent.com/16867941/114114058-9d3d5400-98a5-11eb-9c90-6c5f8fa7c2cb.png)

The number of result display can also be restricted to 10 or 50 or 100 per page according to the flexibility of the user.
The search is provided with some other functions for report generation on the searched data so that it is more reliable to the user for future reference. The functions are as follows:
a. Generate PDF.
b. Generate an excel sheet.
c. Copy the data into another page.
d. Printing the results.
The following screenshot clearly depicts how the results are exported into pdf and excel sheets:

![image](https://user-images.githubusercontent.com/16867941/114114122-c2ca5d80-98a5-11eb-9f61-c6088bb9fd42.png)

![image](https://user-images.githubusercontent.com/16867941/114114137-d1187980-98a5-11eb-96d3-e2c1269841e3.png)

CONCLUSION:

This project deals with the execution of the Employee’s Daily Activities in a more efficient and succinct manner which makes the work of the Employee much easier. In our Employee Activity Logger features that ensure the accuracy of record maintenance and its searching based on user requirements have been embedded.

FUTURE SCOPE:

As of now our project is a Web rendered application comprising of the above mentioned functionalities. The scope of this project can be further enhanced where-in we can develop an Android application for more scalability, allowing the employees with easier and quicker access. 

Some more functionalities, such as e-mail alerts, mobile OTP authentications, fast and easier communication among employees encircled in a distant geographical area inside the RINL-VSP could be achieved through a Chat Box and a Notification space.



