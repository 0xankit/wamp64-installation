# wamp64-installation
## Wamp Installation error fix windows
Errors solved:
1. wamp msvcr120.dll is missing
2. wamp msvcp120.dll is missing
3. wamp msvcr110.dll is missing

Download all three required file from here and verify hash at https://www.dll-files.com/
Place the file to your system directory.
By default, this is
`C:\Windows\System` (Windows 95/98/Me),
`C:\WINNT\System32` (Windows NT/2000), or
`C:\Windows\System32` (Windows XP, Vista, 7, 8, 8.1, 10).
On a 64bit version of Windows, the default folder for 32bit DLL-files is `C:\Windows\SysWOW64\` , and for 64bit dll-files C:\Windows\System32\ .
Make sure to overwrite any existing files (but make a backup copy of the original file).
Reboot your computer.
Then try to start wamp server, if it still doesn't works reinstall.
