# ArchLinux
Helpful commands

hyprland skrypt instalacyjny odrazu skonfigurowany (tylko arch minimalna instalacja najlepiej)
https://github.com/JaKooLit/Arch-Hyprland
poradnik: https://www.youtube.com/watch?v=lR7EtbVYWuc&t=540s

Optymalizacja gier na linux

1. sudo pacman -S gamescope gamemode
2. opcje uruchamiania gry i wkleic to: # gamemoderun gamescope -W 1920 -H 1080 -r 75 --force-grab-cursor -f -- %command%

r = odświerzanie monitora
W = Szerokość
H = Wysokość 

Sterowniki do drukarek
1. sudo pacman -S cups
2. yay -S cnijfilter2 scangearmp2
3. sudo systemctl enable cups
4. sudo systemctl start cups
5. http://localhost:631
