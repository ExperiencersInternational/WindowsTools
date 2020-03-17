Hey! This is an easy access method to the Desktop PC settings in Windows 8/8.1. This can also be used in Windows 10 but theres a better way than that. Anyways what you need to do is download AutoHotKey from https://autohotkey.com and then make a new AHK script and put in the script the following:

^S
Send, #i
Wait, 50
Send, {End}
Wait, 50
Send, {Enter}

END OF SCRIPT (don't actually type this in the script xD)

So anyways let me show you what the whole thing means. ^S basically means Control+Shift+S. Send is to send an input to the computer, the first send is sending the Windows key + I at the same time. The wait command tells the program to wait 50ms. Then the program sends the End key which once the settings thing is open basically moves the selection box to the end of the sidebar. It waits 50ms again and then it presses the Enter key which opens the settings app successfully. This is an easier way of accessing the PC settings app without searching for it or anything and if you want it to come on every time you start your PC put the file into C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp. Press Windows + Shift + S for the script to run whenever you need to open settings. If you plan to redisturbute this use the AHK2exe utility and give it the icon in this folder.

I will be making a proper version of this application so you guys won't have to install AutoHotKey.
