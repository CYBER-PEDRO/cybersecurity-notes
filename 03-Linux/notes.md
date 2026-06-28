# 🐧 Linux Essentials

## What is Linux?
Linux is an open-source operating system widely used for servers, cybersecurity, cloud computing, and penetration testing.

---

## Common Linux Distributions
- Ubuntu
- Debian
- Kali Linux
- Parrot OS
- CentOS
- Fedora

---

## Basic Commands

### Navigation
```bash
pwd      # Show current directory
ls       # List files
cd       # Change directory
mkdir    # Create folder
rmdir    # Remove empty folder
```

### File Management
```bash
touch file.txt
cp file1 file2
mv file1 folder/
rm file.txt
cat file.txt
less file.txt
```

### User Commands
```bash
whoami
id
passwd
sudo
```

### Permissions
```bash
chmod 755 file
chown user:file
```

Permission values:
- 7 = Read + Write + Execute
- 6 = Read + Write
- 5 = Read + Execute
- 4 = Read only

---

## Process Management

```bash
ps
top
kill PID
htop
```

---

## Networking Commands

```bash
ip a
ping google.com
netstat
ss
curl
wget
```

---

## Package Management

Ubuntu/Debian:

```bash
sudo apt update
sudo apt upgrade
sudo apt install package
```

---

## Useful Directories

```
/
 /home
 /etc
 /var
 /tmp
 /usr
 /bin
```

---

## Goals

- [ ] Learn 50 Linux commands
- [ ] Navigate directories confidently
- [ ] Manage users and permissions
- [ ] Understand the Linux filesystem
- [ ] Practice every day
