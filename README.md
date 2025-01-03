# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle bug that can occur in HTML when using JavaScript to manipulate the DOM. The bug is a simple typo in the `getElementById` function.

## Bug Description
The bug lies in the JavaScript code within the `bug.html` file.  The developer mistyped `getElementById` as `getElementByIdx`. This causes the JavaScript to fail silently, leaving the intended behavior (hiding the div) unfulfilled. This is uncommon because linters and IDEs often detect this kind of typo.