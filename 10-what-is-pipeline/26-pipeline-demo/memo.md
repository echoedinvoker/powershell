# **_What we want to DO_**

![Alt server manager](pic/bandicam%202022-10-08%2000-59-30-224.jpg)

![Alt what we want to do](pic/bandicam%202022-10-08%2001-02-23-764.jpg)

- Simply speaking, we'll create an organization and then create a user account in it, but we'll do it using **powershell** commands.

# **_Query Syntax about Organization_**

![Alt get-command about organization](pic/bandicam%202022-10-08%2001-03-58-698.jpg)

![Alt check its syntax](pic/bandicam%202022-10-08%2001-05-20-963.jpg)

# **_Create/Check Organization_**

![Alt create org](pic/bandicam%202022-10-08%2001-07-11-163.jpg)

![Alt check org](pic/bandicam%202022-10-08%2001-13-28-973.jpg)

- We will use the value of **distinguishName** as the **path** to this organization, just like folder path.
  - This path will be used in other commands to select the organization.

![Alt check it in server manager](pic/bandicam%202022-10-08%2001-15-05-496.jpg)

- The organization is actually a **folder**.

# **_Create/Check User_**

![Alt create user in it](pic/bandicam%202022-10-08%2001-19-59-482.jpg)

- The value of the **require** parameter can usually be entered directly **without parameter** itself.

![Alt check user in it with server manager](pic/bandicam%202022-10-08%2001-21-27-385.jpg)

![Alt get-aduser](pic/bandicam%202022-10-08%2001-23-56-824.jpg)

- Although this user account cannot be used to log in, the purpose here is only for demonstration purposes, so it does not matter.

![Alt set user's property with pipeline](pic/bandicam%202022-10-08%2001-29-47-372.jpg)

![Alt set user's property without pipeline](pic/bandicam%202022-10-08%2001-34-14-805.jpg)

- **prompt** already presupposes that you must type the name string, so there can be **no more quotes**, even if there is space in the string.
