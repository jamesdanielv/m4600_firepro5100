# m4600_firepro5100
this is clover setup used to get firepro5100 working on laptop

m5100 firepro uses a lot of power during boot, so uninstalling cdrom drive is preffered as powering up may be an issue at times. there may be a way to have firepro use less power at boot, it works without issues in windows but on mac it draws a lot of power at start up.

also you will want to find and download lucidwake 
https://github.com/jamesdanielv/lucidWake
to wake internal monitor up, and also some issues with display resolution so you will want to address that as well i used HiDPI.sh files to make sure resolutions of laptop where supported correctly.

i also added an edid injection for lcd display for dell precision m4600, and it is as follows:


00FFFFFFFFFFFF004CA348540000000000140104902213780AC8959E575492260F505400000001010101010101010101010101010101293680A070381F401810250058C21000001A1C2480A070381F401810250058C21000001A000000FE004A484E58368031353648540A2000000000000041019E0000000002010A20200070


best of luck
