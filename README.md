# Windows Environment Variable Cheatsheet

A list of some useful environment variables in Windows.

Variables should be enclosed in %, for example _echo %TEMP%_ on my Windows 10 machine will result in the output _C:\Users\\{username}\AppData\Local\Temp_, obviously replace {username} with your login username. In most cases the case doesn't matter, but for consistancy we's show variables in upper case.

| Variable | Default/Information |
| -------- | ------- |
| USERNAME | your user name |
| USERDOMAIN | The domain or machine name |
| COMPUTERNAME | The machine name |
| NUMBER_OF_PROCESSORS | The number of processors running on the machine |
| DATE | The current date |
| TIME | The current time in TIME format |
| RANDOM | A random number from 0 to 32767 |
| OS | The operating system (Win10 still reports Windows_NT) |
| PATHEXT | .COM;.EXE;.BAT;.CMD;.VBS;.VBE;.JS;.JSE;.WSF;.WSH;.MSC, comma separated exectuable file extensions in order of precedence (left to right) |
| PROCESSOR_ARCHITECTURE | AMD64/IA64/x86 the architecture of the current process |
| PROCESSOR_IDENTIFIER | Processor ID |
| PROCESSOR_LEVEL | Processor level |
| PROCESSOR_REVISION | Processor revision |
| PROMPT | The command prompt format (for example $P$G) |
| ERRORLEVEL | The error value set when a program exits |
| COMSPEC | C:\Windows\System32\cmd.exe |
| LOGONSERVER | \\\{domain} |
| USERDOMAIN_ROAMINGPROFILE | User domain associated with romaing profile |

The follows are default folder locations

| Variable | Folder locations |
| -------- | ------- |
| SYSTEMDRIVE | C: (or whatever your system drive is) |
| CD | The current folder |
| TMP or TEMP     | C:\Users\\{username}\AppData\Local\Temp |
| HOMEDRIVE    | C: |
| HOMEPATH     | \Users\\{username} |
| USERPROFILE | C:\Users\\{username} |
| APPDATA     | C:\Users\\{username}\AppData\Roaming |
| ALLUSERSPROFILE | C:\ProgramData |
| PROGRAMFILES | C:\Program Files |
| PROGRAMFILES(x86) | C:\Program Files (x86) |
| COMMONPROGRAMFILES | C:\Program Files\Common Files |
| COMMONPROGRAMFILES(x86) | C:\Program Files (x86)\Common Files |
| PROGRAMDATA | C:\ProgramData |
| LOCALAPPDATA | C:\Users\\{username}\AppData\Local |
| SYSTEMROOT or WINDIR | C:\windows (Note: WINDIR may be altered so user SYSTEMROOT instead) |
| PUBLIC | C:\Users\Public |
| PATH | Your file search path |
| PSMODULEPATH | C:\Program Files\WindowsPowerShell\Modules;C:\windows\system32\WindowsPowerShell\v1.0\Module |
| ONEDRIVE | C:\Users\\{username}\OneDrive |
| DRIVERDATA | C:\Windows\System32\Drivers\DriverData |
| CMDCMDLINE | Command line used to launch CMD (i.e. "C:\windows\system32\cmd.exe") |
| CMDEXTVERSION | Number of command process extensons for CMD prompt |

Common folder locations (including the %)

| Variable | Folder locations |
| -------- | ------- |
| %USERPROFILE%\Desktop | C:\Users\\{username}\Desktop |
| %USERPROFILE%\Downloads | C:\Users\\{username}\Downloads |
| %USERPROFILE%\Documents | C:\Users\\{username}\Documents |
| %USERPROFILE%\Pictures | C:\Users\\{username}\Pictures |
| %USERPROFILE%\Music | C:\Users\\{username}\Music |
| %USERPROFILE%\Videos | C:\Users\\{username}\Videos |
| %AppData%\Microsoft\Windows\Start Menu\Programs | C:\Users\\{username}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs |
| %AppData%\Microsoft\Windows\Start Menu\Programs\Startup | C:\Users\\{username}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup |

