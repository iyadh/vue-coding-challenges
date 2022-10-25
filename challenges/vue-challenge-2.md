# Vue Challenge #2

In this challenge, you were asked to debug and refactor a small form, that includes inputs for user’s basic data.

### Requirements
Here are the requirements that you received:

-   The form should have three inputs (“First name”, “Last name” and “City”)
-   First and last name inputs should be required (using the  [“required”](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/required)  attribute), city input should be optional.
-   When the user focuses on any input in the form, the form border should change colour to indicate that the user is actively filling the form.

You went straight into the code and created a reusable BaseInput component that was a simple wrapper component for an input element. You wrapper the component in a <label> tag to include the label.

One of the requirements was also that when the input is focused the border of the form changes its colour to indicate that the user is actively filling the specific section of the form.

You used @focus and @blur events on the component to toggle the focused property that then applied a proper CSS class when true.

Then you realised that wrapping the BaseInput with a <label> was not very reusable and you decided to refactor the component and move <label> into the component itself.

You finished the refactor, now the component accepts a label property that is used to render the label inside the component.

You test the new component, and… something is wrong. The border is not changing its colour when to focus on the input anymore. Also you can submit the form without filling the required fields.

Go through the code and find what needs to be changed to get the component working properly.


### Starter StackBlitz
Please fork this link on [StackBlitz](https://stackblitz.com/edit/vitejs-vite-gwvmur)
