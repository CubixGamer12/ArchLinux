# ArchLinux  
Helpful Commands and Setup Notes

---

### 🖥️ Hyprland Installation (Arch Minimal)

- **Installation Script:**  
  [https://github.com/JaKooLit/Arch-Hyprland](https://github.com/JaKooLit/Arch-Hyprland)

- **Video Guide:**  
  [YouTube – Hyprland Installation Tutorial](https://www.youtube.com/watch?v=lR7EtbVYWuc&t=540s)

---

### 🎮 Game Optimization on Linux

1. Install required packages:
   ```bash
   sudo pacman -S gamescope gamemode

2. In the game’s launch options, paste:
   ```bash
   gamemoderun gamescope -W 1920 -H 1080 -r 75 --force-grab-cursor -f -- %command%

---

### 🖨️ Printer Drivers (Canon and More)

1. Install CUPS:
   ```bash
   sudo pacman -S cups
2. Install Canon printer and scanner drivers:
   ```bash
   yay -S cnijfilter2 scangearmp2
3. Enable and start the CUPS service:
   ```bash
   sudo systemctl enable cups
   sudo systemctl start cups
4. Open the CUPS configuration in your browser:
   ```bash
   http://localhost:631

---

### 🖥️ Hyprland Weather Setup

1. Open the Startup_Apps.conf
   ```bash
   /home/faniq/.config/hypr/UserConfigs/Startup_Apps.conf

2. Add a line at the end
   ```bash
   exec-once = $UserScripts/Weather.sh

3. Restart your computer


---

