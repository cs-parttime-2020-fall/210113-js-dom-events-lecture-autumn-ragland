# 21 01 13 JS DOM Events Lecture

## Set Up
HTML, CSS, and JS files have been provided for this assignment.

## Lecture
Event Handlers
1. Add an onClick event listener to the button in the first div that calls the function alertMessage along with the id alertMessage.
1. Define a function alertMessage that alerts the message "You clicked the first button".

On Click Event Listeners to Alert
1. Select the first button using query selector.
1. Add an event listener that calls the function alertMessage on click.
1. Remove the event listener that calls the function alertMessage on click.

On Click Event Listeners to Update Styling
1. Select the body using query selector.
1. Select the second button using query selector.
1. Add an event listener that updates the background color of the body to #7A93AC.
1. Define an arrow function updateBackground that adds the shadowBlue css class.
1. Refactor the previous event listener to call the function updateBackground on click.

Key Press Event Listeners 
1. Select the textarea using query selector.
1. Select the heading of the third div using query selector.
1. Define an arrow function updateDisplayText that accepts one parameter, event, and sets the innerText of the heading to the value property of the target property of the event.
1. Add an event listener to the textarea that calls the updateDisplayText function on key press.
1. Refactor the function updateDisplayText to set the innerText of the heading to the value property of the textarea.
1. Refactor the event listener to call the function on key up.

Mouse Over Event Listeners
1. Select the fourth div using query selector
1. Add an event listener that alerts the message "This div is off limits" on mouse over.
1. Add an event listener that updates the text of the heading in the fourth div to "THIS DIV IS OFF LIMITS" on mouse enter.
1. Add an event listener that updates the text of the heading in the fourth div back to "Stay Out!" on mouse leave.

Toggle Attributes with Event Listeners
1. Select the text input using query selector.
1. Select the third button using query selector.
1. Add an event listener that toggles the disabled attribute on the text input when the button is clicked
---
1. Select the hidden p element using query selector.
1. Select the fifth button using query selector.
1. Define a function updateSecretMessage that toggles the hidden attribute on the p element.
1. Add an event listener that calls the updateSecretMessage function on click.
1. Refactor the updateSecretMessage function to log "HIDDEN" if the p element is currently hidden or "NOT HIDDEN" if the p element is not currently hidden using getAttribute


