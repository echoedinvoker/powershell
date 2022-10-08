![alt](pic/bandicam%202022-10-09%2005-41-57-880.jpg)

- There are two technologies help you to **connect** to the **hardware or software** on a computer(**local or remote**):

  - **WMI**(Legacy)
    - use **DCOM**(distributed component object model)
      - its downside is requre **RPC**(remote procedure call)
        - it must be allowed by the **firewall** of machine for connections.
  - **CIM**(Newer)
    - have a few different ways to connect machine:
      - **DCOM** - CIM can use legacy way, too.
      - **HTTP** - eliminates the need for firewall's exceptions for remote procedure call and other things.
      - **WS-MAN**(workstaion manager) - All I need on the firewall of this computer, the only exception is **Windows Remote Management**.

- Two technologies have same end - **WMI Repository**.
  -It is one **general repository** which has all the **classes** that let us **connect** to and **manage** **hardware or software** on the machine.

- Our courses will focus on the **CIM** section.
