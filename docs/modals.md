# Modals

Currently the only javascript that's part of this framework is [Micromodal.js](https://micromodal.now.sh). This is used to create WAI-ARIA guidelines compliant modals in a simple manner, but if wanted could be easily removed or switched with a different modal plugin.
The modal styling is done completely in CSS and builds on the card styling.

Make sure to add `dist/95css.js` to your page to be able to use the modals.

## Adding a modal

To add a modal, first add the following code:
```html
<div id="modal" class="modal" aria-hidden="true">
    <div tabindex="-1" data-micromodal-close class="modal-bg">
        <div role="dialog" aria-modal="true" aria-labelledby="modal-1-title" class="modal-dialog">
            <header class="modal-header">
                <h2 id="modal-1-title" class="modal-title">Modal Title</h2>
                <button aria-label="Close modal" data-micromodal-close class="modal-close">X</button>
            </header>
            <div id="modal-1-content" class="modal-body">
                <h3>Modal content</h3>
                <p>Lorem ipsum dolor sit amet,[]</p>
                <button data-micromodal-close class="btn">close</button>
            </div>
        </div>
    </div>
</div>
```
The `modal` class is used to style the modal, the id is used for targeting the modal and can be whatever you want it to be.

The modal should include a `modal-title` to be compliant to WAI-ARIA guidelines as well as a `modal-close` button for usability's sake.

The `modal-body` should hold all the modal content.
The modal can be closed by pressing `esc`, clicking outside the modal or by clicking the `modal-close` button.

You can add extra close buttons by adding a button with the `data-micromodal-close` attribute
