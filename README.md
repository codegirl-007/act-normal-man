# Act Normal Man Page

This is a humorous and helpful manual (`act-normal`) that guides users on how to act respectfully and reasonably around others.

## Installation Instructions

Follow the steps below to install the man page on macOS, Linux, or NixOS.

---

1. **Save the File**  
   Save the `act-normal.1` file to your desired location.

2. **Create a Local Man Directory (Optional)**  
   To avoid modifying system directories:
   ```bash
   mkdir -p ~/man/man1

3. **Create a Local Man Directory (Optional)**
   mv act-normal.1 ~/man/man1/

4. **Add the Man Path to Your Environment:**
   Open your shell configuration file (~/.zshrc, ~/.bashrc, etc.) and add:**
   export MANPATH=$HOME/man:$MANPATH

6. **Reload Shell Configuration**
   source ~/.zshrc  # or source ~/.bashrc

7. **Test Man Page**
   man act-normal
