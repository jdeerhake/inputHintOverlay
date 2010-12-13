inputHintOverlay
================
v1.1.10  
9/21/2010

About
-----
A jQuery plugin that overlays input labels as hints to a form. It uses the title tags on each input/textarea as the label values/hints. It is called it on the form (or any parent).
    $(form).inputHintOverlay()

Why use overlay instead of setting the value? This allows validation to work correctly and prevents the user from accidently submiting erroneous data.

Arguments to this method are adjustments to top and left of the fixed position of each overlay div. The folling would push each hint down 2px and right 5px.
    $(form).inputHintOverlay(2, 5)
The class .inputHintOverlay can be used to style the hints (label.inputHintOverlay) and the div wrapper around the label/input (div.inputHintOverlay).


For more visit the [project site](http://jdeerhake.com/inputHintOverlay.php).
