![preview](preview.jpg)

# 95CSS
## A Windows 95 style CSS framework

![Version 0.2.0](https://img.shields.io/badge/version-0.1.0-brightgreen.svg)

95CSS is a simple CSS framework in the style of the Windows95 O.S.

It uses both Bootstraps reboot and grid system but, even though a lot of class names are similar, it is NOT a Bootstrap theme.

*Suggestions  / pull requests to make this framework look more like Windows 95 / to optimize the code are welcome*

## Getting started
To get started simply add the `dist/95css.css`-file to your page.

## Styling
### Grid
The grid used is the bootstrap 4 grid and usses the same bootstrap classes.
You can use `.container`, `.container-fluid`, `.row` and all the `.col-` classes.

### General
The typography has been given basic styling including it's own simple windows-95 like font.
The body has been given a default background-color.

### Buttons
`button`, `input[type=submit]` and `.btn` have been given a default button styling to look like the windows 95 buttons. There are currently no extra classes like `primary`, `secondary`, `light`, `dark`,...

### Inputs
Most inputs have been styled, including `select`s but the input styling could be improved / built upon.

### Cards
Cards have been styled to look like the popups you'd see in the O.S. They have a card-header, a card-title and card-body. Modals and Cards share the same basic styling.

## Javascript
### Modals
Currently the only javascript that's part of this framework is [Micromodal.js](https://micromodal.now.sh). This is used to create WAI-ARIA guidelines compliant modals in a simple manner, but if wanted could be easily removed or switched with a different modal plugin.
The modal styling is done completely in CSS and builds on the card styling.

Make sure to add `dist/95css.js` to your page to be able to use the modals.
