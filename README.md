Granite Radios
==============

Demo for a CSS-only ADC 2.0 proposal for single questions.

Preview
-------

[Preview of Granite radios](https://raw.githubusercontent.com/AskiaADX/demo-GraniteRadios/master/GraniteRadio-demo.gif)

Possible variables to be open to the end-users
----------------------------------------------

-	Radio outer circle background gradient
-	Radio inner circle background gradient
-	Radio tick color
-	Response item color for hover and active states

I would *not* open the checkbox or tick sizing to end-users as it would oblige them to fiddle around with positioning.

Known issues
------------

This demo was successfully tested in Chrome, Firefox, Safari, Opera and IE9+. Because it relies on CSS transforms for the check (tick) of the control, you will need to add a conditional tag for < IE9 that will display the default checkbox instead.
