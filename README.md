# ECE444 Lab 5
This repo is a clone of https://github.com/mjhea0/flaskr-tdd

## Pros and Cons of TDD (Test Driven Development)
To start with some of the advantages of TDD, there are many reasons to take on a test driven approach such as:

Easier regression testing. If a developer inadvertedly causes a code regression it'll be detected by the test suite and can be addressed prior to merge/deployment. 

Increased test covereage. Since you are developing with a focus on testing, you should have test coverage for most if not all of the code you have written.

Easier refactoring. If you have to make major changes or feature updates, your vast test suite enables you to update package versions and run the test suite to check if any area of your code has been broken by the change.

The disadvantages:

TDD can introduce an extra layer of debugging since you now have to debug your tests in addition to the functionality you are implementing.

Slowed development speed. You now need to produce a greater volume of code for the same feature as compared to a development process where you aren't writing as many tests.

As requirments change, so does the testing need. Large changes in flow/structure can lead to breaking tests which then need to be updated to fit with the new schema, further slowly development.
