# Difference between CADS and tachyons

## Line height

Generator (and tachyons) uses the format of decimals (1.2) when we currently calculate this in rems.

## Media queries:

We currently use:  
$bp--sm: 555px; 
$bp--md: 750px;
$bp--lg: 1024px;
$bp--xl: 1400px;

Where as tachyons uses em and sizes:
medium (m), large (l), extra-large(xl) and not small(ns)

Currently changed it to:
m: 48em (768px)
l: 64em (1024px)

## links

Tachyons links by default don't have a background colour by default

## Grid

Tachyons uses both percentage and fraction classes.
e.g w-50 and w-third or w-two-thirds

We could use both.

## Fonts

Would need to add a class to use open-sans

## Font weight

We only currently use:
Regular (400)
Extra bold (600)
Extra bold (700)
Extra bold (800)

Tachyons uses fw4 { font-weight: 400; }
We could use that plus fw-regular

## General typography

May need to work out how to modify typography styles when at different breakpoints.

ie H1 on mobile is 28px and 36px on larger screens

## Categorising individual css files

Could copy current Tachyons folder structure.
