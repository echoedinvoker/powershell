# **_Concept of Array & ArrayList_**

![Alt array and arraylist concept](pic/bandicam%202022-10-09%2000-42-13-962.jpg)

- Array cannot be modified but can be **recreated**, which is the perspective of the **same variable**.
  - But **recreate** is quite troublesome, because other unchanged parts also have to be rewritten.
    - So the more data in the Array, the more **inefficient** the **recreate** will be.

# **_Array_**

![Alt assign array to variable](pic/bandicam%202022-10-09%2000-45-26-062.jpg)

![Alt print it on the console](pic/bandicam%202022-10-09%2000-47-48-741.jpg)

# **_Array is Fixed, only RECREATE work_**

![Alt correct by recreate](pic/bandicam%202022-10-09%2000-49-25-449.jpg)

![Alt print result](pic/bandicam%202022-10-09%2000-50-34-254.jpg)

![Alt dot methods](pic/bandicam%202022-10-09%2000-52-24-400.jpg)

![Alt try to use method attached to array](pic/bandicam%202022-10-09%2000-54-19-829.jpg)

- Although you can see many **Array-specific methods** in intellisense, they are **not available** because the **Array content is fixed**.

![Alt append by recreate](pic/bandicam%202022-10-09%2000-56-30-975.jpg)

![Alt how to remove](pic/bandicam%202022-10-09%2000-57-51-655.jpg)

![Alt remove by recreate](pic/bandicam%202022-10-09%2000-58-43-974.jpg)

- The only operation **Array** can do is **recreate**.

# **_ArrayList_**

## **Create ArrayList**

![Alt create a arrayList](pic/bandicam%202022-10-09%2001-01-53-905.jpg)

- When we assign an Array to a variable, just add **[System.Collections.ArrayList]** in front of it and the result will be an **ArrayList** instead of an Array.

## **ArrayList can use specific methods to modify**

> Because the contents of an ArrayList are **not fixed**.

![Alt append by method](pic/bandicam%202022-10-09%2001-04-22-939.jpg)

![Alt remove by method](pic/bandicam%202022-10-09%2001-05-14-944.jpg)

- Compared to **recreate**, the above way of using **methods** to modify the content can help us save a lot of time.

# **_Narrow Scope of Get- command_**

## **Narrow Scope with single value**

![Alt get-service](pic/bandicam%202022-10-09%2001-06-16-909.jpg)

![Alt narrow scope by value](pic/bandicam%202022-10-09%2001-07-42-239.jpg)

- We already know that the output of Get-command can use **value** to narrow its search scope.

## **Narrow Scope with array(directly)**

![Alt narrow scope by array](pic/bandicam%202022-10-09%2001-09-00-366.jpg)

- You can also use the **array** to narrow search scope.

## **Narrow Scope with array(via variable)**

![Alt assign array to variable](pic/bandicam%202022-10-09%2001-10-26-989.jpg)

![Alt narrow scope by variable](pic/bandicam%202022-10-09%2001-12-09-969.jpg)

- We can assign the value or Array to the **variable** first, and then use the **variable** to narrow the search scope.
  - This approach increases flexibility in use.
