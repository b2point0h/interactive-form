Build an Interactive Form
================================

## Requirements

- [X] Set focus on the first text field. When the page loads, give focus to the first text field

- [X] Reveal a text field when the "Other" option is selected from the "Job Role" drop down menu. Make sure you add an text input field. Use the id of "other-title" for the field. Add placeholder text of "Your Title" for the field

- [X] For the T-Shirt color menu, only display the options that match the design selected in the "Design" menu.

- [X] If the user selects a workshop, don't allow selection of a workshop at the same date and time -- you should disable the checkbox and visually indicate that the workshop in the competing time slot isn't available.

- [X] When a user unchecks an activity, make sure that competing activities (if there are any) are no longer disabled.

- [X] As a user selects activities to register for, a running total is listed below the list of checkboxes. For example, if the user selects "Main conference" then Total: $200 should appear. If they add 1 workshop the total should change to Total: $300.

- [X] The "Credit Card" payment option should be selected by default and result in the display of the #credit-card div, and hide the "Paypal" and "Bitcoin information.

- [X] When a user selects the "PayPal" payment option, display the Paypal information, and hide the credit card information and the "Bitcoin" information.

- [X] When a user selects the "Bitcoin" payment option, display the Bitcoin information, and hide the credit card information.

- [X] Display error messages and don't let the user submit the form if any of these validation errors exist:
- Name field can't be empty
- Email field must be a validly formatted e-mail address (you don't have to check that it's a real e-mail address, just that it's formatted like one: dave@teamtreehouse.com for example. You'll need to use a regular expression to get this requirement. See the list of Resources for links to learn about regular expressions.
- At least one activity must be checked from the list under "Register for Actitivities."
- Payment option must be selected.
- If "Credit card" is the selected payment option, make sure the user supplied a credit card number, a zip code, and a 3 number CVV value.


## Extra Credit

- [X] Hide the "Color" label and select menu until a T-Shirt design is selected from the "Design" menu.

- [X] Style the "select" menus (drop down menus) on the form, so they match the styling of the text fields (see Resources links for an article on how to improve the look of select menus using CSS and JavaScript).

- [X] Validate the credit card number so that it's a validly formatted credit card number. (see the Resources links for information on how to do this.)

# View Project
[Live Demo](http://re-brand.us/projects/interactive-form/index.html) of this project for peer review.