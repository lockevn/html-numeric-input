# Yet another html numeric input, hope it's awesome

A textbox only allows visitor to type numeric, dot, and minus sign. This will replace the half-ass HTML5 input type=number.
 
 - Allow positive and negative number
 - Allow decimal number (with default decimalSeparator is the dot)
 - While user typing, it will remove all decimalSeparator that have other decimalSeparator following. After this processing, only the last decimalSeparator is kept.
 - This is vanilla JS, no other library required
 - Tested on Chrome, Firefox, IE10, IE11
 - Tested on Windows, the keycodes is taken from http://keycode.info

 
# What do I provide?

This is just a JS function <code>toHtmlNumericInput(string, bool)</code>. Copy it to your page and that's all.


# How to use
Call `toHtmlNumericInput('num');`     // by default, DOT is the decimalSeparator, you can type "123456.789"
Call `toHtmlNumericInput('num', true);` // if you want to use COMMA as decimalSeparator, you can type "123456,789"

A working sample and how to use in action is here https://rawgit.com/lockevn/html-numeric-input/master/index.html