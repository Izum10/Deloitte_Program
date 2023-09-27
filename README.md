# IB-Computer-Science-IA
IB Computer Science Internal Assessment

**Time Sheets/ Data Calculations**

**Defining the Problem**

My client, Mr. W is an auditor working at multinational accounting organization, Deloitte. He is currently
stationed in Bahrain and is responsible for analyzing his staff’s time sheets as well as distributing and
calculating their chargeable hours per day. He wants to find an easier way to tackle this task as it just adds
onto his hectic workload. To date, his approach towards tackling this task involves checking up on each
individual staff member and collecting their time sheets manually. He then has to distribute and calculate
their chargeable hours by hand. He wants a software in which “employees can log in their individual time
sheets and hour distribution manually, through which I can then receive all organized and calculated.”.

We first came in contact in April, 2019 when I was doing an internship at Deloitte’s Dubai office. When
we were first introduced to the IA and were told to find clients in regards to their repetitive tasks, I
immediately thought of auditing as through personal experience the job entails multiple repetitive tasks.

I decided to set up an interview with Mr. W in order to fully analyze his problem and gain his insight on
how he would like the software to run in convenience on his side.

**Rationale for Proposed Solution**

I decided that choosing an online system would be the best solution in regards to Mr. W’s problem as it
would make the whole process more efficient. Additionally, I chose MySQL to store the data due to its
clear and straightforward design making it easy for office users to comprehend the data, and because of
MySQL’s intended purpose of making data management more efficient to home and professional users.

I believe through the use of MySQL, html and php, I can create a web system complex yet simple enough
for office users to understand and operate. Through MySQL I can separate employees apart from each
other by separating them into multiple databases or tables. Furthermore, through the use of php I can
create a connection to the MySQL server allowing the user to edit data easily whilst it all gets inputted
into the database. It also allows me to create code which can pre-calculate the hour distribution alongside
creating an organized table for each employee. Additionally, php and html allow for the software to
become web based making it more convenient in regards to the user’s accessibility.

**Stating Success Criteria**
- Program should include a login form (For protection) which allows users to access the
web-system.
- Program should have different redirects for managers and employees after login.
- Managers should be able to:
- View employee data (Time Sheets) on different dates all pre-calculated.
- Input new employees into database.
- Employees should be able to:
- Input data (Time Sheets) into database.
- View their own data and profile.
- Program should provide a very straightforward user interface which requires no employee
training by the company.
- Program should display text either confirming or warning users after input of data.
