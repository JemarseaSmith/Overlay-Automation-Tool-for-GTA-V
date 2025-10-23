# GTA V Command HUD

This AutoHotkey v2 script creates a real-time command HUD for **GTA V**, allowing players to trigger emotes and server commands without manually typing full command paths. Designed for use with **FiveM**, it streamlines gameplay and roleplay by mapping complex inputs to clean, clickable buttons and hotkeys.

## 🎮 Features
- GUI-based HUD with over 25 mapped commands
- One-click access to emotes, server actions, and roleplay triggers
- Dropdown emote picker with preset animations
- Postal code input with validation
- Real-time execution using AutoHotkey v2
- Position saving via `.ini` files for HUD and submenus
- Hover tooltips for command descriptions
- Toggleable HUD visibility via mouse and hotkeys

## 🧠 Why I Built This
Typing full commands during gameplay was slowing things down and breaking immersion. I built this HUD to automate emotes, server actions, and roleplay commands — making it faster, cleaner, and more intuitive for streamers and players alike.

## 🚀 How It Works
- AutoHotkey v2 handles GUI creation, input mapping, and command execution
- Commands are sent to the active FiveM window using simulated keystrokes
- GUI buttons and dropdowns trigger mapped functions
- HUD and submenu positions are saved between sessions

## 📁 File
- `GTA V Command HUD.ahk` – Main script with GUI logic, command handlers, and input mapping

## ✅ Requirements
- Windows OS (tested on Windows 11)
- [AutoHotkey v2](https://www.autohotkey.com/) installed
- GTA V via FiveM (supports chat-based commands)

## 🛠️ Customization
To modify or expand the HUD:
1. Open `GTA V Command HUD.ahk` in any text editor
2. Add or edit `AddCommand()` entries to include new commands
3. Update emote list in `ShowEmotePicker()` if needed
4. Save and reload the script

## 📸 HUD Display
<img width="190" height="961" alt="image" src="https://github.com/user-attachments/assets/15191d2d-adbe-4505-b651-7b7f7ae2bcc8" />


## 📬 Contact
Questions or feedback? Reach out via jemarseadsmith@gmail.com or connect on [LinkedIn] www.linkedin.com/in/jemarseasmith
