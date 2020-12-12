# Employee Summary Webpage Engine

This Node application will assist managers in generating a webpage that displays their team's basic info for quick access to emails and GitHub Profiles.

## Installation
---
Run `npm install` to install all dependencies

## Folder Structure
---
```
lib/           // classes and helper code
output/        // rendered output
templates/     // HTML template(s)
test/          // jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js         // Runs the application
```
## Usage
---
1. Run `node apps.js` to start the application
2. Enter the number of users within your team
3. Enter the employees name > `ENTER`
4. Enter the employee's ID > `ENTER`
5. Enter the employee's email > `ENTER`
6. Select the employee's title > `ENTER`
7. If you selected Engineer, input their GitHub. If you selected Manager, input their office number. If you selected Intern, input their school
8. Repeat for all employees until you receive the "Success!" notification. 

    ![](images/CLI.gif)

9. Go to the `output` folder, find `team.html` and open it in your default web browser. 

   <img width="1427" alt="10-OOP-homework-demo-1" src="https://user-images.githubusercontent.com/71414528/101994780-ebd13d80-3c79-11eb-81d9-66da00a81516.png">


## Tool & Resources
---
* [Bootstrap](https://getbootstrap.com/) - CSS framework used
* [Node.js](https://nodejs.org/en/) - JavaScript runtime environment

    ### Dependencies
    ---
    * [Inquirer](https://www.npmjs.com/package/inquirer) - for the CLI user interface. This will prompt user within the CLI for employee information.

## Running the Test
---
run `npm run test` in the root

