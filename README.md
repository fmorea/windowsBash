# windowsBash

This tool will allow you to use Ubuntu WSL (downloaded from microsoft store) commands directly from windows shell (cmd, powershell  or windows terminal)

How to install
==

Run the following command inside Windows Bash to generate shortcuts for commands
```sh
wget https://raw.githubusercontent.com/fmorea/windowsBash/master/windowsBash -P /usr/bin && chmod 0777 /usr/bin/windowsBash && windowsBash
```

Then just add the following directory to your path in Windows
* C:\windowsBash

When you want to update the commands list just run the Shell file again
```sh
windowsBash
```
