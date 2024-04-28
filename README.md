# **User Interface Specification Document**  

## Introduction  
The user management screen is a tool to allow adminstrators to manage the users in the system. Details and the requirements of the UI is specified below.

## Requirements  
- Display a list of users with their information.  
- Allow admins to add a new user and save their information to the system
- Give ability to edit the user information to the admins.
- Make an option to enable and disable users.
- Provide a sorting, filtering and searching option to quickly access users information.
- Make sure the system is accessible, interactive and dynamic for different devices.

## UI Elements

### User List
- Display users with their information in a table with columns for `ID`, `Username`, `Email`, `Enabled`.
- Allow the sorting of the list such as ascending or descending `ID`, alphabetical for `Username`, ***true*** or ***false*** for `Enabled`. Make an option to `Hide disabled users` for ease of visibility.
- `Search` option for accessibility.

### User Form
- Include input lines for `Username`, `Display Name`, `Phone`, `Email` and dropdown menu for `User Roles`. 
- Check the the validity of the input lines such as emails being unique and phones being certain length. 
- `Enable` box to active or deactive the user.
- `Save User` option to save the information to the system.

## Page Behavior
- Upon inital load, display the list of users with a default sorting that might be ascending id. If no users are present display a message indicating there are no registered users.
- Include buttons to create a `New User` and save the information.
- Include options on each row of users to edit or delete the information of the user.
- Update the user list dynamically when making changes without refreshing the page.
- Give feedback message when a change is made.
- Allow for a report option to notice the devs in case of an encounter of a bug or a problem. 

## Accessibility
- Ensure all the UI elements are accessible and readable for all devices.
- Allow keyboard shortcuts for the ease of access.
- Sufficient color contrast for text and background for readability.
- Allow the change of font size, background and text color, narrowing or widening of the columns.
- Localization for other languages.

## Change History
- Include the history of changes and new features made to prior versions and show the current version.

## Review and Approval
- Design and functionality should be reviewed and approved by stakeholders
- Allow for a feedback and revisions on stakeholder input.
