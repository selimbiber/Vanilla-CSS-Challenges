# Instructions for Disable Text and Image Selection

## In this lab, you would have to make the give article element non-selectable using the cursor. You would be learning about user-select property.

## By default user-select value is set to auto for all userAgents (Browsers).

## To make the text unselectable we have to change the value of this property to none . This should do the trick, this will stop any users from selecting text on your web page.

## All the browsers by default do not support thisuser-select property to ensure cross-compatability (the features works across different browsers) we need to add a webkit property.

Webkit is the rendering engine used in the Safari Browser. Whereas Blink in the rendering engine used in Chromium based browsers

    ```
    #text {
        -webkit-user-select: none;
    }
    ```

#### Challenges (2/2 done)

Verify that the text is not selectable by double clicking
Verify that the text is not selectable by dragging for a selection

##### [Live Preview](https://selimbiber.github.io/Vanilla-CSS-Challenges/Day17-disable-text-selection/)
