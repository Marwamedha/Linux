# Linux


<div align="center">

# Linux For Data Engineering 

</div>

---

## Table of Contents

- [Main](#main)
- [Apt](#apt)
- [Snap](#snap)
- [Pip](#pip)
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


# Gnome Extension

- **Tiling Assistant**:

---

# Other

- **Chrome**: Download `.deb` package from [official website](https://www.google.com/chrome/)
- **Any Desk**: Download `.deb` package from [official website](https://anydesk.com/tr/downloads/linux)
- **Anaconda**: Download from [official website](https://www.anaconda.com/products/distribution#download-section)
- **Microsoft Azure CLI**: `curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash`
- **ElasticSearch**: Add
  ElasticSearch's [official repository](https://www.elastic.co/guide/en/elasticsearch/reference/current/deb.html)
- **Kibana**: Add Kibana's [official repository](https://www.elastic.co/guide/en/kibana/current/deb.html)
- **Cloudflare WARP**: Download
  from [Cloudflare's website](https://developers.cloudflare.com/warp-client/setting-up/linux/)
- **Cloudflare Zero Trust**: Download
- **Proof General**: Not available via apt/snap
- **Cgoban.jar**: Not available via apt/snap
- **cuDNN**: Not available via apt/snap
- **nvidia-container-cli**: Requires manual installation
