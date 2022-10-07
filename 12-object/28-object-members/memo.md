## **Concept**

![Alt object concept](pic/bandicam%202022-10-08%2004-33-49-834.jpg)

- In PowerShell, each service is an object.
  - Under each object there will be members, members have three types:
    - property
      - attribute of object.
    - method
      - let object to action something.
    - event
      - wait something happened and trigger some action.

## **Practice**

![Alt get-service](pic/bandicam%202022-10-08%2004-37-04-803.jpg)

- In fact, get-service generates an **object** and prints it directly in the console.

![Alt pipe get-member](pic/bandicam%202022-10-08%2004-41-43-652.jpg)

- Because the result of get-service is an **object**, we can **pipe get-member** to get the **member** list of this object.

![alt](pic/bandicam%202022-10-08%2005-02-53-036.jpg)

- The result you see above is also the **object** generated by the get-member, so of course you can also **pipe another get-member** to print out the **member** list of the second object.

## **Alias**

![Alt alias of get-member](pic/bandicam%202022-10-08%2004-49-40-827.jpg)