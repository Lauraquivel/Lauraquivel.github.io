# DANCING

SMP PROTOCOL (Server Message Block protocol (SMB protocol) is **a client-server communication protocol used for sharing access to files, printers, serial ports and other resources on a network**.)

Puerto: **el puerto 445 a través de TCP**.

smbclient -L <ip> : me lista contenido dentro de la ip

smbclient \\\\<ip>\\<nombre de donde me quiero meter> —>me meto dentro de smb

Hago ls para ver lo que hay y descargo con get contenido de lo que hay dentro de Amy.J y James.P.

Salgo de smb y hago cat de lo que me he descargado y ahí encontraré la flag.