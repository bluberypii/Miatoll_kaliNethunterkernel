# Miatoll_kaliNethunterkernel
This is a full working kali nethunter kernel for POCO M2 Pro Redmi Note 9S Redmi Note 9 Pro (Global) Redmi Note 9 Pro (India) Redmi Note 9 Pro Max Redmi Note 10 Lite. 
This kernel is built on lineageos(official) 22.1 kernel.

Before installing this kernel change the name for your device (Redmi Note 9 Pro) from anykernel.sh
                        !!!!!!!!!!!!!!!!!!!!!!!!
if you run into error just check your device active slot(its easy just search it if you dont know)
open the anykernel.sh and change the value in

block=/dev/block/bootdevice/by-name/boot;
is_slot_device=0;  (change this value to 1 if you have active slot) 
ramdisk_compression=auto;


and thats it!!!!!!
you should have a working kernel and can use all the modules wifi adapters in kali nethunter 
