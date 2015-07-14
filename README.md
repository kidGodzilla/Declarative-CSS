# Declarative-CSS
A Declarative CSS Library for Rapid Prototyping &amp; Development which seeks to simplify most use-cases.

## What?
The web is moving toward flexible, declarative standards. However, the only option for this in CSS is inline-styles, 
which have several drawbacks. They make managing precedence difficult, and styling becomes too closely coupled to layout. 

This declarative CSS library is an experiment. Although it is very bloated, it provides a nearly comprehensive set of responsive, declarative CSS classes for manipulating styles and layouts.

## Semantic CSS
This library closely follows CSS syntax. For example, `.display-none` corresponds to `display: none`. This is chosen to make the classes in this library easy to memorize and use.

## Progression Along a Spectrum
In other cases, suffixes are used to indicate progression along a spectrum. For example, `br-0` corresponds to `border-radius: 0`, while `br-1` corresponds to `border-radius: .125rem`.

## REM & Percentage Units
When possible, REM units are used for fixed values & percentages are used for relative ones.

## Responsiveness
This library follows Bootstrap conventions for declaring *xs, sm, md, & lg* breakpoints. Standard Bootstrap grid style suffixes can be appended to any class to indicate that this class should only be applied inside of a specific breakpoint.
This differs slightly from Bootstrap in that breakpoints do not cascade upwards (declaring `display-none-sm` will not make any changes on your medium and large devices).

## Overriding using !important
An `!important` version of each class exists to override previously applied styles. It is used by capitalizing the first letter of the classname.
For example, the className `Display-none` would override `display-block`.
