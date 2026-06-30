Project Name: Madrasah Management Website

This website will be a comprehensive Madrasah Management System designed to manage student records, student fees, teacher information, teacher salaries, and the overall financial activities (income and expenses) of the madrasah. In short, it will maintain complete records of students, teachers, and the institution's financial management through a web application.

1. Dashboard Layout

The application will have a dashboard-style interface with:

A left sidebar for navigation.
A top header on the right.
The remaining area will display the main content based on the selected menu. 2. Sidebar Menu

The sidebar will contain the following menu items:

Overview
Play
Nursery
One
Two
Three
Four
Hifz
Teachers

Selecting a menu item will display the corresponding data in the main content area.

3. Authentication

There will be no public registration page. Only the Admin will be able to log in and register new students or teachers.

4. Student Registration Form

The student registration form will include the following fields:

Student's Name (Bangla)
Student's Name (English)
Mother's Name (Bangla)
Mother's Name (English)
Father's Name (Bangla)
Father's Name (English)
Date of Birth (using a Date Picker)
Birth Certificate Number
Father's Mobile Number
Mother's Mobile Number
Guardian's Mobile Number (the person responsible for bringing the student to and from the madrasah)
Class (Dropdown containing all available classes)
Gender (Dropdown)
Religion (Dropdown)
Blood Group (Dropdown)
Nationality (Dropdown)
Present Address
Permanent Address
Student Photo Upload
A confirmation checkbox stating that all the provided information is accurate. 5. Student Fee Management

The application should also support student fee collection.

The process will be as follows:

Select a student from the student list.
Choose the payment month from a dropdown menu.
Record the student's fee payment for the selected month.

<!-- Madrasah Harmony Hub ভার্সনের জন্য কিছু আপডেট রিকুয়ারমেন্ট -->

1. Student Monthly Fee

There should not be a fixed monthly fee based on the student's class. Instead, the monthly fee will be determined individually at the time of admission.

Therefore, the Student Registration Form should include an additional input field named "Monthly Fee", where the student's agreed monthly fee can be entered.

2. Teacher Management

The Teachers section requires the following enhancements:

2.1. Teacher Registration

Add a Teacher Registration Form to allow the admin to register new teachers.

2.2. Delete Teacher

Provide functionality to delete a teacher from the system if they leave the madrasah.

2.3. Teacher Salary Payment

Similar to the student fee collection system, there should be a feature to record teacher salary payments.
The admin should be able to select a teacher, choose the salary month from a dropdown list, and record the salary payment for that month. 3. Search Functionality

The search box is currently not working. It needs to be fully functional so that users can search and filter records properly.
