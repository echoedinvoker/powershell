# **_Misleading Version by folder_**

![Alt folder version](pic/bandicam%202022-10-01%2000-27-47-063.jpg)

- Currently there are only six versions of powershell: **1, 2, 3, 4, 5, 5.1**
- Regardless of the version of powershell, the application file is always in the **v1.0** folder, which is very misleading.

# **_Current Version_**

![Alt cmd to check current version](pic/bandicam%202022-10-01%2000-28-45-223.jpg)

- We must use the above command to see the current powershell version in use.

# **_Change Version_**

![Alt change version](pic/bandicam%202022-10-01%2000-29-12-445.jpg)

- Because different versions of the command itself or its parameters are different, you may not be able to use the previous script or command, so you must use the above method to switch to an older version.
- Once the powershell console is restarted, the version will return to the default state, so using **powershell -version** to change the version is not permanent, and we don't need to manually switch back again, just reopen it.

# **_Change to Version 1, 2_**

![Alt not installed version](pic/bandicam%202022-10-01%2000-31-11-992.jpg)

- Because powershell version 3 is much different from the previous version and comes from a different .NET framework, it may not be possible to switch to version 2 or 1 directly using **powershell -version**.

## **Open .NET framework 3.5**

> If you must go back to version 2 or 1, you must first open the .NET framework 3.5 at **optionsandfeatures**.

![Alt controller](pic/bandicam%202022-10-01%2000-32-05-020.jpg)

![Alt option and features](pic/bandicam%202022-10-01%2000-33-01-735.jpg)

![Alt  turn windows features on/off](pic/bandicam%202022-10-01%2000-33-23-771.jpg)

![Alt  .NET framework3.5](pic/bandicam%202022-10-01%2000-34-29-469.jpg)

- After checking the box, you still need to **restart** your computer to use **powershell -version** in powershell to change to version 2 or 1.
- A faster alternative to the above process is to use **windows + R** and type **optionalfeatures.exe**.

# **_Not 100% compatibility solution_**

- Note that the above method is **not** 100% compatible with older scripts or commands and may still fail, but you can at least try to do this when there is a need to run older scripts.
