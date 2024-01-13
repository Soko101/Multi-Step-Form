# Multi-Step-Form
Simple Multiple step login page

HTML (index.html):

The HTML file defines the structure of the form and includes three form sections wrapped inside a <div class="container">.
Each form section represents a step in the multi-step process.
The <button> elements inside each form section allow users to navigate between steps or submit the form.
A progress bar is defined using a <div> with the id "progress" and small steps indicators to display the current step.

CSS (style.css):

The CSS file defines the styling for my multi-step form and its components.
It includes styling for form elements, buttons, layout, backgrounds, fonts, and the progress bar.
It controls the positioning of form sections to make them visible or hidden based on user interactions.

JavaScript (index.js):

JavaScript handles the interactivity of your multi-step form.
It uses DOM manipulation to control the visibility and positioning of form sections.
Event listeners are attached to buttons (next1, back1, next2, back2) to manage the progression between form steps.
The progress bar's width is adjusted to reflect the current step's progress.
When the user submits the final step, you can add functionality to process the form data or perform other actions.
The overall flow of your multi-step form is as follows:

Initially, only the first form section is visible.
Users click the "Next" button to proceed to the next step (next1, next2).
Users click the "Back" button to return to the previous step (back1, back2).
The progress bar visually indicates the current step.
After completing all steps, users can submit the form.
Overall, this architecture provides a structured and user-friendly way to guide users through 
a multi-step registration process.
