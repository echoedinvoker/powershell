## **New-Item**

![Alt check syntax of new-item](pic/bandicam%202022-10-07%2013-57-17-990.jpg)

![Alt new-item prompt](pic/bandicam%202022-10-07%2014-03-29-426.jpg)

## **Show-Command**

![Alt show-command](pic/bandicam%202022-10-07%2014-07-10-154.jpg)

- The parameters we saw earlier by querying the New-Item syntax are presented through the UI.

![Alt show-command UI filling](pic/bandicam%202022-10-07%2014-07-55-050.jpg)

![Alt show-command execution](pic/bandicam%202022-10-07%2014-11-28-643.jpg)

- The result of filling in the UI will generate the full New-Item command and execute it.

![Alt show-command another cmd](pic/bandicam%202022-10-07%2014-14-28-643.jpg)

- So in fact, Show-Command works to help us generate commands (according to our filling) and execute them.

## **Out-GridView**

![Alt result too much](pic/bandicam%202022-10-07%2014-16-44-077.jpg)

- Sometimes the result of our command is **too much to read in the console**, we can use the **Out-GridView** command to solve this problem

![Alt pipeline](pic/bandicam%202022-10-07%2014-19-36-967.jpg)

- There are some commands that need to be paired with **pipelines** to achieve their functionality, and **Out-GridView** is one of them.
- **|** is a pipe symbol that can be used to combine commands.
  - The commands are executed in **left-to-right** order, and the command on the right uses the result of the left command as **input**.

![Alt ogv](pic/bandicam%202022-10-07%2014-19-49-573.jpg)

- instead of **Out-GridView**, we usually use its alias **ogv**.

![Alt ogv UI](pic/bandicam%202022-10-07%2014-21-34-775.jpg)

![Alt filter1](pic/bandicam%202022-10-07%2014-21-57-973.jpg)

![Alt filter2](pic/bandicam%202022-10-07%2014-22-39-439.jpg)

- **ogv** will present the results of the command in a new **window**.
  - The window has **scroller** and **filter**, which is suitable for presenting large amount of data.
