# **_Use Variable to Replace Parameter/Save Output_**

![Alt get-service for example](pic/bandicam%202022-10-09%2020-01-51-659.jpg)

![Alt assign value to variable](pic/bandicam%202022-10-09%2020-03-05-230.jpg)

![Alt assign output to variable](pic/bandicam%202022-10-09%2020-04-06-326.jpg)

![Alt use variable to print](pic/bandicam%202022-10-09%2020-04-33-850.jpg)

- variable doesn't just store the value, it stores the **result of the Get-command**.
- When a **value or object is used repeatedly** in a script, variables can greatly simplify the script content.

# **_Variable Types_**

![Alt variable type](pic/bandicam%202022-10-09%2020-05-18-380.jpg)

![Alt get-date](pic/bandicam%202022-10-09%2020-06-19-208.jpg)

- Get-Date will get the current time.

  - current time is date value.

- Get-Date is usually less often executed as a normal command and uses its parameters, but is usually directly assign to the variable like bellow.

![Alt assign get-date to variable](pic/bandicam%202022-10-09%2020-06-59-193.jpg)

- The variables in PowerShell do not need to be declared, but rather their type is determined by the assigned value.
  - in this case, date is assigned to the variable, so this variable is date type.

# **_Variable is Object_**

![Alt date type variable's properties](pic/bandicam%202022-10-09%2020-09-38-791.jpg)

![Alt date type variable's method](pic/bandicam%202022-10-09%2020-11-35-402.jpg)

- We can find that the variable does not just store the date, but also generates many related **properties** and **methods**.
  - In fact, any variable is **object** no matter what type of value it store.
