# Student Enrollment Form using JsonPowerDB

## Description

This project is a Student Enrollment Form created using HTML, CSS, Bootstrap, JavaScript, and JsonPowerDB.

The form stores student information in the STUDENT-TABLE relation of SCHOOL-DB database.

The Roll Number works as a primary key. The application checks if a student record already exists:
- If Roll Number is new, the user can save student details.
- If Roll Number exists, existing data is displayed and can be updated.

## Student Fields

- Roll Number
- Full Name
- Class
- Birth Date
- Address
- Enrollment Date


## Benefits of using JsonPowerDB

- Simple and easy to use
- Serverless database
- Fast performance
- Lightweight
- Schema-free database
- Uses JSON format for storing data
- Provides REST API support
- Reduces development time
- Easy integration with JavaScript


## Scope of Functionalities

### Save Student Record
Adds a new student record into JsonPowerDB using PUT command.

### Fetch Existing Record
Searches student data using Roll Number with GET_BY_KEY command.

### Update Student Record
Updates existing student details using UPDATE command.

### Reset Form
Clears the form and restores the default state.


## Technologies Used

- HTML
- CSS
- Bootstrap
- JavaScript
- jQuery
- JsonPowerDB


## Database Information

Database Name:

```
SCHOOL-DB
```

Relation Name:

```
STUDENT-TABLE
```


## Example Record

```json
{
    "Roll_No":"1",
    "Full_Name":"Student Name",
    "Class":"12",
    "Birth_Date":"2005-01-01",
    "Address":"Delhi",
    "Enrollment_Date":"2026-06-07"
}
```


## Release History

### Version 1.0.0

Initial release of Student Enrollment Form.

Features added:
- JsonPowerDB connection
- Insert student data
- Retrieve student data
- Update student data
- Form validation


## Project Status

Completed.


## Sources

- JsonPowerDB Documentation
- Bootstrap Documentation
- Login2Xplore Learning Resources
