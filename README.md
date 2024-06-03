History Wipe Plugin by NamelessGhoul0

This is a simple plugin I created to automatically clear the logs that the Vita uses to store
what apps you open, etc that are very likely sent to Sony. It will do so every 15 minutes

Now, there has not been anyone banned from using Henkaku (as far as I am aware of)
so this is for those of you that are that are paranoid (or like to take precautions, like myself)

For those curious, here is the list of files that this plugin currently wipes:

- vd0:/history/data.bin
- vd0:/history/data.bak
- ur0:user/00/shell/playlog/playlod.dat
- ur0:user/00/shell/playlog/playlog.dat


Instructions:

- Copy the plugin to ux0:/tai/history_wipe.skprx
- Update your taiHen config (us0:/tai/config.txt) and add the path under *KERNEL like so:
    *KERNEL
    ux0:tai/history_wipe.skprx
- Reboot your Vita
