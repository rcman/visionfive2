# Star Five Vision 2

# IMPORTANT NOTE: You need to running sufficient power or the board will not work. Running a type C cable from a PC is not enough! It needs to be at least 20Watts

I'll be putting my notes and development from this board on here.
<br>
# Ubuntu 24.04 running from NVME on my Star Five Vision 2  

<br>
You need to dig on the internet just to find out how this board boots. <br>
<br>
Downloading an older image just to get it to boot and then you need to update the firmware, like they couldn't do that before they sold it.  How lazy!
<br>
Downloaded the Ubuntu image from Ubuntu.com for this board is all I needed? NOPE!
<br>
<br>

# Update Aug 19th
<br>
After downloaoding the Ubuntu server image, burning to Micro SD card - it booted. The preinstalled image didn't seem to work. I imaged the new image to m.2 drive, left the jumper settings the same and bingo. It boots from sd card makes root(/) the nvme. 
<br><br>
Out of all my current boards,  I would say this one took the least amount of time. The BPI-F3 took over a month to get going. The Sipeed laptop is now back to default, I managed to get it imaged with a nice version of Debian.  
<br>
<br>
Download the Ubuntu [Image](https://cdimage.ubuntu.com/releases/noble/release/ubuntu-24.04-live-server-riscv64.img.gz) Ubuntu 24.04 to the NVME  (NOTE: you will lose all your data) <br> 


![image_67223809](https://github.com/user-attachments/assets/54a324f8-311c-488b-94a9-dd0856c71e20)
<br>
<br>
https://wiki.ubuntu.com/RISC-V/StarFive%20VisionFive%202
<br><br>
![Screenshot from 2024-09-15 18-13-33](https://github.com/user-attachments/assets/60497c29-ec90-4b0b-a9b3-93cd56dcbea6)
<br>
What I am running now! And HDMI works!
<br>
https://rvspace.org/en/project/VisionFive2_Debian_Wiki_202302_Release

<br>
best documentation ever!

<br>
https://github.com/starfive-tech/VisionFive2

