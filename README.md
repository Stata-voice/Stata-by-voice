# Stata-by-voice

**Instructions in Progress - need to make links clickable, complete setup instructions, etc.
 
Code/vocabularies for use with coding in Stata using Dragon NaturallySpeaking
Also, details on installation / setup for nonprogrammers who want to do basic (statistical) coding using Dragon.

Resources I have found useful so far:
Introductory blog posts (start here) http://explosionduck.com/wp/introduction-to-voice-programming-part-one-dns-natlink/


How to get set up:
1) Install Windows 
2) Install Dragon NaturallySpeaking Professional Individual
      Note a) only up through version 14 currently works with NatLink, a crucial piece of software for this all to work
      Note b) Install in default directory to make sure NatLink will work properly
3) Install Python 2.7 [Thanks to simianhacker for details on how to do this: https://github.com/simianhacker/code-by-voice)
      a) Download Python 2.7 (http://sourceforge.net/projects/natlink/files/pythonfornatlink/python2.7.zip/download)
      b) Extract the download
      c) Install python-2.7
      d) Install pywin32-218.win32-py2.7
      e) Install PyXML-0.8.4.win32-py2.7
      f) Install wxPython2.8-win32-ansi-2.8.12.1-py27
4) Add PATH enviroment variable for C:\Python27 and C:\Python27\Script (Right click on computer, click on Advanced system settings, click on Enviroment Variables)
5) Install NatLink (also comes with Vocola and Unimacro) - most up-to-date source: http://qh.antenna.nl/unimacro/index.html
      a) Enable NatLink using the GUI (from Windows Start menu)
6) ...
