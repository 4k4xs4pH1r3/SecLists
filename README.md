# For Debian, Ubuntu, Kali or Parrot
```
apt update -y && apt install git -y && cd /usr/share && mv /usr/share/wordlists /usr/share/wordlists_bck && git clone https://github.com/4k4xs4pH1r3/SecLists.git /usr/share/wordlists && cd /usr/share/wordlists_bck/ && mv * -u -f /usr/share/wordlists/ && cd /usr/share/ && git clone https://github.com/danielmiessler/SecLists.git /usr/share/SecLists && cd && apt install neofetch screenfetch -y && neofetch && apt install nmap metasploit-framework asciinema steghide radare2 mtr firmware-realtek net-tools wpasupplicant wireless-tools -y && neofetch && apt-get autoclean && apt install -f && apt -f install && apt autoremove -y && apt-get clean cache && apt update && apt-get autoclean && apt-get clean cache && apt update && apt update -y && apt full-upgrade -y --allow-downgrades && sudo dpkg --configure -a && cd && sudo apt-get install python3 python3-pip -y && neofetch && bash <(wget -qO- https://git.io/vAtmB)
```

# For macOS
```
cd && mkdir ~/wordlists && sudo git clone https://github.com/4k4xs4pH1r3/SecLists.git ~/wordlists && mkdir ~/SecLists && sudo git clone https://github.com/danielmiessler/SecLists.git ~/SecLists && brew install neofetch && neofetch
```
