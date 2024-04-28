# Use the latest Arch Linux base image
FROM archlinux:latest

# Update the system and install necessary base packages
RUN pacman -Syu --noconfirm \
    && pacman -S --noconfirm curl base-devel git procps-ng

# Add the BlackArch repository to the system
RUN curl -O https://blackarch.org/strap.sh \
    && chmod +x strap.sh \
    && ./strap.sh --noconfirm \
    && rm strap.sh

# Install specific tools from the BlackArch repository
RUN pacman -S --noconfirm nmap sqlmap dirb gobuster metasploit nikto wireshark-cli hydra john theharvester wpscan zaproxy

# Keeps the container running
CMD ["tail", "-f", "/dev/null"]
