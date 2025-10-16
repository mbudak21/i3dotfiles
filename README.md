# i3dotfiles

Minimal configuration for [i3wm](https://i3wm.org/) and [i3blocks](https://github.com/vivien/i3blocks), tuned to my liking.  
The goal is **sane defaults** with just a few quality-of-life tweaks.

---

### i3
- Keybindings are mostly defaults, with:
  - `Super + D` → `dmenu`  
- Everything else is pretty much standard.

### i3blocks
- Uses **Caskaydia Cove Nerd Font**.  
- Status bar labels use **glyphs instead of plain text** for RAM, SSD, etc.
- The bar has interactible elements and supports tray applications.
---

## 📸 Screenshots

**No windows open**  
<img width="2559" height="1599" alt="image" src="https://github.com/user-attachments/assets/7df103b4-4217-4860-8e81-ba0e81306b59" />

**Two terminals with fastfetch**  
<img width="2559" height="1599" alt="image" src="https://github.com/user-attachments/assets/6ea4216d-27b5-4383-bb35-af6d20db0a99" />

---

## Usage

```bash
git clone https://github.com/mbudak21/i3dotfiles
cd i3dotfiles
cp ./i3/config ~/.config/i3/config
cp ./wallpaper.png ~/.config/i3/wallpaper.png

# And now you need to overwrite the i3blocks config.
# Simply copy the files in i3blocks into your config. You may already the i3blocks folder, if you don't install i3blocks.
```

## Dependencies
Make sure you have the **CaskaydiaCove** font and **dmenu** installed.  
Some i3blocks modules (CPU, battery) may also require extra utilities such as `acpi` and `mpstat`.
