## **Error Messages**

### _Typo failed_

![Alt typo error](pic/bandicam%202022-10-11%2010-49-52-793.jpg)

### _Query failed_

![Alt query non-exist error](pic/bandicam%202022-10-11%2010-50-54-809.jpg)

- In PowerShell, if the result of a query is **nothing**, it is also treated as an **error**.

## **Hide Error Message**

![Alt silent error msg](pic/bandicam%202022-10-11%2011-10-31-493.jpg)

- In PowerShell, even if the command results in an **error**, the subsequent commands will **continue to be executed**.

![alt](pic/bandicam%202022-10-11%2011-11-23-479.jpg)

- We can use **-ErrorAction SilentContinous** to hide the error message.
  - "**Continous**" I think is actually a redundant word, because regardless of whether there is an error program will **not be interrupted** in PowerShell.

## **Try Catch**

![Alt try catch with ..](pic/bandicam%202022-10-11%2010-56-14-091.jpg)

- **Try Catch** in PowerShell must be used with **-ErrorAction Stop**, otherwise the **Catch** part will not be executed when the error happens.

## **Finally**

![Alt finally](pic/bandicam%202022-10-11%2010-57-16-189.jpg)

- Works in the same way as other languages.

![Alt remove -ErrorAction stop](pic/bandicam%202022-10-11%2010-59-18-669.jpg)

- Removing **-ErrorAction stop** does not affect the execution of the **Finally** part of the command.
