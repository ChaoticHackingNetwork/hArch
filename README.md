# hArch {Hackers Arch} 
Version 1.0.0 

![image](https://user-images.githubusercontent.com/49621391/200466477-b8748c44-53d5-4a98-b5c3-e9af8f4ee700.png)




A simplistic Arch build – your gateway to a streamlined Arch Linux experience designed for speed and efficiency. Whether you're a seasoned security researcher, a bug hunter, or simply a Linux enthusiast looking to breathe new life into aging hardware, hArch guarantees a swift and seamless journey – because your hardware's age shouldn't limit your potential.

Geared towards those delving into penetration testing, reverse engineering, or eager to dive into the Linux ecosystem, hArch offers a curated selection of essential tools, downloaded during installation or at your convenience. And with its bash script foundation, customization is not just encouraged, but celebrated. Make hArch truly yours by tweaking to your heart's content.

Have an old laptop collecting dust? Throw hArch on it. By Default, Networking is not Enabled. 

      systemctl enable dhcpcd                  #Enable Ethernet on Startup
      
      iwctl station list                       #List WiFi Devices
      iwctl station wlan0 scan                 #Scan for WiFI
      iwctl station wlan0 get-networks         #List SSID
      iwctl station connect <SSID>             #Connect
      systemctl enable iwd                     #Enable WiFi on Startup
   

**Works great with HypverV/irtualbox or Bare-Metal... Whatever you prefer** 

The added vimrc file is well... perfection but VSCode/Nvim will still be available as an alternative. Please drop any suggestions on other IDE's as I am always looking too improve or try others. 


![image](https://user-images.githubusercontent.com/49621391/198865669-f8c270ba-19c0-47cb-830b-722c25845d37.png)



Run vim after completion to execute plugin installation...

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
 
At the end of the installation process, you'll encounter a prompt to either download the master toolset or skip. Opting to download the master toolset may extend the installation time by an additional 5-10 minutes. However, this feature will evolve over time with updates. Future iterations will introduce a more user-defined installation process, allowing you to tailor your system more accurately to your needs. For instance, if you're embarking on a reverse engineering task or a web pentest, you can simply select those specific options during installation to receive the necessary tools, streamlining the process and saving time by excluding unnecessary ones.

### To-Do List
- [x] vimrc completed
- [x] Tested bare-metal & Virtual
- [x] Manual partitioning
- [x] Better script UI
- [x] Parallel Downloads w/ Speedtest
- [x] Add Dockerfile for small hackers lab
- [ ] User defined tool set
- [ ] Kernel choice
- [ ] Disk encryption during install
- [ ] URL shortener
- [ ] Fix NVIDIA drivers not working
- [ ] Auto add bootloader
- [ ] Improve Hacker lab
- [ ] 2024 Tools/Wordlist improvements

If you wish to communicate with me on any updates or bugs! Create an issue or find me on Discord: @Chaotic_Guru#8356 or email me @bughunt3r88@outlook.com
  
