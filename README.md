# AeroSpace Configuration Overview

This is my config for AeroSpace that leverages Vim bindings and keyboard-driven workflows for efficient window management on macOS.

## Key Concepts

### 1. **Vim-Inspired Navigation**
Window focus and movement use `hjkl` navigation:
- `cmd + ctrl + h/j/k/l`: Move focus left/down/up/right.
- `cmd + ctrl + shift + h/j/k/l`: Move the currently focused window in that direction.

This mirrors the logic of Vim's cursor movement, keeping navigation fluid and intuitive for keyboard users.

---

### 2. **Layout Switching**
Quickly toggle between tiling modes:
- `cmd + ctrl + /`: Set layout to `tiles horizontal vertical`.
- `cmd + ctrl + ,`: Set layout to `accordion horizontal vertical`.

---

### 3. **Smart Resizing**
Resize windows with simple keystrokes:
- `alt + shift + -`: Shrink focused window.
- `alt + shift + =`: Expand focused window.

---

### 4. **Workspace Management**
Workspaces are accessed and organized using familiar patterns:
- `ctrl + cmd + [1–9, A–Z]`: Switch to workspace.
- `ctrl + cmd + shift + [1–9, A–Z]`: Move the focused window to a specific workspace.

Alphabetic workspaces are used to group tasks (e.g., `E` for editors, `P` for productivity, etc.), often tied to application rules.

---

### 5. **Multi-Monitor Support**
- `alt + shift + tab`: Move current workspace to the next monitor (wraps around).
- Specific workspaces are pinned to monitors using `[workspace-to-monitor-force-assignment]`.

---

### 6. **Modal Workflow via Service Mode**
A secondary binding mode (`alt + shift + ;`) enters "Service Mode" for administrative tasks:
- `r`: Reset and flatten layout.
- `f`: Toggle between floating and tiling.
- `backspace`: Close all windows except the current one.
- `alt + shift + hjkl`: Join containers across directions.

---

### 7. **Automated App Assignment**
Common apps are automatically moved to relevant workspaces:
- Terminal apps (`iTerm2`, `Emacs`) go to workspace `E`
- Browsers and productivity tools like Safari, Trello, Notes, etc., are assigned their own workspaces

