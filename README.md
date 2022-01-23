# Visual regression testing with React and Backstop Js

A visual regression test checks what the user will see after any code changes have been executed by comparing screenshots taken before and after code changes.

## Steps to run this app

* Clone the repository
* cd inside folder
* npm i 
* npm run start - to see the basic h1 title

## How to check visual changes

* npm run backstop:test - Once changes are made, running this command will display the comparison of between old and new change as below.
* npm run backstop:approve - If the changes are intentional, running this command will update the reference screenshot in the app.

![Backstop report](docs/backstop-screenshot.png?raw=true "Backstop report")

