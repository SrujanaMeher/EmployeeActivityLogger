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

![image](https://user-images.githubusercontent.com/16867941/114113374-0d4ada80-98a4-11eb-92a0-ef030530000c.png)

The user initially views a HTML page and is requested to input his mode of Activity.
Here every Employee is authenticated by Registering for the EAL in our ealregister.html page. The following code snippet shows the employee registration page where the employee just enters his/her employee id and the basic details are pre-fetched in order to provide authenticated registration. Then a password matching the required criteria is accepted and the registration would be completed:

![image](https://user-images.githubusercontent.com/16867941/114113434-33707a80-98a4-11eb-8018-6d880cfeb74c.png)

Here there will be no duplicate and proxy registrations whatsoever as we validate the employee id and match with the already present employee database at the RINL-VSP. Every employee is requested to choose a password during his/her registration.
Later the employee Logs in for performing his activities. The following is the snippet showing the EAL’s Log-In page:



