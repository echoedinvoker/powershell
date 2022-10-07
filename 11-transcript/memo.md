# **_Start/Stop Transcript by commands_**

![Alt start transcript](pic/bandicam%202022-10-08%2003-04-43-592.jpg)

- The file path of the record is **invisible require parameter**.

![Alt find out text file](pic/bandicam%202022-10-08%2003-05-08-951.jpg)

![Alt open file to check content](pic/bandicam%202022-10-08%2003-05-24-089.jpg)

- Some **metadata** will be written directly after the file is generated.

![Alt random commands](pic/bandicam%202022-10-08%2003-06-06-484.jpg)

- Feel free to enter some commands for it to record.

![Alt recording content](pic/bandicam%202022-10-08%2003-07-16-295.jpg)

- We can see that it will record not only the **commands** itself, but also the **results** generated.

![Alt stop transcript](pic/bandicam%202022-10-08%2003-08-06-838.jpg)

![Alt recording stop](pic/bandicam%202022-10-08%2003-08-34-377.jpg)

- The time point of the end record will also be recorded in the text file.

# **_Transcript automatically_**

> Sometimes people forget to open transcripts or if the system administrator wants to know what powershell commands are used by the people logged into the machine, they can go to the **windows group policy** and open the **automatic transcript configuration**.

![Alt windows+R](pic/bandicam%202022-10-08%2003-09-56-918.jpg)

![Alt grp policy->windows powershell](pic/bandicam%202022-10-08%2003-11-57-652.jpg)

![Alt open powershell transcript](pic/bandicam%202022-10-08%2003-12-34-023.jpg)

- If the directory is active, you can also find this setting in any OU.

![Alt default setting](pic/bandicam%202022-10-08%2003-13-08-672.jpg)

- This feature is turned off by default.

![Alt enable it](pic/bandicam%202022-10-08%2003-13-55-895.jpg)

- Where **//server/share** actually does not know where its absolute path is, still need to clarify.

# **_Create Transcript File to Workspace_**

> If I want to use this feature in **emily skill** and store the records in the **workspace folder** so that other modules can access the contents, how should I specify the text file path?

![Alt $pwd for workspace](pic/bandicam%202022-10-08%2003-21-10-943.jpg)
