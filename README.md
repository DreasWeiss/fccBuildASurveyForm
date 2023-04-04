# fccBuildASurveyForm
FreeCodeCamp cert-task for (New) Responsive Web Design

## Build a Survey Form

Objective: Build an app that is functionally similar to https://survey-form.freecodecamp.rocks

User Stories:

- You should have a page title in an h1 element with an id of title
- You should have a short explanation in a p element with an id of description
- You should have a form element with an id of survey-form
- Inside the form element, you are required to enter your name in an input field that has an id of name and a type of text
- Inside the form element, you are required to enter your email in an input field that has an id of email
- If you enter an email that is not formatted correctly, you will see an HTML5 validation error
- Inside the form, you can enter a number in an input field that has an id of number
- The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
- If you enter numbers outside the range of the number input, which are defined by the min and max attributes, you will see an HTML5 validation error
- For the name, email, and number input fields, you can see corresponding label elements in the form, that describe the purpose of each field with the following ids: id="name-label", id="email-label", and id="number-label"
- For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field
- Inside the form element, you should have a select dropdown element with an id of dropdown and at least two options to choose from
- Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the name attribute
- Inside the form element, you can select several fields from a series of checkboxes, each of which must have a value attribute
- Inside the form element, you are presented with a textarea for additional comments
- Inside the form element, you are presented with a button with id of submit to submit all the inputs
- Fulfill the user stories and pass all the tests below to complete this project. Give it your own personal style. Happy Coding!

Note: Be sure to add <link rel="stylesheet" href="styles.css"> in your HTML to link your stylesheet and apply your CSS


## Tests
- [x] You should have an h1 element with an id of title.
- [x] Your #title should not be empty.
- [x] You should have a p element with an id of description.
- [x] Your #description should not be empty.
- [x] You should have a form element with an id of survey-form.
- [x] You should have an input element with an id of name.
- [x] Your #name should have a type of text.
- [x] Your #name should require input.
- [x] Your #name should be a descendant of #survey-form.
- [x] You should have an input element with an id of email.
- [x] Your #email should have a type of email.
- [x] Your #email should require input.
- [x] Your #email should be a descendant of #survey-form.
- [x] You should have an input element with an id of number.
- [x] Your #number should be a descendant of #survey-form.
- [x] Your #number should have a type of number.
- [x] Your #number should have a min attribute with a numeric value.
- [x] Your #number should have a max attribute with a numeric value.
- [x] You should have a label element with an id of name-label.
- [x] You should have a label element with an id of email-label.
- [x] You should have a label element with an id of number-label.
- [x] Your #name-label should contain text that describes the input.
- [x] Your #email-label should contain text that describes the input.
- [x] Your #number-label should contain text that describes the input.
- [x] Your #name-label should be a descendant of #survey-form.
- [x] Your #email-label should be a descendant of #survey-form.
- [x] Your #number-label should be a descendant of #survey-form.
- [x] Your #name should have a placeholder attribute and value.
- [x] Your #email should have a placeholder attribute and value.
- [x] Your #number should have a placeholder attribute and value.
- [x] You should have a select field with an id of dropdown.
- [x] Your #dropdown should have at least two selectable (not disabled) option elements.
- [x] Your #dropdown should be a descendant of #survey-form.
- [x] You should have at least two input elements with a type of radio (radio buttons).
- [x] You should have at least two radio buttons that are descendants of #survey-form.
- [x] All your radio buttons should have a value attribute and value.
- [x] All your radio buttons should have a name attribute and value.
- [x] Every radio button group should have at least 2 radio buttons.
- [x] You should have at least two input elements with a type of checkbox (checkboxes) that are descendants of #survey-form.
- [x] All your checkboxes inside #survey-form should have a value attribute and value.
- [x] You should have at least one textarea element that is a descendant of #survey-form.
- [x] You should have an input or button element with an id of submit.
- [x] Your #submit should have a type of submit.
- [x] Your #submit should be a descendant of #survey-form.
