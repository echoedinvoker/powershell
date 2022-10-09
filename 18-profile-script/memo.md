# **_Concept of Profile Script_**

![Alt what is profile script](pic/bandicam%202022-10-09%2021-10-06-364.jpg)

- **Host** is the place in powershell where commands are actually executed.

![Alt profile script locations](pic/bandicam%202022-10-09%2021-11-17-976.jpg)

- The path of the profile script file is stored in two variables by default.
  - But the file does not exist at first, we need to build it ourselves.

# **_Create Profile Script for PowerShell_**

## **Only has path of profile script but not files**

![Alt check with file explorer](pic/bandicam%202022-10-09%2021-12-50-752.jpg)

![Alt check variables in powershell host](pic/bandicam%202022-10-09%2021-13-54-730.jpg)

## **Create profile script by ourself**

![Alt create profile script](pic/bandicam%202022-10-09%2021-17-00-616.jpg)

![Alt check folder](pic/bandicam%202022-10-09%2021-17-39-633.jpg)

![Alt check file and content](pic/bandicam%202022-10-09%2021-18-08-654.jpg)

## **Setting Alias and Variable in the Profile Script**

![Alt write script with notepad](pic/bandicam%202022-10-09%2021-19-47-505.jpg)

- We can write directly in the notebook, or open the script in ISE to write.

## **Execution Policy problem**

![Alt error msg in new host](pic/bandicam%202022-10-09%2021-24-37-176.jpg)

![Alt change executionPolicy](pic/bandicam%202022-10-09%2021-26-33-904.jpg)

## **Check Result**

![Alt reopen host](pic/bandicam%202022-10-09%2021-26-49-479.jpg)

![Alt check alias and variable set on profile](pic/bandicam%202022-10-09%2021-29-18-589.jpg)

![Alt $proc](pic/bandicam%202022-10-09%2021-29-41-065.jpg)

# **_Create Profile Script for ISE_**

## **PowerShell and ISE use different Profile Script**

![Alt open a new ISE](pic/bandicam%202022-10-09%2021-30-00-472.jpg)

![Alt error msg](pic/bandicam%202022-10-09%2021-30-51-223.jpg)

- We found that the profile script I just set above has no effect in ISE.

## **Create profile script for ISE**

![Alt create profile script with ISE](pic/bandicam%202022-10-09%2021-33-22-149.jpg)

![Alt check file and content](pic/bandicam%202022-10-09%2021-34-10-965.jpg)

![Alt open previous file](pic/bandicam%202022-10-09%2021-35-24-339.jpg)

![Alt save as...](pic/bandicam%202022-10-09%2021-35-32-651.jpg)

![Alt modify file name](pic/bandicam%202022-10-09%2021-37-06-335.jpg)

- If you want to enter file name together **with the expension**, you must wrap the entire file name and expension in **double quotes** so that it will not be affected by the following file type.

![Alt confirm override](pic/bandicam%202022-10-09%2021-37-14-919.jpg)

![Alt check ISE profile](pic/bandicam%202022-10-09%2021-37-50-625.jpg)

## **Check Result**

![Alt reopen ISE](pic/bandicam%202022-10-09%2021-38-15-320.jpg)

![Alt check alias and variable](pic/bandicam%202022-10-09%2021-38-56-536.jpg)

# **_Edit Profile Script with ISE_**

## **Open Profile script with ISE**

![Alt open script with ISE1](pic/bandicam%202022-10-09%2021-39-03-898.jpg)

![Alt open script with ISE2](pic/bandicam%202022-10-09%2021-39-19-240.jpg)

## **Modify Host property**

> We can change the environment of the below Host by modifying the properties of the **$Host** variable.

![Alt edit $host property](pic/bandicam%202022-10-09%2021-40-49-148.jpg)

![Alt save and close ISE](pic/bandicam%202022-10-09%2021-41-15-143.jpg)

![Alt reopen ISE](pic/bandicam%202022-10-09%2021-42-11-316.jpg)

# **_Delete Profile Script_**

![Alt delete powershell folder](pic/bandicam%202022-10-09%2021-42-41-413.jpg)

![Alt ISE host background not recovery](pic/bandicam%202022-10-09%2021-46-01-488.jpg)

- Reopen ISE, host of it still green...

![Alt direct edit host background color to blue](pic/bandicam%202022-10-09%2021-46-46-728.jpg)

- directly modify $host's background color property to blue and reopent ISE.

![Alt not this color](pic/bandicam%202022-10-09%2021-49-02-680.jpg)

- It works but color is wrong.

![Alt to darkblue](pic/bandicam%202022-10-09%2021-50-58-208.jpg)

- do it again, use darkblue this time.

![Alt  yes correct color](pic/bandicam%202022-10-09%2021-51-35-976.jpg)

- finally back to default color... "DarkBlue"

- You can find that although the **custom Alias and Variable** settings will be **cleared when the host is closed**, the **build-in variables** such as $Host will be **permanently changed** if the content is changed.
