# win-test-wrapper

Hamradio logging. Starts Win-Test under Linux as known from Windows by typing 'win-test'.

This is a simple wrapper shellscript for calling Win-Test from Linux commandline in the Windows way managed by the debian package management. 

It installs the script calling wine and Win-Test in /usr/bin. It also checks the dependency concerning wine and installs it when it is not present. Have Fun.

Install: 
Download the .deb file, go to the Download dir. Then type
  apt install ./win-test-wrapper

Uninstall:
  apt remove win-test


Wine will be required and automatically installed by package manager if it was not installed before.

It is necessary to install win-test.exe itself in the usual way after
  wine win-test....

If its finishes simple call the program using 
  win-test
on the Linux command line
