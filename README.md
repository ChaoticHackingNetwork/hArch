# hArch {Hackers Arch} 
Version 1.0.0 

![image](https://user-images.githubusercontent.com/49621391/200466477-b8748c44-53d5-4a98-b5c3-e9af8f4ee700.png)




A simplistic Arch build, and a lightweight hacker distro... SPEED and EFFICIENCY is what hArch gurantees. Spin up a hacking VM or bare metal system within minutes **Internet Speed Dependent**

Harch is intended ideally for Security Researchers/Bug Hunters but open to anyone, it is geared towards those who want to get into Penetration Testing/Reverse Engineering or even learn Linux but have an old or slow; maybe even Ancient piece of Technology. Nothing wrong with that either!

The tools (Downloaded during install or after, your choice) are many of the known but widely used tools out there. The lightweight Arch distro is ideal for bringing the older computers to life and this gives you the ability too tweak your system too your liking, I encourage you too make adjustments too the script, its only Bash ;)

Have an old laptop collecting dust? Throw hArch on it. By Default, Networking is not Enabled. 

      systemctl enable dhcpcd                  #Enable Ethernet on Startup
      
      iwctl station list                       #List WiFi Devices
      iwctl station wlan0 scan                 #Scan for WiFI
      iwctl station wlan0 get-networks         #List SSID
      iwctl station connect <SSID>             #Connect
      systemctl enable iwd                     #Enable WiFi on Startup
   

**Works great with HypverV/irtualbox or Bare-Metal... Whatever you prefer** 

The added vimrc file is well... perfection but VSCode will still be available as an alternative. Please drop any suggestions on other IDE's as I am always looking too improve or try others. 


![image](https://user-images.githubusercontent.com/49621391/198865669-f8c270ba-19c0-47cb-830b-722c25845d37.png)



Vim/Nvim is the only IDE/text editor youll ever need,(Unless you too like Sublime :). Run vim on startup to execute plugin installation.

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
- [x] Manual partitioning
- [x] Better script UI
- [x] Parallel Downloads
- [x] Add Dockerfile for small hackers lab
- [ ] User defined tool set
- [ ] Kernel choice
- [ ] Disk encryption during install
- [ ] URL shortener
- [ ] Fix NVIDIA drivers not working
- [ ] Auto add bootloader
- [ ] Improve Hacker lab

If you wish to communicate with me on any updates or bugs! Create an issue or find me on Discord: @Chaotic_Guru#8356 or email me @bughunt3r88@outlook.com
  
