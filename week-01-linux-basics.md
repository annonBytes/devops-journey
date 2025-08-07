# 📚 Week 1: My DevOps Journey Begins with Linux

This week marked the beginning of my DevOps learning journey — and like most people transitioning into this field, I started where many say you should: **Linux**.

## 🚀 What I Set Out to Do
- Get familiar with Linux as an operating system
- Set up my homelab using an old PC
- Understand the boot process and Linux fundamentals

---

## 🖥️ Installed Ubuntu on My Homelab

I chose **Ubuntu 24.04** as my distro — it's beginner-friendly, well-documented, and widely used in production. I turned an old PC into my dedicated **homelab**, and that process alone taught me a lot:

- I ran into some graphical config issues initially
- Learned how to troubleshoot using TTY and logs
- Successfully created a bootable USB using Rufus

---

## 🧱 What I Learned This Week

### 1. Introduction to Linux & Distros
- Linux isn't a single OS — it's a kernel used by many distributions like Ubuntu, Fedora, Arch, etc.
- Ubuntu simplifies a lot, but under the hood, it’s still all about the command line.

### 2. The Linux File System Hierarchy (FHS)
I explored how Linux organizes files:

- `/etc` – config files  
- `/usr` – user-installed programs  
- `/var` – variable data like logs  
- `/home` – user directories  
- `/bin`, `/sbin`, `/boot` – essential binaries and boot files

> Understanding FHS made me realize how structured and purposeful the OS actually is.

### 3. The Boot Process
I broke down what happens when Linux boots:
1. BIOS/UEFI is triggered
2. Bootloader (GRUB) is loaded
3. Kernel is selected and initialized
4. `init` or `systemd` starts system processes

> I used `dmesg` and `journalctl` to view logs during boot — it’s like watching the OS wake up.

### 4. Basic Linux Commands
Getting comfortable with:
- Navigating directories: `ls`, `cd`, `pwd`
- Managing files: `cp`, `mv`, `rm`, `touch`
- Permissions: `chmod`, `chown`
- Viewing system info: `top`, `df`, `free`
- Editing with `vim` (still learning… muscle memory coming slowly)

---

## 📒 Reflections

- Linux makes you **think**. Every action is deliberate.
- I’m already starting to understand how DevOps requires not just knowledge, but patience and curiosity.
- Having a homelab is like owning a safe playground — you *want* to break stuff just to fix it again.

---

## 🔜 What’s Next: Week 2 Goals

- Learn about Vim 
- Install Vim on my Ubuntu homelab
- Write my first line of Vim
- Build muscle memory with CLI

---

Thanks for reading! If you’re on a similar journey or have tips, I’m all ears.  
Let’s build and break things together 💻

**#DevOps #Linux #LearningInPublic #Homelab #Ubuntu #Week1**
