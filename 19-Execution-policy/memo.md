# **_Concept of Execution Policy Level_**

![Alt concept](pic/bandicam%202022-10-10%2005-12-41-834.jpg)

- **Restriced** is default level.
- About **digital sign**, you would have to have a **certificate server/certification authority(ca)/PKI server** (same thing).
  - This is a role in the windows operating system.
    - so on the windows server, you can install **active directory certificate services**.
      - then you generate a **code signing certificate** which is used to digitally sign any scripts that you want to execute on any computers **on your domain**.
- The problem with **AllSigned** is that if there is any change in the script, the **digital sign** will be **invalidated** and must be obtained again.
- **RemoteSinged**, simply explain that only the scripts **downloaded from the network** need digital sign, local scripts do not need.
- The difference between **Bypass** and **Unrestriced** is that when running the **download script**, Unrestriced pops up a **prompt hint** while Bypass does not get any prompt just run.

# **_Run a Local Script_**

## **Create a local script**

![Alt write a script with ISE](pic/bandicam%202022-10-10%2005-14-18-593.jpg)

![Alt save script to documents folder1](pic/bandicam%202022-10-10%2005-14-25-492.jpg)

![Alt ave script to documents folder2](pic/bandicam%202022-10-10%2005-15-01-303.jpg)

## **Run a local script**

![Alt run it and failed](pic/bandicam%202022-10-10%2005-18-43-816.jpg)

- default execution policy level is **restricted**, so no script can be executed.

![Alt modify execution policy and run again](pic/bandicam%202022-10-10%2005-21-45-085.jpg)

# **_RemoteSigned Level_**

## **Create a script on network**

![Alt upload script to internet](pic/bandicam%202022-10-10%2005-23-43-172.jpg)

![Alt rename](pic/bandicam%202022-10-10%2005-24-17-206.jpg)

![Alt download](pic/bandicam%202022-10-10%2005-26-00-519.jpg)

## **Try out RemoteSigned Level**

![Alt change policy to remote](pic/bandicam%202022-10-10%2005-26-49-856.jpg)

![Alt run local script](pic/bandicam%202022-10-10%2005-27-31-538.jpg)

![Alt  run downloaded script](pic/bandicam%202022-10-10%2005-28-18-646.jpg)

## **Unblock-File**

![Alt unblock-file](pic/bandicam%202022-10-10%2005-29-59-812.jpg)

- **Unblock-File** removes the network information from the file and makes the computer think it is a **local** script, so you don't need to have a digital signature to run the downloaded script in this way.

![Alt run downloaded script again](pic/bandicam%202022-10-10%2005-31-10-508.jpg)

# **_Set Execution Policy Level in the Local Group Policy Editor_**

![Alt enter group policy editor](pic/bandicam%202022-10-10%2005-31-50-390.jpg)

![Alt enter powershell](pic/bandicam%202022-10-10%2005-32-33-963.jpg)

![Alt open execution policy](pic/bandicam%202022-10-10%2005-32-42-485.jpg)

![Alt default execution policy setting](pic/bandicam%202022-10-10%2005-33-03-677.jpg)

![Alt change setting](pic/bandicam%202022-10-10%2005-34-22-742.jpg)

- The advantage of the above way is that you don't need to set the **script execution policy** one by one computer.
- Once you set the **script execution policy** with the **group policy editor** approach, you **cannot** use command in PowerShell to change it.
