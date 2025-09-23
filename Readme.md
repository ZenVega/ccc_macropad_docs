# CCC macropad

## Installation

### QMK Cli

In order to get QMK installed on your system run
'python3 -m pip install qmk'
Test if installation was successfull:
'qmk --version'
If everything works run:
'qmk setup'
this will install the qmk firmware
submit prompts with 'y'

You should now have QMK setup in '~/qmk_firmware'.

### Create new layout
`cd ~/qmk_firmware/keyboards
qmk new-keyboard`

follow the instructions. when it comes to the board, choose, 
->non of the above layouts
->15. promicro_rp2040

your new keyboard's setup should now be created in ~/qmk_firmware/keyboards/<your_keyboards_name_folder>
![image](images/qmk_keyboard_files.png)

when it prompts you: 
MCU = RP2040 #or whatever you are using
bootloader = rp2040 
VIA_ENABLE=yes
