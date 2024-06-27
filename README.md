# Module 3 Challenge

## Technology Used

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |
| Javascript | [https://developer.mozilla.org/en-US/docs/Web/Javascript](https://developer.mozilla.org/en-US/docs/Web/Javascript) |
| Git | [https://git-scm.com/](https://git-scm.com/)     |

## Description

[Visit the Deployed Site](https://kaylahebertson.github.io/module-3-challenge/)

This project is a simple employee data tracker that allows one to enter an employee's first name, last name, and salary. Using JavaScript enables the user to see an alphabetized list of their employees by last name. Opening the console log will show the average salary and pick a random employee from the list. 

## JavaScript example

Here is an example of a JavaScript function that allows a user to enter data until they hit cancel. This data is turned into an array and is later used to display employees' information, calculate the average salary, and randomly pick an employee.

```javascript
const collectEmployees = function () {
  const employees = [];
  let userPrompt = true;

  while (userPrompt) {
      const firstName = prompt("Please enter employee's first name");
      const lastName = prompt("Please enter employee's last name");
      const salary = parseFloat(prompt("Please enter the salary of the employee"));

      const employee = {
      firstName: firstName,
      lastName: lastName,
      salary: salary,
    };

  employees.push(employee);

  userPrompt = confirm('Do you want to add another employee?');
}

return employees;

};
```

## Usage

This project can be used to track employee data, find the average salary, and pick an employee at random.

## Learning Points

This project helped me learn how to create a function in JavaScript. I learned how to use a while loop so that a function will repeat continously until the user chooses to stop it. I also learned how to use Javascript to do math and randomly pick a index.

## Author Info

```md
Kayla Hebertson

* [Github](https://github.com/kaylahebertson)
* [LinkedIn](www.linkedin.com/in/kayla-hebertson)
* [Portfolio](coming soon)

```

## Credits

Coding Bootcamp

[W3Schools](https://www.w3schools.com/)

[MDN Web Docs](https://developer.mozilla.org/en-US/)

## License

Please refer to the LICENSE in the repo.