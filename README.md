#SELECTORS
##Relational Selectors
- Descendant (E F)
- Child (E > F)
- Adjacent Sibling (E + F)
- General Sibling (E ~ F)

##Attribute Selectors
- E[attr]
- E[attr=val] equals
- E[attr~=val] like
- E[attr|=val] or
- E[attr^=val] preffix
- E[attr$=val] suffix
- E[attr*=val] contains

## Pseudo-Class UI Selectors
- :enabled
- :disabled
- :checked
- :indeterminate
- :default
- :valid
- :invalid
- :in-range
- :out-of-range
- :required
- :optional
- :read-only
- :read-write

## Negation Pseudo-Class Selector
- tag:not(argument)

## Target Pseudo-Class Selector
- tag:target

## Structural Selectors
- :root
- :empty
- :first-child
- :last-child
- :first-of-type
- :last-of-type
- :only-child
- :only-of-type

## NTH Type Selector
- :nth-child(n) [n= odd/ even / an+b]
- :nth-last-child(n)
- :nth-of-type(n)
- :nth-last-of-type(n)

## Pseudo-Elements
- ::first-line
- ::first-letter

## Generated Content
- ::before
- ::after
    - content
- ::selection

## COLORS
- RGBA
- HSL and HSLA
- Opacity
- Gradients

## WEB FONTS
- @font-face
//fontsquirrel.com
- Text Shadows
- Multi-Column
    - column-count
    - column-gap
    - column-width
    - column-rule

## FLEXIBLE BOX MODEL

## CSS3 Box Model
- Border Radius
- Border Images
- Box Shadows
    - inset

## CSS3 BACKGROUNDS
- background-size
- background-repeat: round | space
- Multiple Backgrounds
- background-origin
- background-clip

## CSS3 TRANSFORMS
- transform:
    - scale
    - skew
    - rotate
    - translate
    //westciv.com/tools/transforms
- transform-origin:


## CSS3 TRANSITIONS
- transition-property:
    - none | all | <iden>
- transition-duration:
    - time
- trnsition-timing-function:
    - keywords
        - linear
        - ease
        - ease-in
        - ease-out
        - ease-in-out
- transition-delay:
    - time
- //shorthand
    - transition: height 1s ease-in .5s;


## MEDIA QUERIES
- width
- height
- device-widht
- device-height
- orientation
- aspect-ratio
- device-aspect-ratio
- color
- color-index
- monochrome
- resolution
- scan
- grid

## RESOURCES
- http://www.alistapart.com/articles/responsive-web-design/

- http://www.smashingmagazine.com/2010/07/19/how-to-use-css3-media-queries-to-create-a-mobileversion-of-your-website/
