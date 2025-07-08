# 🛡️ Parrot OS Post-Install Automation Script

### ⚙️ Automate Your Ethical Hacking Toolkit Setup  
**By: Syed Muneeb Ur Rehman**

This Bash script automates the essential setup of penetration testing tools on a fresh **Parrot OS** installation. Whether you're a student, cybersecurity engineer, or CTF player — save time by skipping manual installs and jump straight into hacking.

---

## 🚀 Features

- ✅ Adds and configures Parrot security repositories  
- ✅ Updates and upgrades the system  
- ✅ Installs essential security & red team tools  
- ✅ Downloads popular wordlists (rockyou, SecLists, etc.)  
- ✅ Sets proper folder permissions  
- ✅ Checks internet connectivity  
- ✅ Displays author info and interactive CLI menu  

---

## 📸 Terminal Preview

> 📷 **Screenshot Here**  
> *![image](https://github.com/user-attachments/assets/31615e19-0e5b-41ad-ace6-278baa21cba3)*

```
#############################################
#                                           #
#     Author: Syed Muneeb Ur Rehman        #
#                                           #
#############################################

 [i] Install Menu – Choose steps in order:

   [1]  Update and upgrade
   [2]  Add Parrot tools to apt
   [3]  Change PPA permissions manually
   [4]  Update and upgrade again
   [5]  Install tools
   [6]  Clean system
   [7]  Set folders permissions

   [q]  Exit
```

---

## 🛠️ Installation

> 🧠 This script is designed for **Parrot OS**. Please run it as **root**.

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/parrot-auto-setup.git
cd parrot-auto-setup
```

### 2. Make the Script Executable
```bash
chmod +x setup.sh
```

### 3. Run the Script
```bash
sudo ./setup.sh
```

---

## 📁 Directory Layout

| Path                        | Description                          |
|-----------------------------|--------------------------------------|
| `/usr/share/wordlists/`     | Common wordlists (SecLists, rockyou) |
| `/opt/`                     | Toolkits like impacket, pspy         |
| `/usr/share/webshells/`     | Webshells like reGeorg, p0wny        |
| `/etc/theHarvester/`        | theHarvester OSINT tool              |

---

## 🧰 Tools Included (Highlights)

- 🔍 `nmap`, `masscan`, `sqlmap`, `dnsenum`, `whois`
- 🔐 `john`, `hydra`, `cewl`, `hashcat`, `crunch`
- 🌐 `wpscan`, `gobuster`, `dirbuster`, `wfuzz`
- 📡 `evil-winrm`, `impacket`, `theHarvester`, `pspy`
- 🕸️ `reGeorg`, `p0wny-shell`, `nikto`, `smbmap`
- 📁 Wordlists: `SecLists`, `rockyou.txt`, `usernames.txt`

---

## 🔐 Wordlists Installed

- [x] `rockyou.txt`  
- [x] `SecLists` (Full)  
- [x] `usernames.txt`  
- [x] `dirbuster` lists  

---

## 👨‍💻 Author

**Syed Muneeb Ur Rehman**  
Cybersecurity Engineer | Instructor | Tool Developer  
🌐 GitHub: [github.com/yourusername](https://github.com/yourusername)  
🔗 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).  
Use responsibly — for **educational and ethical purposes only**.
