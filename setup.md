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

**Personal Preference Setup**

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

**Chrome**

- Password Manager
    - "Offer to save password" - OFF
    - "Auto Sign-in" - Off
