### Form Structure:
* 'form' :Form controls live inside a 'form' element.
* 'input': The 'input' element is used to create several different form controls.
* 'textarea' :The 'textarea' element is used to create a mutli-line text input.
*  type="radio" : Radio buttons allow users to pick just one of a number of options.
* 'select' :A drop down list box (also known as a select box) allows users to select one option from a drop down list.
* 'option' :The 'option' element is used to specify the options that the user can select from.
* 'button' : this element was introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button.
* 'label' :When introducing form controls,the code was kept simple by indicating the purpose of each one in text next to it.
* fieldset :You can group related form controls together inside the 'fieldset' element.
### Information from a form is sent in name/value pairs.
### HTML5 introduces new form elements which make it easier for visitors to fill in forms.

## Table Properties:
* width
* padding
* text-transform
* letter-spacing, font-size
* border-top, border-bottom
* text-align
* background-color
* :hover
* collapse
* separate

#### Forms are easier to use if the form controls are vertically aligned using CSS.
#### Forms benefit from styles that make them feel more interactive.

#### USER INTERFACE EVENTS:
* 
### EVENT TRIGGER :
* input Fires when the value of an 'input' or textarea element changes. First supported in IE9 (although
it does not fire when deleting text in IE9). For older browsers, you can use keydown as a fallback.
keydown Fires when the user presses any key on the keyboard. If the user holds down a key, the event
continues to fire repeatedly. This is important because it mimics what would happen in a text input
if the user holds down a key (the same character would be added repeatedly while the key is held
down).
* keypress Fires when the user presses a key that would result in a character being shown on the screen. For
example, this event would not fire when the user presses the arrow keys, whereas the keydown event
would. If the user holds down a key, the event continues to fire repeatedly.
keyup Fires when the user releases a key on the keyboard. The keydown and keypress events fire before a
character.

### You can use event delegation to monitor for events that happen on all of the children of an element.

