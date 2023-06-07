   Harmonia   

Harmonia design system
======================

by [@xargr](https://twitter.com/xargr)

Heading 1
=========

Heading 2
---------

### Heading 3

Font families
-------------

Font family Poppins ( used only in headings or CTA )

`@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');      font-family: 'Poppins', sans-serif;`  
or  
`@import url('https://fonts.googleapis.com/css2?family=Sora&display=swap');      font-family: 'Sora', sans-serif;`

Font family Tahoma ( it's web safe - used everywhere as a default font family and required in text heavy areas )

Font size
---------

primary font size 16px

medium font size 14px

small font size 12px

on mobile minumun 16px

Font style
----------

only normal

Font weight
-----------

normal or bold

Font color
----------

primary neutral color #2c2c2c

secondary neutral color #828893

Font scale
----------

1.25 - Major third see [typescale.com](https://typescale.com/)

Spacing
-------

followed the [8 point system](https://www.google.com/search?q=8+point+system)

css variables  
`--space-1: 4px;   --space-2: 8px;   --space-3: 16px;   --space-4: 24px;   --space-5: 32px;   --space-6: 40px;`

for internal distances eg. label and field, we can then only use 4 point system

Color ratio
-----------

followed the [60-30-10 color rule](https://www.google.com/search?q=60+30+10+color+rule+design+system)

Text alignment
--------------

Use left alignment everywhere

Use center alignment for text maximun 3 lines

Web accessibility
-----------------

no more than 60 characters per line for desktop and 30-40 for mobile

group related items together and give enough space to differentiate them

Layout
------

12 grid for desktop, 8 grid for tablet and 4 grid for mobile

maximun width 1200px

16px margin left and right

32px gutter for each grid side and 16px for mobile

Dark mode
---------

avoid pure black on text and surface color

surface color #121212

primary text color 87% opacicy and 60% for secondary color

vibrant color saturated -20%

Viewport - responsiveness
-------------------------

mobile first approach

768px and up for tablets and bigger screens

1200px and up for large screens

12 columns grid layout
----------------------

wrap every row with `.grid` class and then use accordingly `.col-12 .col-6 .col-4`

col-12

col-6

col-6

col-4

col-4

col-4

Elevation
---------

`.shadow-normal`

`.shadow-small`