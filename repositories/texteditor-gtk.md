[iterami/TextEditor.gtk](https://github.com/iterami/TextEditor.gtk) Documentation
---------------------------------------------------------------------------------

### Shortcuts

Shortcut         | Notes
-----------------|---------------------
Backspace        | Backspace
Ctrl + A         | Select All
Ctrl + Backspace | Delete Previous Word
Ctrl + C         | Copy
Ctrl + D         | Delete Line
Ctrl + Delete    | Delete Next Word
Ctrl + F         | Find/Replace...
Ctrl + G         | Find Next
Ctrl + H         | Replace All
Ctrl + L         | Go to Line...
Ctrl + O         | Open...
Ctrl + Q         | Quit
Ctrl + R         | Sort Lines
Ctrl + S         | Save
Ctrl + Shift + G | Find Previous
Ctrl + Shift + S | Save As...
Ctrl + Shift + Z | Redo
Ctrl + T         | New Tab
Ctrl + V         | Paste
Ctrl + W         | Close Tab
Ctrl + X         | Cut
Ctrl + Y         | Clear Undo/Redo
Ctrl + Z         | Undo
Delete           | Delete
End              | Go to Bottom
Escape           | Hide Windows
Home             | Go to Top
Insert           | Toggle Insertion

---

### Installation

1. `sudo apt-get install libgtk-3-dev`
2. `git clone http://github.com/iterami/common.git` into the same directory as `TextEditor.gtk`.
3. Use your terminal to navigate to the `TextEditor.gtk` directory and `make` it.
4. Run the compiled `texteditor` located at `~/.iterami/texteditor`.

---

### Updating

1. Close `TextEditor.gtk`.
2. `git pull` the `common` and `TextEditor.gtk` repositories.
3. Use your terminal to navigate to the `TextEditor.gtk` directory and `make` it.
4. Run the compiled `texteditor` located at `~/.iterami/texteditor`.

---

### Uninstallation

1. Use your terminal to navigate to the `TextEditor.gtk` directory.
2. `make clean`
3. If you have no other iterami GTK repositories installed, you can delete the `~/.iterami/` directory.
4. Delete the cloned `TextEditor.gtk` directory.
5. Optionally remove `common` and `libgtk-3-dev`.