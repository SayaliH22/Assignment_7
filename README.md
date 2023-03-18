# Assignment_7
Description: Used a Sass/scss in a two page website.

Sass/Scss Used:
1) Variables: Used an $primarycolor and $secondarycolor for reusing the naming convention.

2) Mixin: Used mixin for creating CSS code that was reused throughout the website. It was used for container.

3) Function: Used function for setting the font color to black if background is of light color ,
	     else if the background color is dark then the color is set to white. 

4) Nesting: Nesting was done inside the navigation tab.

5) Import: @import was used to include the content of one file in another. Here we imported 'config', 'mobile', etc files.

6) Extend: Here we extended @extend btn which shared a set of CSS properties from one selector to another.

7) Selector :The parent selector, &, is a special selector invented by Sass that’s used in nested selectors to refer to the outer selector. It makes it possible to re-use the outer selector in more complex ways, like adding a pseudo-class or adding a selector before the parent.

8) Interpolation: Interpolation can be used almost anywhere in a Sass stylesheet to embed the result of a SassScript expression into a chunk of CSS

-- Variables in CSS
Prefixed with $
$primary-color: blue

-- Nesting

Instead of writing parent class name again and again, we can include all child classes of particular parent class
under respective parent class writing once

-- Modules
We can break css in separate files and bring them into one main css file
_filename.scss : writing _ will not compile the file. 
you can use those modules using @use keyword in another sass file
@use 'filename'


-- Mixins
It is just like the function which takes a parameter where value could be css property
You can place css inside mixin and use parameter value to assign it to different css properties
To use mixins we need to use keyword @include

-- functions
Functions work same as mixins, but the only difference is that they return something


-- Inheritance
There are cases where we have similar styles to some components except few extra styles. For that we need to write similar 
lines of css again and again
To avoid that we can use inheritance 
You can create one block of similar properties and extend that in the different classes where you want the similar styles

-- Operators
It can be used to make calculations
You can write formula for your css property

-- Conditionals
Like if else loop 
makes it more like a programming language