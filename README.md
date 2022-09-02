# P.I.-Works-Inc-Interview-Question
P.I. Works, Inc Interview Question - the user interface specification document <br/>

## QUESTION <br/>
Please prepare the user interface specification document in English for the user management screen below (Markdown syntax preferred). It should include the requirements, details related to UI components, the behavior of the page when using these components, what to show to the user at the beginning, etc. This document will be used by Software developers who will develop this user interface. <br/>

![the user management screen](https://github.com/RecepFatih/P.I.-Works-Inc-Interview-Question/blob/main/question.png) <br/>

## ANSWER <br/>

* When the screen is first turned on; <br/>
  *    There should be a "New User" button in the upper left corner. <br/>
  *    There should be a "Hide Disabled User" option next to the "New User" button. <br/>
        *    If this option is enabled, users will be hidden. <br/>
    * Users registered in the system should appear on the screen.  <br/>
    * If the "New User" button is pressed, 
      * A place to enter the "New User" information will appear on the right side of the screen.   <br/>
      * There will be a "Save User" button in the upper right corner of the screen.   <br/>
      * *Information required for "New User";    <br/>
        * Username
        * Display Name
        * Phone
        * Email
        * User Roles, It will be selected from the options that appear on the screen. Options;
            * Guest
            * Admin
            * Super Admin
        * All fields must not be blank
      * When all information is entered, the user can be registered with "Save User" button.
* After saving, the "New User" area is closed and the screen looks like it was first opened.
