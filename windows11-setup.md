# Windows 11 Setup

## Description
This repository serves as a comprehensive operation manual for setting up a highly efficient Windows 11 development environment. It focuses on creating a unified, keyboard-centric workflow while maintaining mouse accessibility. The setup leverages several powerful tools:

- **OneDrive**: Cloud synchronization for seamless configuration migration
- **uTools**: Efficient productivity enhancement with quick search and automation
- **PowerToys**: Microsoft's power user tools for advanced Windows customization
- **MouseMaster**: Mouse gesture and keyboard simulation for enhanced navigation
- **Fluent Search**: Fast system-wide search and window management
- **AutoControl**: Auto control for mouse and keyboard
- **Cursor**: AI-powered code editor

The documentation includes detailed shortcut configurations, environment setup procedures, and best practices for maintaining a consistent development environment across multiple machines.

**Key Features:**
- 🔄 Unified shortcut system across applications
- ⌨️ Keyboard-first workflow design
- 🖱️ Enhanced mouse operation support
- 🔍 Quick application/window identification
- 🌐 Easy environment migration
- 🎨 Visual workspace organization

**Target Audience:**
- Developers seeking an efficient Windows setup
- Power users looking to optimize their workflow
- Anyone interested in keyboard-centric computing
- Users managing multiple development environments

### Goals
Efficient Windows PC configuration with:
- Unified shortcuts for easy memorization and use
- Easy environment migration
- Keyboard-only operation convenience
- Mouse-only operation convenience
- Quick application identification
- Quick focused window recognition
- Quick input method recognition

### Solutions
###### Unified shortcuts for easy memorization and use
Windows 11 system and common application characteristics:
- Desktop: Windows desktop, multiple desktops can be created
- Window: Application windows, some applications have single instance, others can open multiple instances
- Pane: Window panes within applications, multiple panes can be created; e.g., split screen in Edge, editor groups in VSCode, panes in Windows Terminal
- Tab: Tabs within applications or panes, usually multiple tabs can be opened; e.g., browser tabs, editor tabs, terminal tabs
- Navigation bar: Usually at the top of the window, showing tab addresses; e.g., address bar in Edge, navigation path in VSCode, address bar in File Explorer
- Resource bar: Usually vertical bar on the left side, showing application resource list; e.g., vertical tabs in Edge, explorer in VSCode, navigation pane in File Explorer
- Sidebar: Usually vertical bar on the right side, showing application-specific features; e.g., Copilot sidebar in Edge, GitHub Copilot in VSCode, preview pane in File Explorer
- Console: Usually at the bottom of the window, showing application logs; e.g., console in Edge, terminal in VSCode
- Command: Execute application commands
- Settings: Open system/application settings

Common shortcuts:
- New
    - Window: ctrl+n
    - Pane: 
        - New right: ctrl+.
        - New down: ctrl+,
    - Tab: ctrl+t
- Duplicate
    - Window: alt+n+c
    - Pane: 
        - Duplicate right: alt+.+c
        - Duplicate down: alt+,+c
    - Tab: alt+t+c
- Switch (toggle display/focus)
    - Switch to recent (hold modifier key to use arrow keys for selection)
        - Window: alt+tab
        - Tab: ctrl+tab
    - Switch to previous
        - Window: alt+shift+tab
        - Tab: ctrl+shift+tab
    - Switch to left
        - Pane: alt+left
        - Tab: alt+[
    - Switch to right
        - Pane: alt+right
        - Tab: alt+]
    - Switch to up
        - Pane: alt+up
    - Switch to down
        - Pane: alt+down
- Search and switch to open
    - Window: win+`
    - Same app window: alt+`
    - Tab: ctrl+`
- Search and open from history
    - Same app window: alt+shift+`
    - Tab: ctrl+shift+`
- Close
    - Window: alt+w
    - Pane: alt+/
    - Tab: ctrl+w
- Close all
    - Tabs in pane: ctrl+alt+/
    - Tabs: ctrl+alt+w
- Close others
    - Tabs in pane: ctrl+shift+/
    - Tabs: ctrl+shift+w
- Reopen closed
    - Tab: ctrl+shift+t
- Move tab to
    - New window: alt+t+n
    - (New) window
        - Move right: alt+t+=
        - Move left: alt+t+-
    - New pane:
        - Right: alt+t+.
        - Down: alt+t+,
    - (New) pane
        - Move up: alt+t+up
        - Move down: alt+t+down
        - Move left: alt+t+left
        - Move right: alt+t+right
    - Tab
        - Forward: alt+t+[
        - Backward: alt+t+]
- Move pane to
    - New window: alt+.+n
    - (New) window: 
        - Move right: alt+.+=
        - Move left: alt+.+-
    - Pane
        - Left: alt+.+left
        - Right: alt+.+right
        - Up: alt+.+up
        - Down: alt+.+down
- Pan position:
    - Window:
        - Up: alt+n+e
        - Down: alt+n+d
        - Left: alt+n+s
        - Right: alt+n+f
- Resize
    - Window: 
        - Up: alt+n+i
        - Down: alt+n+k
        - Left: alt+n+j
        - Right: alt+n+l
    - Pane: 
        - Up: alt+.+i
        - Down: alt+.+k
        - Left: alt+.+j
        - Right: alt+.+l
- Merge
    - All windows: ctrl+alt+n+m
    - All panes: ctrl+alt+.+m
    - Current window to next window: alt+n+m
    - Current pane to next pane: alt+.+m
- Open bookmarks bar: alt+\
- Open settings: alt+i
- Execute command: alt+r
- Back: ctrl+[
- Forward: ctrl+]
- Open console: alt+del
- Focus to navigation bar: alt+d
- Search content: ctrl+f
- Rename: ctrl+2
- Focus to resource bar: alt+1
- Focus to sidebar: alt+2

Windows system common shortcuts:
- Snap window to top half: win+alt+up
- Snap window to bottom half: win+alt+down
- Move window to left screen: win+shift+left
- Move window to right screen: win+shift+right
- Peek at desktop: win+,
- Show/hide desktop: win+d
- Open workspace: win+ctrl+`
- Mouse jump: win+q
- Clipboard: win+v
- Lock screen: win+l
- Open quick layout options: win+z
- Voice input: win+h
- Open settings: win+i
- Open widgets: win+w
- Open Game Bar: win+g
- Select on taskbar: win+t
- New desktop: win+ctrl+d
- Switch apps: alt+tab, three-finger swipe
- Switch desktops: win+ctrl+left/right, four-finger swipe
- Maximize or restore all windows except active: win+home
- Minimize all windows: win+m
- Screenshot: win+shift+s
- Screen recording: win+shift+r

AHK available keys:
- Mouse left click: RAlt
- Menu key: RCtrl

Edge common shortcuts:
- Search history tabs: h
- Search bookmarks: \
- Search open tabs and history: `
- Page element location: q

Cursor common shortcuts:
- Add bookmark: ctrl+\
- Editor code location: ctrl+q
- View git history: ctrl+h
- Accept next word of inline suggestion: ctrl+1
- View file history: alt+3
- Focus to git changes: alt+4
- Focus to run and debug: alt+5
- Focus to todo: alt+6
- Open in file explorer: alt+shift+e
- Show active file in explorer view: alt+shift+1
- Go to symbol in editor: ctrl+3
- Refactor: ctrl+6

utools common shortcuts:
- Search and switch windows: win+`
- Search files/folders: win+shift+e
- Clipboard: alt+v
- Search browser bookmarks: win+\

Fluent Search common shortcuts:
- Search screen elements: alt+q

mousemaster common shortcuts:
- Activate screen hint: alt+f
- Activate screen switch: alt+s
- Activate move: alt+e
    - Move: e/s/d/f
    - Activate screen grid: g
    - Activate screen hint: q
    - Switch monitor: tab
    - Slow down: shift
    - Exit: capslock
    - Back: w
    - Forward: r
    - WheelUp: up
    - WheelDown: down
    - WheelLeft: left
    - WheelRight: right
- Click and exit: space
- Mouse left click: RAlt
- Mouse right click: RCtrl

###### Easy environment migration
- Use OneDrive and file links to sync most application configurations and archives
- Use scoop to download and configure environment
- Use Windows system sync, Edge sync, VSCode sync, utools sync
- Edge uses workspace to sync tabs
- Use file links to sync VSCode settings to Cursor and Trae settings

###### Keyboard-only operation convenience
- Set shortcuts
- Use quick tools: utools, Fluent Search, mousemaster

###### Mouse-only operation convenience
- Maintain application accessibility in taskbar and start menu

###### Quick application identification
- Edge uses themes, Edge uses workspace to configure different colors
- VSCode uses peacock to set different instance themes

###### Quick focused window recognition
- Windows applies theme color to window borders

###### Quick input method recognition
- Use DynCursor to dynamically modify cursor style

### Implementation
[Detailed implementation steps are maintained in the original Chinese document]

### Usage
[Simplified setup steps are maintained in the original Chinese document]

### Other Applications
1. AndroidStudio
2. AndroidSDK
3. NDK
4. CMake
5. Keyboard driver software
6. MSI Afterburner
7. Steam
8. Epic
9. RockStar
10. 3dMark
11. Lossless Scaling
12. Leigod Accelerator
13. PICO Connect
14. OpenVPN
15. Feishu 