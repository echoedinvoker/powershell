## **Tack Manager**

![Alt default](pic/bandicam%202022-10-08%2021-43-40-698.jpg)

![Alt task manager](pic/bandicam%202022-10-08%2021-44-39-087.jpg)

- **Get-Process** is actually what we see in **Task Manage**.

## **Order By CPU (High to Low)**

![Alt get-member](pic/bandicam%202022-10-08%2021-46-45-640.jpg)

- Because the columns name printed in the console may not be the correct property name, you can first use **Get-Member** to see what properties are available

![Alt sort cpu](pic/bandicam%202022-10-08%2021-47-45-013.jpg)

- Try to use property "cpu" to do sort, and it looks like the result is what we want

## **Only need Subset of output**

> If you want only part of the original output(**Subset**), you can use the **Select-Object**.

![Alt subset first 10](pic/bandicam%202022-10-08%2021-49-23-123.jpg)

![Alt last 10](pic/bandicam%202022-10-08%2021-49-59-458.jpg)
