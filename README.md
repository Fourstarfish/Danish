# CSC207-Project-Group-262
## Problem Domain: HR System
Our Team is currently looking to develop a software that alleviates the hassle of maintaining Human Resource system within the administrative body of the University of Toronto.

## Description of Application
- Access to a calendar which shows which roles are missing from lectures and labs.
- Request for leave button that notifies others with the same role (Prof, TA) and asks if there is anyone willing to fill for them by sending it to an announcements page.
- A feature which allows the user to see whether a particular day is a public holiday, for which leaves would not be necessary.

## Link to API Documentation used
- https://developers.google.com/calendar/api/v3/reference/events
- https://calendarific.com/api-documentation

## Screen shot of tool for trying API
https://i.postimg.cc/zBJ4bL6q/Screenshot-2023-09-29-at-7-52-06-PM.png
## Example of running our code
`joe.requestLeave('10/13/2023')`

Example #2: Email Verification
{
    "email": "yoohamj@gmail.com",
    "autocorrect": "",
    "deliverability": "DELIVERABLE",
    "quality_score": "0.95",
    "is_valid_format": {
        "value": true,
        "text": "TRUE"
    },
    "is_free_email": {
        "value": true,
        "text": "TRUE"
    },
    "is_disposable_email": {
        "value": false,
        "text": "FALSE"
    },
    "is_role_email": {
        "value": false,
        "text": "FALSE"
    },
    "is_catchall_email": {
        "value": false,
        "text": "FALSE"
    },
    "is_mx_found": {
        "value": true,
        "text": "TRUE"
    },
    "is_smtp_valid": {
        "value": true,
        "text": "TRUE"
    }
}


## List of Technical Problems
- Calendarify API only allows 500 API Calls per month. We don't foresee this being a massive problem, but it's something
to keep in mind.

