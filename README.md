# hArch {Hackers Arch} 
Version 0.1.2

![image](https://user-images.githubusercontent.com/49621391/193427466-3750395a-5dab-40d9-8457-87832c460c0a.png)



A simplistic Arch build, a lightweight hacker distro...

Harch is intended preferably for Security Researchers but open to anyone, it is geared towards those who want to get into Penetration Testing/Reverse Engineering or even learn Linux but have an old or slow; maybe even Ancient piece of Technology. The tools (Downloaded during install or after, your choice) are many of the known but widely used tools out there. The lightweight Arch design is ideal for bringing the older computers to life!

Have an old laptop collecting dust? Throw hArch on it.
 
 **Works great with HypverV or Virtualbox** 

But to get the real experience, use bare-metal :) 

The added vimrc file is well... perfection

![image](https://user-images.githubusercontent.com/49621391/193386061-3ff981af-2f7f-4e5e-a1ff-a3ae4dc8cd3f.png)

Vim is the only IDE youll ever need, and this gets you going! Run vim on startup to execute plugin installation.

Checkout - https://realpython.com/vim-and-python-a-match-made-in-heaven/ - if you don't believe me
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
 
The prompt at end will ask to download master toolset or skip. It will add an extra 5-10 min install time. 

### To-Do List
- [x] vimrc completed
- [x] Tested bare-metal & Virtual
- [ ] User defined tool set
- [ ] Disk encryption 
- [ ] url shortener

If you wish to communicate with me on any updates or bugs! Create an issue or find me on Discord: @Chaotic_Guru#8356 or email me @bughunt3r88@outlook.com
  
