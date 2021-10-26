# ottd-mt32-fix
Work in progress.  I am working on editing the rest.
An edited version of OpenTTD's Base midi music files to be played in Munt (or with real MT32 Unit).  
Original files have terrible instrument selection, and missing tracks.
------------------------------------------------------------------------------------------

INSTALL
-------
Simple process.
SHOULD WORK ON ALL PLATFORMS AND OSs (MAC, WINDOWS, DOS, etc. etc.) 
 
 --------------------------------------------
BACK UP YOUR ORIGINAL FILES BEFORE PROCEEDING
---------------------------------------------

For WINDOWS running steam, dump the midi files into C:/ProgramFiles (x86)/Steam/steamapps/common/OpenTTD/baseset/openmsx-(game version)

Locating the folder without the steam version is the same except you find the install folder wherever OpenTTD is installed.

Not sure with other systems, but it shouldn't be too hard to find.  Just dig around in the OpenTTD install folder.
---------------------------------------------------------------------------------------------------------------------------------

To use these files with Munt (or the MT32 itself) find the correct port your midi device is using and simply change the musicdriver
output in your openttd.cfg to (including quotes) "dmusic:port=(the port number of your device)"

After this, simply load up OpenTTD and enjoy.

---------------------------------------------------------------------------------------------------------------------------------

For further inquiries, please email me at gullne99@gmail.com
