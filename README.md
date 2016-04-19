# Yet another html numeric input, hope it's awesome
A textbox only allows visitor to type numeric, dot, and minus sign. This will replace the half-ass HTML5 input type=number.

 - Support positive and negative number
 - Support decimal number (default is dot).
 - While user typing, it will remove all decimalSeparator that have other decimalSeparator following. After this processing, only the last decimalSeparator is kept.
 - This is vanilla JS, no library required
 - Tested on Chrome, Firefox, IE10, IE11
 - Tested on Windows, the keycodes is taken from http://keycode.info

# How to use
Call toHtmlNumericInput('num');
Call toHtmlNumericInput('num', true);   // if you want to use comma as decimal separator

A working sample and how to use in action is here https://rawgit.com/lockevn/html-numeric-input/master/index.html