<h1>As of July 15th 2022, undetected by windows defender</h1>

<body>
USAGE:

./TestTCP.exe [ip] [port]

OR

(If IP and PORT pre-set in csharp code and recompiled)

<b>Does not need to be ran from command-line:</b>

./TestTCP.exe

--------------------------------------------------------

Issues:

- Internal Windows Shell Commands do not work, yet: cd, dir, etc
- Not persistant.
- Running any command with a menu-submenu system will result in a stall (i.e netsh on its own).
- Windows Defender has not yet detected it however if it does, change the code up and/or encrypt it.

</body>
