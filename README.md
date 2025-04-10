#                                                 ![image](https://github.com/user-attachments/assets/4154968a-a8fd-4f7e-ac0a-ac461a468c18)  Linux For Data Engineering 


<div align="center">



</div>

---

## Table of Contents

- [Main](#main)
- [Files](#Working-with-Files)
- [Permissions & Ownership](#Permissions-&-Ownership)
- [Archiving & Compression](#Archiving-&-Compression)
-[Package Management)](#Package-Management-(Debian/Ubuntu))
- [Gnome Extension](#gnome-extension)
- [Other](#other)

---

# main

- **autoinstall**:

```bash
sudo ubuntu-drivers autoinstall
```

---

- **lists Director Content**:

```bash
ls 
```

- **Change directory**:

```bash
cd 
```

- **Make directory**:

```bash
mkdir
```

- **Remove files/folders**:

```bash
rm
```

- **Copy files/folders**:

```bash
cp
```

- **Move or rename**:

```bash
mv
```

- **Show current path**:

```bash
pwd
```

- **View file content**:

```bash
cat
```

- **Edit files in terminal**:

```bash
nano
```

- **Remove an Emty Directory**:

```bash
rmdir
```

- **Create empty file**:

```bash
touch
```

- **Display file content**:

```bash
cat
```

- **Show directory structure (install needed)**:

```bash
tree
```

- **Find files by name**:

```bash
find . -name "*.txt" 
```

- **Show file type info**:

```bash
Show file type info
```

- **openssh-server**:

```bash
sudo apt install openssh-server
```
- **Python**:

```bash
sudo apt install python3 python3-pip python3-venv
```
---

# Working with Files

- **View file content**:

```bash
cat <file>
```

- **Scrollable file viewer**:

```bash
less <file>
```

- **# First 10 lines**:

```bash
head <file>
```

- **Last 10 lines**:

```bash
tail <file> 
```

- **Live log viewer**:

```bash
tail -f <file>
```

- **Count lines**:

```bash
wc -l <file> 
```

- **Split text (example with colon delimiter)**:

```bash
cut -d':' -f1 <file>
```

- **Sort lines**:

```bash
sort <file>
```

- **Remove duplicates**:

```bash
uniq <file>
```
---

# Permissions & Ownership

- **Make file executable**:

```bash
chmod +x <file>
```

- **Read/write/execute for owner, read/execute for others**:

```bash
chmod 755 <file>
```

- **Change ownership**:

```bash
chown user:group <file>
```

---
# Archiving & Compression

- **Create tar archive**:

```bash
tar -cvf file.tar dir/  
```

- **Extract tar**:

```bash
tar -xvf file.tar
```

- **Create compressed archive**:

```bash
tar -czvf file.tar.gz dir/
```
---
#  Package Management (Debian/Ubuntu)

- **Update package list**:

```bash
sudo apt update
```

- **Upgrade all packages**:

```bash
sudo apt upgrade
```

- **Install a package & Remove a package**:

```bash
sudo apt install <pkg>
sudo apt remove <pkg>
```
------
#  Shortcuts & Tricks

- **Repeat last command**:

```bash
!! 
```

- **Run last command starting with abc**:

```bash
!abc 
```

- **Cancel running command &Log out of terminal**:

```bash
Ctrl + C
Ctrl + D
```

# Gnome Extension

- **Tiling Assistant**:

---

# Other

-
- **Sources For Study**:https://youtu.be/gojeTqXdBH0?si=JakPynz50ZZmYgWe
