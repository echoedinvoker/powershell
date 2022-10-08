## **Operator Table**

![Alt operator table](pic/bandicam%202022-10-09%2002-25-03-375.jpg)

## **Use Operator to Compare two value directly**

### _capital sensible or not_

![Alt -eq -ceq](pic/bandicam%202022-10-09%2002-26-43-396.jpg)

### _compare number_

![Alt -gt -lt](pic/bandicam%202022-10-09%2002-27-15-285.jpg)

### _wildcard_

![Alt -like](pic/bandicam%202022-10-09%2002-29-01-542.jpg)

## **Where-Object command**

![Alt where-object](pic/bandicam%202022-10-09%2002-34-44-773.jpg)

- The above writing approach only works in **PS5 or newer version**, just specify the **property** and then write the **operator followed by the value** to know what we want to do.

![Alt older script](pic/bandicam%202022-10-09%2002-38-40-858.jpg)

- In the **old version of PS** we had to use **$PSitem.property** to explicitly tell it to use a certain property of each item under the object for comparison.

![Alt more older script](pic/bandicam%202022-10-09%2002-40-17-656.jpg)

- In **PS1 or 2** we don't even have **\$PSitem** to use, we can only use **\$\_** .
