```
xcode-select --install

# PAY ATTENTION TO THE PYTHON VERSION
export PATH="$HOME/Library/Python/3.11/bin:/opt/homebrew/bin:$PATH"

sudo pip3 install --upgrade pip

pip3 install ansible

ansible-galaxy install -r requirements.yml

ansible-playbook main.yml --ask-become-pass
```

---

**System Preference**

- Language & Region
    - Region - United States
        - Other settings
- Add new input language
    - "Language input methods"
        - Add new language

- Change "Keyboard shortcuts"
    - Cleanshot 
        - Disable all keyboard shortcuts under "Screenshots"
    - Raycast
        - Disable all Spotlight shortcuts
    - Input methods
        - Change "... Previous input source" shortcut
            - CMD + SPACE
    - "Modifier Keys"
        - Caps Lock -> Control

- "Trackpad Options" (Accessibility)
    - Use trackpad for dragging
        - Three-Finger Drag
     
- Notification
    - Disable lock screen notification
    - Disable application notifications
 
- Desktop & Dock
    - Automatically hide and show the Dock - ON
    - Show recent applications in Dock - OFF
 
- Privacy & Security
    - FileVault Turn On
        - iCloud or Encryption Key

**Chrome**

- Password Manager
    - "Offer to save password" - OFF
    - "Auto Sign-in" - OFF
- Addresses and more
    - "Save and fill addresses" - OFF

**Moom**

```
defaults import com.manytricks.Moom ~/Download/Moom.plist

# Export the setting config
defaults export com.manytricks.Moom ~/Download/Moom.plist
```
