# Exercise Link:<br>
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Test_your_skills:_Conditionals<br>

# Instructions:<br>
For the final task you are given four variables:<br>

* `machineActive` — contains an indicator of whether the login machine is switched on or not `(true/false)`.<br>
* `pwd` — Contains the user's login password.<br>
* `machineResult` — begins uninitialized, but is later used to store a response that will be printed to the output panel, letting the user know whether the machine is switched on.<br>
* `pwdResult` — begins uninitialized, but is later used to store a response that will be printed to the output panel, letting the user know whether their login attempt was successful.<br>

We'd like you to create an `if...else` structure that checks whether the machine is switched on and puts a message into the `machineResult` variable telling the user whether it is on or off.<br>

If the machine is on, we also want a second conditional to run that checks whether the `pwd` is equal to cheese. If so, it should assign a string to `pwdResult telling the user they logged in successfully. If not, it should assign a different string to `pwdResult` telling the user their login attempt was not successful. We'd like you to do this in a single line, using something that isn't an `if...else` structure.<br>

# My Solution:
```
// Add your code here
    if (machineActive) {
      if (pwd === "cheese") {
        pwdResult = "Log in successful!";
      } else {
        pwdResult = "Invalid password!";
      }
      machineResult = "Machine is on";
    } else {
      machineResult = "Please turn on the machine";
    }
```
