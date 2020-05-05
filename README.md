# config

## ~/.screenrc
- https://stackoverflow.com/questions/1543427/gnu-screen-changing-the-default-escape-command-key-to-alt-x
  escape ^Zz

## vscode
- https://marketplace.visualstudio.com/items?itemName=tuttieee.emacs-mcx
- // Place your key bindings in this file to override the defaults
[
    {
        "key": "cmd+y",
        "command": "redo",
        "when": "textInputFocus && !editorReadonly"
      }
]

## MacOS
- Keybord (Shortcuts can also be found in application menus): 
  - Modify Keys: Swith ^control and ⌥alt/option
  - General:
    - ⌘+space: Spotlight
    - ^+⌥+space: Input Method
    - ^+⌘+D: Turn Dock On/Off
  - Mission Control/Workspaces
    - ⌘+↑: Mission Control
    - ⌘+↓: Application windows/current window
    - ⌘+←: Switch to left workspace
    - ⌘+→: Switch to right workspace
    - ⌘+D: Show Desktop
  - Zoom In/Out
    - ^+⌘+0: Zoom On/Off
    - ^+⌘+-: Zoom Out
    - ^+⌘++: Zoom In
  - Screenshot
    - ^+⌘+⇧+1: Save screen as a file
    - ^+⌘+1: Copy screen to clipboard
    - ^+⌘+⇧+3: Save area as a file
    - ^+⌘+3: Copy area to clipboard
    - ^+⌘+⇧+5: Show screenshot options
  - Window (**Bold** is the Menu Title when adding App Shortcuts)
    - ⌘+M: Minimize
    - ^+⌘+M: **Zoom**
    - ^+⌘+F: Enter/Exit Full Screen
    - ⌘+W: Close Window
    - ⌘+Q: Close App
    - ⌥+⌘+←: **Move Window to Left Side of Screen** (Index finger on ⌘, middle finger null, ring finger on ⌥)
    - ⌥+⌘+→: **Move Window to Right Side of Screen** (Index finger on ⌘, middle finger null, ring finger on ⌥)    
    - ⌥+⌘+⇧+←: **Tile Window to Left of Screen** (Index finger on ⌘, middle finger null, ring finger on ⌥)
    - ⌥+⌘+⇧+→: **Tile Window to Right of Screen** (Index finger on ⌘, middle finger null, ring finger on ⌥)
  - System
    - ⌘+L: **Lock Screen** (Origin is ⌘+^+Q; Changing by adding "App Shortcuts" titled "Lock Screen")
   
    
- Terminal:
  - Preference: Use Option as Meta Key
  - 

## Elementary OS
- Keybord (Mostly same with Mac OS, except ^+⌘ is now ⌘+⌥): 
  - General:
    - ⌘+space: Applications Munu
    - ^+⌥+space: Input Method
    - ^+⌘+D: Turn Dock On/Off
  - Workspaces
    - ⌘+↑: Mission Control
    - ⌘+↓: Application windows/current window
    - ⌘+←: Switch to left workspace
    - ⌘+→: Switch to right workspace
    - ⌘+D: Show Desktop
  - Zoom In/Out
    - ⌘+⌥+-: Zoom Out
    - ⌘+⌥++: Zoom In
  - Screenshot
    - ⌘+⌥+⇧+1: Save screen as a file
    - ⌘+⌥+1: Copy screen to clipboard
    - ⌘+⌥+⇧+2: Save window as a file
    - ⌘+⌥+2: Copy window to clipboard
    - ⌘+⌥+⇧+3: Save area as a file
    - ⌘+⌥+3: Copy area to clipboard
  - Window
    - ⌘+M: Minimize
    - ⌘+⌥+M: Maximize/Full Screen
    - ⌘+⇧+M: Unmaximize
  - System
    - ⌘+L: Lock Screen
    - 

## Windows 10
- Activation: hyw@umd.edu; Office 365: hyw@umd.edu
- Dual Boot: Easy BCD (not necessary because Linux grub is good enough: just do sudo update-grub)
  1. Add a new entry
  2. Advanced Settings: Changed Linux driver to Boot 
  After installation of Linux
  - Not working because it is ubuntu: bcdedit /set "{bootmgr}" path \EFI\ubuntu\grubx64.efi
- Powershell
  - Download latest powershell
- Emacs
  - Download emacsxxx.zip file; unzip; and copy the content to Program Files
  - Search "Environment Variables" on Windows Search and add a new path entry C:\Program Files\emacs-26.3-x86_64\bin\
  
## Elementary OS
- Dual Boot: 
  - **boot-repair** fixes everything and can be used on live usb:
    - install **boot-repair** and use recommend repairs
      - https://askubuntu.com/questions/226061/how-to-install-the-boot-repair-tool-in-an-ubuntu-live-disc
        (Don't copy the second apt-add-repository)
  - sudo update-grub: fix broken ones
  - Optional: grub-customizer (add ppa) Installing Linux after Windows        
        
  - Disks
    - 3 paritions
      1. / primary partition like /dev/sda1 (sda1-sda4 for primary paritions)
      2. /home home partition like /dev/sda5 (starting from sda5, logical partitions)
      3. swap area like /dev/sda6. RAM size
      (/dev/sda1: dev -> device; sda1 -> s device (SCSI and also h device), a (first devie), 1-4 primary partitions
- Deb packags:
  - sudo dpkg -i xxx.deb
  - install gdebi from app store
    - sudo gdebi google-chrome-stable_current_amd64.deb 
- Emacs
  - fix crash out on startup: https://elementaryos.stackexchange.com/questions/797/how-to-get-gnu-emacs-work-on-elementary-os
  - in your .bash_aliases file: alias emacs='XLIB_SKIP_ARGB_VISUALS=1 emacs' and then source ~/.bashrc
  - remove emacs (need to have a version number):
    - sudo apt remove --autoremove emacs25 emacs25-nox
