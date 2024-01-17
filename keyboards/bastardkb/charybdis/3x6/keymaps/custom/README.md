# README

## compile and flash firmware using command line

1. `qmk flash -c -kb bastardkb/charybdis/3x6/v2/splinky_3 -km custom`
2. unplug the usb-c
3. unplug the trs connection
4. plug the usb-c
5. press the reset twice when prompt
6. repeat step 1-5 on the other side

## compile, then flash firmware by copy/paste

1. `qmk compile -c -kb bastardkb/charybdis/3x6/v2/splinky_3 -km custom`
2. unplug the usb-c
3. unplug the trs connection
4. plug the usb-c
5. press the reset twice when prompt
6. copy the .uf2 file into the bootloader's drive
6. repeat step 2-5 on the other side
