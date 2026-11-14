"How to Unlock the bootloader?"

Alr, I unlocked the bootloader from this xda forums https://xdaforums.com/t/itel-s23-unlock-bootloader-guide-for-windows-based-pc-laptop.4742794/

"How did you do it?"

Use custom recovery, from https://github.com/Massatriof16/recovery-collections/releases/tag/For_s23 
i personally use orangefox, but u can use TWRP or SHRP

"How do you flash it?"

Make sure u have the files from releases, then reboot to recovery (the custom recovery) (if u dont know, just power off the phone, press power button like 2-3 secs then press volume down, after u see the itel logo, let out the power button)
after u got to recovery, flash the "Anykernel3-....zip" (NOT THE IMAGE ONE!). The first reboot may take long

"From the top bar, its like u custom rommed it"

Yes, i did custom rom it

"How to custom rom the Itel S23?"

Well, u need

1. plaform-tools (https://developer.android.com/tools/releases/platform-tools)
2. SPD Driver (https://spddriver.com/)
3. The rom (I personally use corvus os, if you want, https://sourceforge.net/projects/tipzbuilds/files/GSIs/CorvusROM/Official/20221015/Corvus_vS4.0-Leviathan-treble_arm64_ab-Gapps-Official-0103.img.xz/download)

Now, the commands (u can do it without custom recovery)

1. Open cmd through platform-tools (extract it), how? press left click on mouse then u will see "Open Command Prompt", press that (dont run it as administrator)
2. Now, lets start, type adb devices to check it (enable USB Debugging on developer options) then click allow from ur phone
3. If its dont detected, u may didnt install the spd drivers
4. If its detected, type "adb reboot fastboot"
5. In fastbootd mode, type "fastboot delete-logical-partition product_a" then enter, after that, u wanna type the same command (fastboot delete-logical-partition) but changed the product_a to product_b, system_ext_a, system_ext_b (make sure its product_a and product_b first)
6. After that, u type "fastboot flash system " then drag the corvus file to the cmd then press enter
7. After that type "fastboot -w" to wipe ur data
8. Then u can reboot by "fastboot reboot"
9. If its successful congrats
10. If it failed, well, u may did the steps wrong
