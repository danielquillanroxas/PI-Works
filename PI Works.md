
# Page User Interface Specification Document
 ### The page is divided into 3 main parts: `Header`, `lower-left side`, and `lower-right side`.
 ### The `lower-left side`, and `lower-right side` have equal areas.

## Page Header
#### This page section contains the `+New` button and `Save User` button
#### It has a light grey background.
**"+ New" Button** 
- This button is located on the top-left part of the page.
- When the user clicks this button, a new form will be output on the `lower-right part` of the page.
- This button has a bright blue color and a rectangular shape.

**"Save User" Button** 
- This button is located on the top-right part of the page.
- The button is initially deactivated but turns clickable when the user finishes the user information form.
- This button has a bright blue color after the form is filled.

## Lower-left side
### This part displays the User Table
#### This part has a white background

**User Table**
- This section displays 4 columns and n rows.
- The four columns are: `ID`, `Names`, `Emails`, `Enabled`.
- Next to each column label is a `sort` button. When a user clicks this, the data is sorted alphabetically or numerically.
- It displays the user names, emails, and whether it is 'enabled' or 'disabled'.
- Rows change color to light blue from the normal grey color when the cursor hovers it.
- The new user will be displayed here when the form-filling is done on the `lower-right side` of the page.

## Lower-right side
### This part displays the form to be filled to add a new user.
#### This part has a white background.



**User Form** 
- The first text of this section is `"New User"` as the header. It has a grey background.
- This part displays labels for: `User Name`, `Display Name`, `Phone`, `Email`, `Enabled`. Arranged from top to bottom respectively.
- To the right of each label is a textbox for users to enter information.
- For `User Roles`, when the textbox is clicked, a dropdown menu is displayed with options: `Guest`, `Admin`, and `SuperAdmin` in the same order.
- The `enabled` label has a tickbox next to it instead of a textbox.
- When all the boxes are filled, the `Save User` button is activated and the data input are displayed onto the `User Table` part of the page.
