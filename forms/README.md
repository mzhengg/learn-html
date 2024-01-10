## Getting Started

<!-- - Install the version of Node JS for your OS https://nodejs.org/en/download -->
<!-- - From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number. -->
<!-- - In the terminal install dependencies using the command:
    `$ npm install` -->
<!-- - In the terminal run the local server using the command:
  - `node form-server.js` -->
<!-- - Open "form.html" in a browser. Enter username and password and click "Submit". -->

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
  - The URL that processes the form submission

2. What is the purpose of the _method_ attribute in the _form_ tag?
  - The HTTP method to submit the form with. The only allowed methods/values are:
    - POST: form data sent as the request body.
    - GET (default): form data appended to the action URL with a ? separator.
    - DIALOG: when the form is inside a <dialog>, closes the dialog and causes a submit event to be fired on submission, without submitting data or clearing the form.

3. What is the purpose of the _name_ attribute in the _input_ tag?
  - It is the name of the form control that is submitted with the form as part of a name/value pair

4. What is the purpose of the _type_ attrbute in the _input_ tag?
  - It specifies the type of information that the input object should recieve - type of form control

5. What is the purpose of the _label_ tag?
  - It displays a caption for an item in a user interface.

6. What is the purpose of the _required_ attribute?
  - Specifies that a value is required or must be checked for the form to be submittable