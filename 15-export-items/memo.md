# **_Create/Check Item_**

![Alt create folder and check](pic/bandicam%202022-10-09%2004-53-01-505.jpg)

- Get-ChildItem is used to view all items (file or folder) under a specific folder.

# **_Export Object_**

![Alt output result to text file](pic/bandicam%202022-10-09%2004-56-35-993.jpg)

![Alt check content of file](pic/bandicam%202022-10-09%2004-57-05-137.jpg)

![Alt output result to csv](pic/bandicam%202022-10-09%2005-01-43-627.jpg)

![Alt check content of csv](pic/bandicam%202022-10-09%2005-02-32-337.jpg)

- Note that the output file types of Out-File and Export-Csv are fixed, and the given Path should also have the correct subfile name(such as .txt or .csv).

![Alt ouput result to printer/pdf](pic/bandicam%202022-10-09%2005-05-28-800.jpg)

- About exporting PDF, it is not possible to directly give the full path in command to skip the small window step above.
  - There are more complex ways to automatically generate pdfs, but it' s beyond the scope of this lecture.

# **_Remove Items_**

![Alt remove file](pic/bandicam%202022-10-09%2005-11-46-675.jpg)

![Alt remove folder](pic/bandicam%202022-10-09%2005-14-02-590.jpg)

- Remove-Item with **-Recurse** allows the entire process to be uninterrupted by the prompt window above.
