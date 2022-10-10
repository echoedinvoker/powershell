# **_Intro If ElseIf & -Not_**

## **Three Result of Get-Service**

![Alt get-service narrow by displayName](pic/bandicam%202022-10-10%2007-53-02-084.jpg)

![Alt start service](pic/bandicam%202022-10-10%2007-56-56-371.jpg)

- This step may not work and there will **not** be any error message, if this is the case use the **administrator** to open ISE.

![Alt get-service not exist](pic/bandicam%202022-10-10%2007-58-24-160.jpg)

## **if Else**

![Alt assign result to a variable](pic/bandicam%202022-10-10%2008-01-32-933.jpg)

- When get-service query does not get any service, it **does not return anything** to $service.
  - **nothing is falcy value**, so if it used in condition it should become False value.

![Alt -Not operator](pic/bandicam%202022-10-10%2008-03-05-682.jpg)

- just like **~** operator in JS.

![alt](pic/bandicam%202022-10-10%2008-23-07-067.jpg)

- We can use the same approach to execute commands for different blocks based on the presence or absence of variables.

# **_Write a complete Script_**

![Alt full script](pic/bandicam%202022-10-10%2008-06-50-213.jpg)

![Alt stop service and run script](pic/bandicam%202022-10-10%2008-08-50-705.jpg)

![Alt get non-exist service and run script](pic/bandicam%202022-10-10%2008-10-51-293.jpg)
