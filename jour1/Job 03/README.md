# Job 03 - Creating a Form in HTML

In this task, you created an HTML page with a form containing various input fields like text, password, checkbox, radio buttons, and a submission button.

### Questions:

1. How are the `name` attributes of form fields used during form submission?

   - The `name` attributes of form fields play a vital role during form submission. They are used to identify and associate the values entered by the user with specific fields. When the user submits the form, the browser sends the data to the server using the `name` attribute as the key and the user-entered value as the corresponding value. This allows server-side scripts to process and handle the form data accurately.

   - For example, if you have a text input field with the `name` attribute set to "user_name," and the user enters their name as "John," during form submission, the browser sends the data as "user_name=John." The server can then access this data using the "user_name" key to perform further actions.

2. How are different input types (text, password, checkbox, radio) typically used in web forms?

   - Text Input: Text input fields (`<input type="text">`) are used for capturing single-line text input from users, such as names, email addresses, or search queries.

   - Password Input: Password input fields (`<input type="password">`) are used to securely collect sensitive information, such as user passwords. The entered characters are often masked for security purposes.

   - Checkbox: Checkboxes (`<input type="checkbox">`) allow users to select multiple options from a list. They are typically used when users can choose multiple items from a set of options.

   - Radio Buttons: Radio buttons (`<input type="radio">`) are used when users need to select a single option from a list of mutually exclusive choices. Users can only choose one option within a group of radio buttons.
