# SAMD51-Bootloader-note
my note about update SAMD51 UF2 bootloader<br>

- use JLinkFlash utility
- connect && erase target ATSAMD51J19
- write 2bytes for the D51 Security
- upload bootloader @ 0x0
- reboot

<img src="pic/JlinkBootloaderM4_Notes.png" />



#Reference:
[Flash adafruit uf2 bootloader to grandcentral m4 express board](https://gist.github.com/C47D/b54ea63f30b1e61852514ad6e1177a72)
