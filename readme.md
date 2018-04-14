# MLP eDM Test

## Goal
My goal was to replicate the email template in the images provided, with an extendable text area, as well as links, and styling.

The PSD includes slices for images used in the email, as well as non-image slices to gauge content size. Guidelines were added to parts of the template that required positioning or reference.

The eDM-template.html file was developed and tested in Chrome and Safari. I aimed to have both browsers display content as close to the original image. Failing that, I made sure they were at least formatted the same - no extra lines, pixels, etc. Measurements are either in px for positioning, and REM for text for consistency and responsiveness. Comments were intentionally left in the HTML file for referencing and indexing.

There were some notable cross-browser difficulties that were encountered (and overcome) such as, font sizing/weight - Safari displays slightly larger, and horizontal resizing when a container cannot hold its contents.

## Some notable styling:

### Consistency to design and error
- The goal was to make an email template with an extendable text area. While I believe that has been achieved, I have intentionally used the original text, errors and all (Such as “Willyou” in the side bar). This was so I had the most accurate reference to sizing and positioning.

### Colour Gradient
- There are two colour gradients used as background colours. The most notable being the background of the main email content. I noticed that the colours at the top began at #ececec, and ended lighter at #fefefe in the footer. I replicated this top down colour gradient as a background colour. The other possible gradient is used in the top most header. I opted to use an image instead, as the gradient did not fully match.

### Footer divider border
- This is somewhat similar to the colour gradient, but it is only 4px in height, and does not interfere with the background's colour gradient.


## Index of the eDM

#### Header and Banner
Where you will find the topmost page content - including links to follow on Youtube and Facebook

#### Left Column
Where you will find the extendable text sections, and red arrow links.

##### Extendable text section ("top, center, bottom")
Text areas that can extended as you add more text content

#### Right Column
Contains side bar with link, and promo image.

#### Footer
Contains footer links and disclaimers.
