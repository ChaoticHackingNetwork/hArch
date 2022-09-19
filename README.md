# hArch {Hackers Arch} 
Version 0.1.1

![image](https://user-images.githubusercontent.com/49621391/190882386-5ae0fa75-727b-4046-bee2-84947bec3cbf.png)



A simplistic Arch build, a lightweight hacker distro...

Harch is intended preferably for Security Researchers but open to anyone, it is geared towards those who want to get into Penetration Testing/Reverse Engineering but have an old or slow system. The tools (Downloaded during install or after, your choice) are many of the known but widely used tools out there. The lightweight Arch design is ideal for bringing the older computers to life!

Have an old laptop collecting dust? Throw hArch on it.
        
 **Works great with HypverV or Virtualbox** 

But to get the real experience, use bare-metal :) 
__________________________________________________________________________________________________________________________________________________________________

To install, boot into Arch live ISO and:
  
    1. curl -O https://raw.githubusercontent.com/ChaoticHackingNetwork/hArch/main/hArch
    2. chmod +x hArch
    3. ./hArch
    * Some systems show a bad meterpreter if so run: sed -i -e 's/\r$//' hArch 
    4. After hArch install, it will download hArchPost
    5. arch-chroot /mnt
    6. ./hArchPost
    7. Hack the Universe!
 
~~To install all tools after install run: sudo pacman -S - < Master or Install during boot~~

WIP coming soon with Version 0.1.2


If you wish to communicate with me on any updates or bugs! Create an issue or find me on Discord: @Chaotic_Guru#8356 or email me @bughunt3r88@outlook.com
  
