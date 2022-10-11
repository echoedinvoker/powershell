# **_Functionalize Get-Service pipeline_**

> If a **pipeline** in PowerShell is long and needs to be used frequently, you can define it with function.

## **commands in the pipeline**

![Alt feel command too long](pic/bandicam%202022-10-11%2013-53-06-516.jpg)

## **functionalize pipeline**

![Alt create function](pic/bandicam%202022-10-11%2013-56-16-561.jpg)

## **save function as ps file**

![Alt save as](pic/bandicam%202022-10-11%2013-58-06-810.jpg)

![Alt save function to file](pic/bandicam%202022-10-11%2013-59-12-279.jpg)

## **use function**

![Alt execution file and use function](pic/bandicam%202022-10-11%2014-02-35-796.jpg)

- According to the lecture, the ps file will be **discarded after execution**, which means that the result will be **removed from memory**, so the execution of the function should **fail**.
  - But I can actually execute it directly and **successfully**.

![Alt dot to contain it in the memory](pic/bandicam%202022-10-11%2014-04-48-090.jpg)

- If it fails, a **dot** must be added in front of the execution of the ps file to **prevent** the result of the ps file from being removed from memory.

# **_Functionalize Get-ADUser pipeline_**

## **commands in the pipeline**

![Alt get-aduser all users](pic/bandicam%202022-10-11%2014-10-12-928.jpg)

- Because **-Filter** must be present, if you want to get **all user data**, you have to give the **-Filter \*** parameter.

![Alt get only disable user](pic/bandicam%202022-10-11%2014-13-44-720.jpg)

- **enabled** is property name, so you can't just give **disable**.
- Here the **compare operator** needs to be wrapped in **curly brackets**, but not when using **where-object** before.
  - Beware of these subtle differences.

## **funtionalize pipeline**

![Alt functionalize](pic/bandicam%202022-10-11%2014-23-36-983.jpg)

## **save function as ps file**

![Alt save as](pic/bandicam%202022-10-11%2014-16-10-569.jpg)

![Alt save function to file](pic/bandicam%202022-10-11%2014-16-33-242.jpg)

## **use function**

![Alt use function](pic/bandicam%202022-10-11%2014-19-08-345.jpg)

- In practice, running the ps file directly **without dot** in front of it also works.
