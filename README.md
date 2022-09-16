# hArch {Hackers Arch} 

![image](https://user-images.githubusercontent.com/49621391/189473325-b63e7711-f5bc-4a6e-b19d-6c104306ea1e.png)


A simplistic Linux box, a lightweight hacker OS!!!

Harch is preferably for Security Researchers, specifically those who want to get into Penetration Testing/Reverse Engineering but have an old or slow system. The tools (Downloaded during install or after, your choice) are many of the known but widely used tools out there! The lightweight Arch design is ideal as alot of the bloatware of unneeded applications is not taking up precious resources!

Have an old laptop collecting dust? Throw Harch on it.

Default Features:

         Shell = Fish
         DeskT = I3/MATE 
         Displ = LightDM
        
 **Works great with HypverV or Virtualbox**
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
    
    If you wish to communicate with me on any updates or bugs! Create an issue or find me on Discord: @Chaotic_Guru#8356 or email me @bughunt3r88@outlook.com
  
  
  ｈＡｒｃｈ Ｌｉｎｕｘ
