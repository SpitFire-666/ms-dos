<img src="https://user-images.githubusercontent.com/38451588/127482226-e67f4267-7245-4e89-8b6c-4aec09c49c5a.png" width="200" />

# MS-DOS stuff

_Tools, info, links and resources for MS-DOS_


## Recommended software

|SOFTWARE |Desc|Notes|d|
|-|-|-|-|
| EIDL | Places CPU in a HALT state when DOS is idle, allowing the CPU to run cooler | https://www.bttr-software.de/products/eidl/ |  |
| DOSKEY (enhanced!) | With tab autocompletion and other great stuff | http://www.paulhoule.com/doskey/| | 
| Blackout | Screen blanker/saver | Note: place this into a non-"blackout" subfolder otherwise autoexec.bat will not process its parameters correctly. Eg use ```C:\apps\blackout.exe 12``` in ```autoexec.bat``` | |
| UNISOUND | UNISOUND is a Freeware DOS-only tool useful to configure and initialize ISA PnP sound cards from serveral brands and models, like ESS, Creative, ALS, CMI, ADI, Yamaha, Diamond tech, Aztech, OPTi, Crystal, community-made ones like Orpheus, AWE64 Legacy... (And also some non-PnP cards, like early SB16 software configurable models which required DIAGNOSE.EXE, are supported). Works on all x86 CPUs (8088/8086/286/386... and higher) | https://www.vogons.org/viewtopic.php?f=62&t=72553 | 
| FastDOOM |  Doom port for DOS, optimized to be as fast as possible!  | https://github.com/viti95/FastDoom | 
| CuteMouse | Mouse Driver | | |
| DOSMid | Midi Player | | |
| Norton Commander | | | 
| PlayWAV | http://www.fysnet.net | | |
| Treesize | | | 
|  EtherDFS | a network drive for DOS | https://www.vogons.org/viewtopic.php?f=24&t=52260 |

# System info

#### Virtual/protected mode
 
 - To use real mode, comment out HIMEM.SYS from config.sys and reboot

#### CPU

CHKCPU

### Screen Utils

- UltraVision https://www.4dos.info/tools/uv212.zip

![image](https://user-images.githubusercontent.com/38451588/133178127-07499414-f1ad-4479-b9e8-80958b0a954f.png)


http://www.reimagery.com/fsfd/screen.htm#screenmode


# Audio

- http://www.reimagery.com/fsfd/sound.htm#midiplayers

- https://www.cubic.org/player/download.html

- https://www.vogons.org/viewtopic.php?f=24&t=37630

 |--|---|--|
 | | | | |
 |--|--|--|--|
 |MIDIplay | Play MIDI files through PC speaker  |     MIDIplay is a freeware 19K DOS program which plays a MIDI file through a PC's internal speaker. Output is monophonic  | no working links found |
 |SBPlay | SND, VOC, WAV, AIF, IFF, RAW sound files player – no sound card required  | | ftp://ftp.externet.hu/pub/mirror/sac/sound/sbply258.zip |
 | LxVox - Tiny WAV file player (8-bit mono), no sound card required. | http://hplx.pgdn.de/lxvox.zip | | |
 | PlayWAV 1.0 Quick playing of WAV files  | http://www.dreamlandbbs.com/sound/utils/playwav.zip | | | 
 | DOSMid | http://dosmid.sourceforge.net/ | | |


# GUIs

- OpenGEM

![image](https://user-images.githubusercontent.com/38451588/131199150-ce5e09fe-b31c-4d9e-8d96-386a65208200.png)

- COSTA graphical shell:

https://github.com/jacobpalm/costa


# Menus

|SOFTWARE |Desc|c|d|
|-|-|-|-|
| Moo | Doesn't support LFNs (trips up on ~ character which it uses for internal purposes | | |
| 


https://forums.launchbox-app.com/files/file/934-launchbox-for-ms-dos-special-edition/

## 
https://github.com/alespergl/slr/releases/tag/v0.1

## RLoader
https://github.com/marco-sacchi/RLoader


# MS-DOS Tool Alternatives



EDIT: Edit http://wiki.freedos.org/wiki/index.php/Edit

MEM: http://wiki.freedos.org/wiki/index.php/Mem

FREESP - Faster free space/dir listing: https://github.com/ChartreuseK/FREESP


http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/dn2.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/doszip.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/fdshell.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/fdtui.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/paint2.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/pgme.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/group-edit.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/ewsnake.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/flpybird.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/vertigo.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/group-gui.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/cal.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/du.html

https://sourceforge.net/projects/dog/

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/foxcalc.html

http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/pdtree.html


https://github.com/Baron-von-Riedesel/Jemm

# Command Prompt


$e[xx;yy;zzm

where xx = attribute code, yy = foreground color code, and zz = background color code.

```
0 Turn Off Attributes
1 High Intensity
2 Normal Intensity
4 Underline (mono only)
5 Blink
7 Reverse Video
8 Invisible
30 Black
31 Red
32 Green
33 Yellow
34 Blue
35 Magenta
36 Cyan
37 White
40 Black
41 Red
42 Green
43 Yellow
44 Blue
45 Magenta
46 Cyan
47 White
```

- Load ANSI
config.sys
````
  DEVICE = C:\DOS\ANSI.SYS
  ````
PROMPT $e[1;32m$p$g$e[m  

![image](https://user-images.githubusercontent.com/38451588/175847189-2f360671-7655-4490-870f-29378812acf2.png)


INVERTED
  PROMPT $e[7;10m$p$g$e[m  
  
PROMPT $D $B $T$H$H$H $_ $P$G

PROMPT $D $B $T$H$H$H $_ $P$G
  
  
- Merry Christmas
````
prompt $e[1;5;37m  *$_$e[0;32;40m  1$_ $e[1;31;42m u $_$e[33;42m
  x o $e[30;40m$e[K$_  _$_$e[31m MERRY$_CHRISTMAS!$_$e[37m$p$g
````
````
prompt $e[1;32;40m  Z$_$e[33;43m   $e[40m$e[K$_$e[43m    $_
  __ $e[37;40m$e[37;40m$e[K$_ BOO!$_$_$e[35m  $p$g$e[37m
 ````
 ````
 prompt
  $e[44;37;5m$e[16C$e[0;44;1;31m$_111$e[36m111$e[31m111$e[3
  5m11 1\]$_$e[32;5mx x x x x x   x$e[0;1;44;37m$e[1A$p$g
````


https://retrocomputing.stackexchange.com/questions/11073/set-screen-resolution-in-dos-only-pc


## Boot menu

https://retrocomputing.stackexchange.com/questions/6801/how-do-i-create-a-boot-menu-to-select-between-windows-and-dos/6802#6802

https://kb.iu.edu/d/aamm

# FONTS

FONTEDIT: https://www.uselesssoftware.com/download/fontedit-zip

FontEdit is a program which lets you to modify the font used in DOS Text mode with a VGA adapter. It provides a graphical interface in which you can modify the standard DOS font. It is mouse driven, and cannot be run without a mouse.


https://github.com/viler-int10h/Fontraption

https://github.com/viler-int10h/vga-text-mode-fonts


# Hardware


## ISA USB adapter (incl mass storage)

### updated driver (faster)

https://www.vogons.org/viewtopic.php?p=1074259#p1074259

http://www.toughdev.com/content/2018/04/usb-flash-drives-on-8-bit-isa-bus-using-ch375-isb-to-usb-adapter/

https://www.vogons.org/viewtopic.php?f=46&t=43311

https://monotech.fwscart.com/XTCFMini_Bootable_8bit_ISA_CF_Card_Interface/p6083514_19478750.aspx


parallel-port, Ethernet-to-WiFi connectivity.

## 🐁 Mouse

http://cutemouse.sourceforge.net/


# Applications

TheDraw/AcidDraw

https://www.youtube.com/watch?v=iObKua8bdr8

https://dosprograms.info.tt/links.htm




https://winworldpc.com/library/applications/platform-dos

http://www.sysinfolab.com/index.htm
PC Tools, 
CPBackup, 
Autodesk Animator,
VPIC, 
QPEG, 
E3 text editor
QText
EinsteinWriter
Scream Tracker 2/3
Impulse Tracker
Blaster Master 16
TeleMate
Terminate
BlueWave
DESQview

DOS Navigator 


 
# Networking and Internet


http://www.dendarii.co.uk/FAQs/dos-apps.html


## SSH

https://github.com/AnttiTakala/SSH2DOS/

## Internet 

https://github.com/jhhoward/MicroWeb

https://github.com/DrKylstein/retro-proxy -  A https to http proxy that allow old browsers to access modern sites, with conversion and compression options. 

https://github.com/tenox7/wrp


## SMB Networking

http://www.jacco2.dds.nl/samba/dos.html

https://wiki.samba.org/index.php/Configuring_FreeDOS_to_Access_a_Samba_Share

http://www.toughdev.com/content/2018/06/using-microsoft-network-client-3-0-for-ms-dos-with-modern-versions-of-windows/



### Initialise NIC
````
C:\LAN\3C509.COM 0x60
`````

NET.EXE - http://www.ka9q.net/code/ka9qnos/


https://syncterm.bbsdev.net/ -  SyncTERM is a BBS terminal program 


### mTCP

http://www.brutman.com/mTCP/mTCP.html

### Setup

- Create Environment var
````batch
SETMTCPCFG=C:\LAN\CONFIG.CFG
````

- create CONFIG.CFG file (in the folder that SETMTCPCFG points to)
````batch
PACKETINT 0x60
IPADDR 192.168.1.99
NETMASK 255.255.255.0
GATEWAY 192.168.1.1
NAMESERVER 192.168.1.2
````

- DHCP.EXE - Get an IP
````
DCHP.EXE
````

- HTTPSERV.EXE

Hosts a web page, eg http://192.168.1.50/index.htm

````
HTTPSERV -doc_root c:\lan
````

- FTP

Setup an FTP server, eg Xlight FTP Server




# UNSORTED

https://github.com/ChartreuseK/VGASNOW

Necromancer's DOS Navigator, 
ems/xmsdsk, 
mfplay, 
pkzip, 


cd-emulation programs fakecd/fakedr so I don't have to mess with disks...
 
https://github.com/microsoft/GW-BASIC

https://www.vogons.org/viewtopic.php?f=24&t=63514
 
### Graphics, Pictures, and Publishing
- Micrografx Designer (poor man's CorelDraw, but even better IMHO)
- Paint Shop Pro
- ACDSee
- Sea Graphics Viewer with support for high resolution video modes. http://www.dcee.net/Files/Graf/sea11gfx.zip
- QPEG-386 (DOS image viewer, VESA support)
- PictView http://www.pictview.com/pictview.zip
- LxPic http://hplx.pgdn.de/lxpic.zip
- ShowJPG http://www.pictview.com/showjpg.zip
- PixView http://www.cs.unibo.it/~rossi/pixview/pixv23.zip
- LWhiz ftp://ftp.sac.sk/sac/graph/lwhiz.zip
- PrintMaster and BannerMania (kind of a very basic publishing programs (banners, greeting cards, etc.)

### Office:
- PFS Professional Write Plus (DOS word processor)
- Microsoft Word 2.0
- Microsoft Excel 3.0
- Recognita Select (OCR) 
- Ami Pro
- Quatro Pro, from time to time)

### Engineering:
- AutoCAD 12 (DOS and Windows 3.1)
- Easyplot
- Matlab 3.5 SE
- Mathcad 6
- Lahey FORTRAN
- QuickBasic

### Utilities:
- Stacker
- Colorado Backup
- QEMM
- Norton Utilities
- Checkit Pro
- PCTools
- DiskCopyFast
- F-Prot
- Ontrack Disk Manager
- XTree Gold
- Volkov Commander 
- Electronics Workbench
- TreeSize: http://www.cnd.org/HYPLAN/yawei/freesoft.html
 
 https://www.vogons.org/viewtopic.php?f=63&t=58922
 
 

Arachne web browser:

http://www.glennmcc.org/


# Graphics

VMODE
 
 
# GAMES

https://www.vogons.org/viewtopic.php?f=61&t=81589

https://www.vogons.org/viewtopic.php?f=61&t=82495

- http://www.pixelships.com/adg/
- https://github.com/viti95/FastDoom
- https://www.vogons.org/viewtopic.php?f=61&t=61035&hilit=t3100&start=160
- The Catacomb Abyss 3D
- LHX attack chopper
- Wings of Fury
- Paganitzu 
- Pinball Night Mission
- http://www.mobygames.com/game/mach-3/
- https://en.wikipedia.org/wiki/PopCorn_%28video_game%29
- Colorado, 
- Targhan,
- Starblade, 
- Metal Mutant - all great 2D games from French developer Silmarils. They all work on both CGA and Hercules
- North & South - ton of fun and local multiplayer possible. CGA & HGC both.
- Prince of Persia - timeless classic. Native CGA and Hercules support.
- Prehistoric - tough as nails, but I have a soft spot for it. Native CGA and Hercules support.
- BlockOut - 3D Tetris clone. Not that great today, but played a hell out of it as a kid. Native CGA and Hercules support.
- Budokan - nostalgia factor mostly for me, but still can be enjoyable in small doses. Native CGA and Hercules support.
-  Digger - quick, fun, works via SimCGA (you have to jump through a few hoops) on Herc.
- Sokoban - did not like it too much as a kid, but appreciate logic games more now. Native CGA and Hercules support.
- Korean Dungeon Boy
- Street rod
- Arctic Fox
- OutRun
- California Games
- Pinball Dreams
- https://github.com/nanochess
- https://www.youtube.com/watch?v=TE6SkrEFcoI
- https://www.youtube.com/c/dosnostalgic/videos

## DEMOS

https://www.dropbox.com/s/df1h2w2zapo2kpv/crystfix.zip?dl=0

http://www.oldskool.org/demos/explained/demo_reviews.html
 
## QBasic

https://www.youtube.com/watch?v=sqy7Xfklo7w

https://forum.thegamecreators.com/thread/222397

http://www.petesqbsite.com/downloads/graphics.shtml

# Convert a VirtualBox VM to a physical disk

```
"C:\Program Files\Oracle\VirtualBox\vboxmanage" internalcommands converttoraw DOS-256MB.vdi DOS-256.img
```


# References 


https://www.vogons.org/viewtopic.php?f=24&t=82258

http://reimagery.com/fsfd/#siteidx

https://www.danielsays.com/ssg-dos.html

http://www.dcee.net/Files/Graf/

https://www.danielsays.com/ssg-dos-mace1.html

https://www.danielsays.com/ssg-dos-fs.html

https://www.vcfed.org/forum/forum/genres/pcs-and-clones/15399-ms-word-5-5-for-dos-for-free-legally?15238-MS-Word-5-5-for-DOS-for-FREE-(legally)=

https://www.fltk.org/index.php

https://winworldpc.com/product/pc-speaker-driver-wi/pc-speaker-driver-windows-31


https://www.vogons.org/viewtopic.php?f=24&t=82258

https://github.com/zerokelvinkeyboard/tachyonos

https://sourceforge.net/projects/michalos/

 https://sourceforge.net/projects/zexos/
 
 https://www.mdgx.com/dos.htm#DOS
 
 NewDeal Office 3.2a


http://www.doshaven.eu/released/2007/



https://archive.org/details/softwarelibrary_msdos_texteditors

http://www.bttr-software.de/freesoft/

https://www.uwe-sieber.de/english.html

http://mpxplay.sourceforge.net/

https://www.4dos.info/dalter.htm

http://www.resoo.org/docs/dos/free_software/fileman1.htm

http://ndn.muxe.com/

http://dosprograms.info.tt/utils.htm

https://archive.org/details/softwarelibrary_msdos

http://www.reimagery.com/fsfd/#siteidx

https://www.tindie.com/products/theoldnet/rs232-serial-wifi-modem-for-vintage-computers-v3/

https://www.youtube.com/watch?v=S35-jFSMEf8
