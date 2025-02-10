# Uncommon HTML Bug: Incorrect innerHTML usage for display property

This repository demonstrates an uncommon bug related to using `innerHTML` to manipulate the CSS `display` property of an HTML element.  The bug results in the element not being hidden as expected.

## Bug Description

The bug arises from attempting to set the `display` property of an element indirectly using `innerHTML`. Instead of directly modifying the element's style attribute, the code replaces the element's content, potentially leading to unexpected outcomes.

## Solution

The solution involves directly manipulating the element's style property using JavaScript, ensuring that the `display` property is set correctly.