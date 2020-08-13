<p>
  <strong>Purpose:</strong><br> 
  You are going to learn basic form validation and event handling in JavaScript.
</p>

<p>
  <strong>Requirements:</strong><br>
    To complete this project you will write and submit one HTML file containing embedded CSS (optional) and JavaScript (not optional). The file will be called lab1.html. This file contains a registration form, which can be styled any way you like subject to the requirements below.<br>
  This single submission file lab1.html must be an ASCII file (i.e. a plain text document with a .html extension). You may create it with any editor but you must ensure that it is a text file. In other words, it should not contain anything except ASCII characters (including HTML tags/CSS rules/JavaScript and content).
</p>

<p>
  This lab will be a simple registration form. Every visible form input should be labeled with explanatory text (like “Username:” or “Enter Message Here…”). The form should have the following inputs:
  <ul>
  <li><strong>Username</strong> <em>(a text field)</em></li>
  <ul>
    <li>The user should enter only letters in this field, or the entry is invalid</li>
  </ul>
  <li><strong>Password </strong><em>(a password field, <input type=”password”>)</em></li>
  <ul>
    <li>The user should enter a password containing a mix of upper-­case and lower-­ case letters and numbers (at least one of each, or the entry is invalid). Other characters are allowed but optional.</li>
  </ul>
  <li><strong>Student ID number </strong><em>(a text field)</em></li>
  <ul>
    <li>The user should enter a 9 digit number. No letters are allowed or the entry is invalid.</li>
  </ul>
  <li><strong>Message </strong><em>(a textarea)</em></li>
  <ul>
    <li>The user may enter up to 25 words (note: not characters!).</li>
    <li>The field should be disabled if 25 words are entered, such that no other words can be typed into the textarea. This can be accomplished a few different ways.</li>
    <li>Text next to the field should count down from 25 to 0 as the user enters words.</li>
    <li>The string split() method can be used with a single space “ “ delimiter, or with a regular expression to capture all white space. This is up to you. Both are considered correct.</li>
  </ul>
  <li>Submit (a button input type, or a submit input type if you can <strong>get this to work without actually submitting the form</strong>)</li>
</ul>
</p>
<br>
  When the user presses the Submit button, the form is checked…<br>
  <strong><u>FOR VALID FORMS</u></strong>
  <p>If the form is valid (i.e. abides by the rules above), then an easy-­to-­see message should be tastefully displayed at the bottom of the screen in its own div. Nothing else should be displayed in this div. While the user is filling out the form, this div should be empty (have no text). This message can say, for example: “SUCCESS!” <strong>Again, the form should not actually be submitted!</strong>
  </p>
<strong><u>FOR INVALID FORMS</u></strong>
  <p>If the form is invalid, the page’s background should change color (this can be accomplished with a div that encloses all other content, if you like), and error text should be added to the page (previously invisible/not displayed) that details all the current errors. The error text should stand out and be colored differently than any other elements on the page. (You may change the class attribute of the error text and body/div elements using JavaScript to accomplish this effect, where the classes are defined in embedded CSS, also located in the <head> section, like the JavaScript code, see below….) Everything invalid about the form entries should be displayed as error text.
  </p>
