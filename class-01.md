# Responsive Web Design
## Responsive web design is the practice of building a website suitable to work on every device and every screen size, like desktop laptop , mobile .
##  Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation ,Mobile, on the other hand, generally means to build a separate website commonly on a new domain solely for mobile users .

## Responsive web design is broken down into three main components
1. ### flexible layouts 
2. ###  media queries 
3. ### flexible media 

## Flexible Layouts 
## Flexible layouts do not advocate the use of fixed measurement units, such as pixels or inches. Reason being, the viewport height and width continually change from device to device

## Flexible Grid 
### Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units.

## Media Queries
### Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example

## Flexible Media
### As viewports begin to change size media doesn’t always follow suit. Images, videos, and other media types need to be scalable, changing their size as the size of the viewport changes.
### One quick way to make media scalable is by using the max-width property with a value of 100%. Doing so ensures that as the viewport gets smaller any media will scale down according to its containers width. 

## Floats
### Float is a CSS positioning property , There are four valid values for the float property. Left and Right float elements those directions respectively. None ensures the element will not float and Inherit which will assume the float value from that elements parent element.
### An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float .
### If this parent element contained nothing but floated elements, the height of it would literally collapse to nothing.
### Techniques for Clearing Floats
1. ####  The Empty Div Method
2. ####  The Overflow Method
3. ####  The Easy Clearing Method

### Problems with Floats 
1. #### Pushdown
2. #### Double Margin Bug
3. #### The 3px Jog
4. ####  Bottom Margin Bug

## SMACSS (Scalable and Modular Architecture for CSS)
###  SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process.

## SMACSS is categorization
1. ### Base
2. ### Layout
3. ### Module
4. ### State
5. ### Theme


### State changes are represented in one of three ways
1. #### class name
2. #### pseudo-class
3. #### media query

