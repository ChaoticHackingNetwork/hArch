# Harch {Hackers Arch} - A quick, simplistic Arch Linux box with a minimal selection of powerful hacking tools, a lightweight hacker OS!!!

Harch is intended for Security Researchers, preferably those who want to get into Penetration Testing/Ethical Hacking but have an old or slow system... The tools(Downloaded during install or after, your choice) are many of the basic but widely used tools out there! The lightweight Arch design speeds up install time as well not having unneeded applications taking up precious resources! **Works great with HypverV or Virtualbox too**

Default Features:

         DE    = I3/MATE 
         DM    = LightDM
         Shell = Fish
  

If you wish to communicate with me on any updates or bugs! Create an issue or find me on Discord: @Chaotic_Guru#8356 or email me @bughunt3r88@outlook.com


__________________________________________________________________________________________________________________________________________________________________

To install, boot into Arch live ISO and:
  
    1. curl -O https://raw.githubusercontent.com/ChaoticHackingNetwork/Harch/main/Harch
    2. chmod +x Harch
    3. ./Harch
    * Some systems show a bad meterpreter if so run: sed -i -e 's/\r$//' Harch 
    4. After Harch install, it will download HarchPOST
    5. arch-chroot /mnt
    6. chmod +x HarchPOST
    7. ./HarchPOST
    8. To install all tools after install run: sudo pacman -S - < Master or Install during boot

Tools will be broken down into categories for a more user preferred system, not every tool is needed. Master tool list is downloaded as of now!!!

    1. Web-Tools = Web App and Network Tools, i.e. Metasploit, Dirbuster etc...
    2. Cracking-Tools = Cracking tools , i.e Hydra, Hashcat etc...
    3. Forensic-Tools = Tools for Forensics, i.e. Maltego, Steghide etc...
    4. Master-toolList = You guessed it, all the tools in one txt file...
    
    
  
