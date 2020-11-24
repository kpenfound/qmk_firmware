# Keeb Iris rev4 Build

Instructions found here: https://docs.keeb.io/iris-rev3-build-guide/

Prep switches.  These are 62g Sakurio for alphanumeric and 67g Tealio V2 from zealpc.net

![prep switches](https://kpenfound-photo.s3.amazonaws.com/PXL_20201120_194631956.jpg)

Disassemble switches and apply 205 lube

![disassemble switches](https://kpenfound-photo.s3.amazonaws.com/PXL_20201120_195753962.jpg)

![lube switches](https://kpenfound-photo.s3.amazonaws.com/PXL_20201120_202331708.jpg)

Prep plates and rotary encoder(s)

![prep plates](https://kpenfound-photo.s3.amazonaws.com/PXL_20201120_215012578.jpg)

Place outer switches in board to align the pcb, then place all switches in the board

![place switches](https://kpenfound-photo.s3.amazonaws.com/PXL_20201121_001040375.jpg)

Solder the switches. This is just 2 pins per switch

![solder switches](https://kpenfound-photo.s3.amazonaws.com/PXL_20201121_001045633.jpg)

Place the posts on the plate and attach the bottom piece

![posts](https://kpenfound-photo.s3.amazonaws.com/PXL_20201121_002158434.jpg)

![bottom](https://kpenfound-photo.s3.amazonaws.com/PXL_20201121_002556753.jpg)

First side done!

![finished side](https://kpenfound-photo.s3.amazonaws.com/PXL_20201121_002605897.jpg)

Repeat on the other side

![outer switches](https://kpenfound-photo.s3.amazonaws.com/PXL_20201121_002857240.jpg)

![all switches](https://kpenfound-photo.s3.amazonaws.com/PXL_20201121_010242799.jpg)

And now the board is assembled

![finished](https://kpenfound-photo.s3.amazonaws.com/PXL_20201123_172543127.jpg)

Now set up qmk: https://beta.docs.qmk.fm/tutorial/newbs_getting_started

And set up your [keymap](./keymap.c)

Then `qmk compile` and `qmk flash`!
