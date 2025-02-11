# React Native TypeError: Cannot read properties of null (reading 'property')

This repository demonstrates a common React Native error: `TypeError: Cannot read properties of null (reading 'property')`.  This error occurs when you attempt to access a property of an object that is currently `null` or `undefined`.  The solution involves proper null and undefined checks to avoid accessing properties of non-existent objects.  The example showcases the error and a robust solution using optional chaining and nullish coalescing.

## Reproducing the Error

The `bug.js` file demonstrates the error.  It attempts to access the `name` property of a user object that may not yet have been loaded from an API or might be null.