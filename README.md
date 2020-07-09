# config

## ~/.screenrc
- https://stackoverflow.com/questions/1543427/gnu-screen-changing-the-default-escape-command-key-to-alt-x
  escape ^Zz

## vscode
- https://marketplace.visualstudio.com/items?itemName=tuttieee.emacs-mcx
- // Place your key bindings in this file to override the defaults
Code->Preference->Keyboard Shortcuts->First Icon on the top right corner.
// Place your key bindings in this file to override the defaults
[
    {
        "key": "cmd+y",
        "command": "redo",
        "when": "textInputFocus && !editorReadonly"
      },
      {
        "key": "shift+alt+5",
        "command": "editor.action.startFindReplaceAction"
      },
      {
        "key": "shift+alt+5",
        "command": "-editor.action.startFindReplaceAction",
        "when": "editorFocus && !config.emacs-mcx.useMetaPrefixMacCmd"
      },
      {
        "key": "shift+cmd+5",
        "command": "editor.action.startFindReplaceAction"
      },
      {
        "key": "shift+cmd+5",
        "command": "-editor.action.startFindReplaceAction",
        "when": "config.emacs-mcx.useMetaPrefixMacCmd && editorFocus"
      },
      {
        "key": "escape shift+5",
        "command": "editor.action.startFindReplaceAction"
      },
      {
        "key": "escape shift+5",
        "command": "-editor.action.startFindReplaceAction",
        "when": "config.emacs-mcx.useMetaPrefixEscape && editorFocus"
      },
      {
        "key": "right",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "left",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "up",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "down",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "ctrl+f",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "ctrl+b",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "ctrl+p",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "ctrl+n",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "ctrl+a",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
    },
    {
        "key": "ctrl+e",
        "command": "-emacs-mcx.executeCommands",
        "when": "editorFocus && findWidgetVisible"
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
    - ^+⌘+M: **Zoom**/Maximize
    - ^+⌘+F: Enter/Exit Full Screen
    - ⌘+W: Close Window
    - ⌘+Q: Close App
    - ⌥+⌘+←: **Move Window to Left Side of Screen** (Index finger on ⌘, middle finger null, ring finger on ⌥)
      - ^+⌥+⌘+←: Google Chrome or Brave Browser because they used the default to switch tabs
        - When adding App Shortcuts, choose the application of Google Chrome Or Brave Browser
    - ⌥+⌘+→: **Move Window to Right Side of Screen** (Index finger on ⌘, middle finger null, ring finger on ⌥) 
      - ^+⌥+⌘+→: Google Chrome or Brave Browser because they used the default to switch tabs
        - When adding App Shortcuts, choose the application of Google Chrome Or Brave Browser
    - ⌥+⌘+⇧+←: **Tile Window to Left of Screen** (Index finger on ⌘, middle finger null, ring finger on ⌥)
    - ⌥+⌘+⇧+→: **Tile Window to Right of Screen** (Index finger on ⌘, middle finger null, ring finger on ⌥)
    
  - System
    - ⌘+L: **Lock Screen** (Origin is ⌘+^+Q; Changing by adding "App Shortcuts" titled "Lock Screen")
   
    
- Terminal:
  - Preference: Use Option as Meta Key

## Elementary OS
- Keybord (Mostly same with Mac OS, except ^+⌘ is now ⌘+⌥): 
  - General:
    - ⌘+space: Applications Munu
    - ^+⌥+space: Input Method
  - Workspaces
    - ⌘+↑: Mission Control
    - ⌘+↓: Application windows/current window
    - ⌘+←: Switch to left workspace
    - ⌘+→: Switch to right workspace
    - ⌘+⌥+→: 
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
  - Windows
    - ⌘+M: Minimize
    - ⌘+⌥+M: Toggle Maximized (Toggle means On/Off)
    - ⌘+⌥+F: Toggle Fullscreen
    - ⌘+W: Close Window
    - ⌘+Q: Close App
    - ^+⌘+←: Move Window to Left Side of Screen
    - ^+⌘+→: Move Window to Right Side of Screen
  - System
    - ⌘+L: Lock Screen
    
## Windows 10
- Keyboard
  - General:
    - ⊞+space: Input Method
  - Workspaces
    - ⊞+↹: All workspaces
    - ^+⊞+←: Switch to left workspace
    - ^+⊞+→: Switch to right workspace
    - ^+⊞+D: Create a new workspace (Contrary to MacOS)
    - ^+⊞+F4: Close the current workspace (Contrary to MacOS)
  - Zoom In/Out
    - ⊞+-: Zoom Out
    - ⊞++: Zoom In
  - Screenshot
    - ⊞+⇧+S: screenshot tool
  - Windows
    - ⊞+↑: Maximize
    - ⊞+↓: Minimize
    - ⊞+←: Move Window to Left Side of Screen (Contrary to MacOS)
    - ⊞+→: Move Window to Right Side of Screen (Contrary to MacOS)
    - ⊞+M: Minimize windows
    - ⊞+⇧+M: Restore minimized windows
    - Alt+F4: Close Window

  - System
    - ⊞+L: Lock Screen

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
