# Web Development Techdegree - Project 03 #
 
## Responsive Registration Form ##

### Project Instructions ###

* [X] For this project we will be checking the design in Google Chrome version 48 or higher. Different browsers display forms slightly differently so please make sure it looks         correct in Google Chrome before submitting.

* [X] Build the layout using a mobile first design:
  * Make sure the HTML file includes the viewport meta tag in the head of the document.
  * Look at the provided mockup (mobile-form.png) and add the same content to your index.html file.

* [X] Create the form structure:
  Only use one `<form>` tag. The `<form>` tag should contain all the form elements. Add a fieldset and legend for each of the following sections:
  * "Contact Information" section of the page, and
  * The "Newsletter" section of the page

* [X] Make sure you include the following form field types:
  * text input
  * email input
  * telephone input
  * select menu
  * checkboxes
  * radio buttons
  * textarea
  * submit button

* [X] Form fields should include the following attributes:
  * `input`: should include `id`, `type` and `name` attributes.
  * `select` and `textarea`: should include `id` and `name` attributes.

* [X] Add labels to each form element using the HTML `<label>` tag. The text inside the labels should match the names of the form fields in the mockups.
  * Make sure you properly pair each `<label>` element with its corresponding form control via the `for` attribute. Don't forget about the textarea element. That needs a             functioning label too.

* [X] Use the input field's `placeholder` attribute to add the text "required" to:
  * the Full Name field
  * the Email address field

* [X] Once you have everything in place for the mobile layout, use a media query to add a breakpoint to adjust the layout for wider tablet and desktop screens.
  * Match the design as it should look on a tablet or desktop that is 768px wide using the desktop-form.png mockup.
  * Use a mobile-first approach by writing your media queries using the `min-width` property in your CSS.

* [X] Once all your breakpoints are in place, double check your layout matches both the mockups.
  * Mobile: Text should be above the form field.
  * Desktop: Text should be to the left side of the form field.

* [X] Use a Google Font for the text. The design uses the "Merriweather" font but, you can use any Google Font that you'd like.

* [X] Add `:focus` states to the form for when a user clicks or tabs into a text field.

### Extra Credit ###

* [X] Additional placeholder text for other text fields.

* [X] Use the `required` attribute to add HTML5 validation to make sure that required fields are filled out and input is formatted correctly.

* [X] Add at least the following additional styling enhancements to the form, feel free to add extra styling but leave the basic layout the same as the mockup.
  * Change the background color for at least ONE of the main sections of the site.

* [X] Uses CSS transitions for focus states.
  * For example, make a background color fade into view when the user clicks on a text field, and fade out when the user clicks or tabs out of the field.
