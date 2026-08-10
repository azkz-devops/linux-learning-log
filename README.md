# linux-learning-log
Record of My Linux Learning — From VirtualBox + Ubuntu Setup to Command Operations. Since August 5, 2026, I have been learning Linux as a fundamental step toward becoming a DevOps engineer.

## 💻 Environment
- PC: Windows (Company PC)
- CPU: 13th Gen Intel Core i7-1365U
- RAM: 16.0 GB
- Storage: 477 GB
- Virtualization: VirtualBox 7.2.14
- OS: Ubuntu 26.04 LTS

## 📅 Learning Log

### Day 1: Environment Setup
- Installed VirtualBox (solved several issues on company PC)
- Downloaded and installed Ubuntu 26.04 LTS
- Configured VM settings (Memory: 4096MB, CPU: 2)
- Changed timezone to JST

**Command used:**
sudo timedatectl set-timezone Asia/Tokyo


### Day 2: Basic Commands
- `ls -la`: list files (detailed + hidden files)
- `cd ~`: go to home directory
- `mkdir`: create folder
- `touch`: create empty file
- `cp`: copy
- `mv`: move or change name
- `rm`: delete
- `rm -r`: delete folder


### Day 3: GitHub Account Setup & Documentation
- Created GitHub account to record learning progress
- Created this README.md to document
- Learned `echo`: display and write text
- Learned `sudo`: execute as root
- Learned `whoami`: confirm the current username
- Learned `cd ..`: go up one directory
- Learned `rmdir`: delete folder
- Learned `mv * ..`: All files move up one directory
- Learned that no space for naming


### Day 4: Ubuntu setting and Command practice
- Changed the clipboard sharing setting in the device settings to 'Bidirectional' so that I could copy documents from Windows.
- Reviewed how to write to files, delete them, and so on.
- Changed the VirtualBox host key combination to Right Alt, since the default was Right Ctrl, which this PC does not have.
- installed the necessary packages to enable Japanese input on Ubuntu.
**Command used:**  
- sudo apt update
- sudo apt install ibus-mozc
- sudo reboot
- head — Displayed only the first 10 lines of a file.
- tail — Displayed only the last 10 lines of a file.
- nano — Edited a file in the terminal. ー＞Save: Ctrl + O ー＞Enter / ー＞Exit: Ctrl + X
- chmod 644 * ー Changing File Permissions / Other users can only read the files in the folder.
- head -n3 ー Displayed only the first 3 lines of a file.
- grep ー Searching for a specific string  Example: 'grep Day 10_Aug_learning.txt' (searching for the word "Day")
