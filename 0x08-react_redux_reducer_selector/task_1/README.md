Now that you have set up a basic reducer, let’s reuse what we learned in the Immutable module and apply it to that reducer:

Install Immutable.js within the project
Update the uiReducer.js file to use Map from Immutable.js
Update the different part of the reducer function to use set from Map
Update the test suite, so it takes into account the changes
Tips:

You can use the toJS function within your tests for an easy comparison
Remember that Immutable.js always return a new Map after a modification
Requirements:

For better performances, do not use any fromJS, toJS function within the reducer
All the tests in the project should pass
