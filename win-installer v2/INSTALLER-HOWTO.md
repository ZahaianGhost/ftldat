How to create the Windows installer
-----------------------------------

First you will need the following:
   *  NSIS (http://nsis.sourceforge.net/Main_Page).
   *  PyInstaller (http://www.pyinstaller.org/).
   *  PyWin32 (http://sourceforge.net/projects/pywin32/files/pywin32/Build%20218/).
   *  Python 2.* (http://python.org/download/).

Then do the following:
   
1. Open a command prompt.  Go to this folder via the prompt (e.g. c:\ftldat\Win-Installer). And run PyInstaller with the following command:
   
   c:\python27\python.exe path\to\pyinstaller.py ftldat.spec
   
2. Check whether the version in ftldat.nsi is OK.
3. Run NSIS, by rightclicking on ftldat.nsi and using "Compile NSIS Script".
4. Test installer and voila, it should be installed. Cheers, you've just manually compiled a functional installer!
