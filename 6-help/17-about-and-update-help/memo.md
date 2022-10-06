# **_Help files(about\_)_**

![Alt get-help about_](pic/bandicam%202022-10-06%2017-29-15-674.jpg)

- There are some **help files** for commands and modules that start with **about\_**, we can use **get-help** to see their contents as above.

![Alt not only syntax](pic/bandicam%202022-10-06%2017-31-28-092.jpg)

- The contents of these help files are not only particularly in-depth, but there are also some other topics **beyond syntax** that are explored.

![Alt -Detailed](pic/bandicam%202022-10-06%2017-32-57-175.jpg)

- We use the original **get-help + [command]** method to query, and even if we add parameter **-Detailed**, we are still limited to the syntax description

# **_Update help files_**

![Alt update-help issue](pic/bandicam%202022-10-06%2017-41-03-542.jpg)

- These help files are updated even more often than PowerShell itself, and we can use the **update-help** command to update.
- There will be some error messages as above, is a normal situation.

![Alt -Force](pic/bandicam%202022-10-06%2017-41-53-966.jpg)

- The default is to update only once within 24 hours. If you update more than once, the update-help will be completed very quickly and there will be no error message, but in reality, there is no update.
  - We can add parameter **-Force** to force update in 24 hours.

# **_Download help files_**

![Alt create a folder](pic/bandicam%202022-10-06%2017-43-07-592.jpg)

![Alt save-help](pic/bandicam%202022-10-06%2017-44-33-212.jpg)

- When we have to operate poweshell in an **offline environment** and need the **help file**, we can use the **save-help** command to actively download the help file from the network to the specified folder.

![Alt same issue](pic/bandicam%202022-10-06%2017-47-51-555.jpg)

- There is same issue with **update-help**, not big deal.

![Alt help files](pic/bandicam%202022-10-06%2017-44-46-106.jpg)

- The downloaded files are as above.

![Alt files for powershell sys](pic/bandicam%202022-10-06%2017-46-28-075.jpg)

- This is where powershell used to put the help files in default.
- It seems that the downloaded files are not the same as the existing files, so I'm not sure how to update them to powershell.
