# mac-bigsur-read-write-flashdisk
Mac OS bigsur read and write to flashdisk (ntfs), no need to buy 3rd party software :-) 

1. Launch a Terminal, press "Command" and the "Space Bar" at the same time, type “Terminal” and hit the enter key. Then the terminal windows appear.
2. Put the cursor in Terminal, type the following line of code:
```
sudo nano /etc/fstab
```
and put this:
```
LABEL=Data none ntfs rw,auto,nobrowse
```
to terminal.

3. Push "Control" key and the letter “O” key to save this new file, press “Enter” and then press both the "Control" key and the letter “X” key to close the GNU Nano.
4. Unplug the flash drive and then put back the flash drive to the USB flash drive port.
5. To access the files and the drive, ppen "Finder", click on "Go" menu then choose : "folder tab", type in "/Volumes" into the search box. Now, you can see the "Untitled" folder, if not, unplug the flash drive and put back, wait about 15 seconds or more ... be patien ... and voila ... you can see "Untitled" folder.

Just it.
