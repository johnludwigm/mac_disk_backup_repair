# Backup Disks, Time Machine, and Other Issues on Mac


Disclaimer: I don't work for Apple. Any information you take from this README is at your own risk. Good luck!

`fsck_hfs` is one of the main repair mechanisms. The Disk Utility app's repair mechanism is essentially a GUI for this command.

[O'Reilly link](https://www.oreilly.com/library/view/macintosh-terminal-pocket/9781449328962/re70.html#:~:text=The%20fsck_hfs%20command%20validates%20a,Utility%20in%20the%20Utilities%20folder)

```
sudo diskutil unmount /dev/disk1s2
sudo fsck_hfs -f /dev/disk1s2
```
