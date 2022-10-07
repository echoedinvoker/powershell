## **Intro CMD command - "icacls"**

![Alt intro CMD command "icacls"](pic/bandicam%202022-10-07%2011-59-28-256.jpg)

- "**icacls**" is a CMD command that defines the permissions of a folder or file.

## **Prepare a new folder**

![Alt create a new folder](pic/bandicam%202022-10-07%2012-04-19-752.jpg)

![Alt check permission in file explorer](pic/bandicam%202022-10-07%2012-06-09-572.jpg)

## **Try to set permission in PowerShell**

![Alt directly use CMD command in powershell](pic/bandicam%202022-10-07%2012-10-20-807.jpg)

- The way some parameters in CMD command are written to powershell can cause misjudgment like above.

![Alt --%](pic/bandicam%202022-10-07%2012-12-51-116.jpg)

- We will use the parameter **--%**, which means that the values following this parameter are parsed using the **CMD command way**.

![Alt check permission change](pic/bandicam%202022-10-07%2012-13-36-326.jpg)

- test folder successfully added permission to the "backup operator" group.

## **Clear test folder**

![Alt remove folder](pic/bandicam%202022-10-07%2012-17-03-461.jpg)

- Basic file and folder operations can query the keyword **item**.
