# Automatic Emulator Updater
Comes with a graphical interface version and a startup version. Through the graphical interface
you can set the emulator and the directory it is installed in, or the directory you want to
install the emulator to. The startup version of the app can then pull from the setup you created
in the graphical interface in order to update the emulators automatically on the startup of your
machine.

*Currently, the program will only install the 64 bit windows versions of the emulators.

AEUStartup installation instructions:

*Before AEUStartup will work, your emulators and directories need to be setup in the AEU.exe.

- Right click on AEUStartup and click create shortcut.
- Copy or cut it and paste it into the Windows StartUp directory:
   C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
- AEUStartup should then automatically go through its processes on boot based on what was entered in AEU.

You can check what happened during each startup by reading the "updateLog.txt" file
that is created in the same directory where the AEU.exe and AEUStartup.exe files
are located.

*Make sure to keep the AEU.exe and AEUStartup.exe files in the same directory together