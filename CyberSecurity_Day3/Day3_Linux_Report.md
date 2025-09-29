# Linux Practice Report – Day 3
*Date: Monday, September 29, 2025*  
*Author: [Your Name]*  

---

## 🎯 Objective
The goal of this exercise was to practice using the **Linux Command Line Interface (CLI)** and to understand the fundamentals of **file permissions**. These are critical skills for both system administration and cybersecurity.

---

## 🛠️ Tools and Setup
- **Environment:** Ubuntu via WSL (Windows Subsystem for Linux)  
- **Shell:** Bash  
- **Commands practiced:** `ls`, `pwd`, `cd`, `touch`, `mkdir`, `cp`, `mv`, `rm`, `chmod`, `chown`

---

## 📌 Methodology

### 1. Basic CLI Navigation
- Checked working directory with `pwd`  
- Listed files using `ls` and `ls -l`  
- Created files and directories (`touch`, `mkdir`)  
- Copied and moved files (`cp`, `mv`)  
- Deleted files with `rm`  

### 2. File Permissions
- Observed file permissions with `ls -l`  
  Example output:  
-rw-r--r-- 1 teguh users 120 Sep 29 secret.txt
- Understood permission breakdown:
- `rw-` → owner can read/write  
- `r--` → group can only read  
- `r--` → others can only read  

### 3. Modifying Permissions
- Changed permissions with numeric mode:  
```bash
chmod 644 secret.txt

Exercises 
Created a working directory:

-mkdir day3
-cd day3


Created secret.txt:

-echo "My first Linux practice" > secret.txt


Set permissions:

-chmod 644 secret.txt


Created an executable script hello.sh:

-echo 'echo "Hello Cybersecurity!"' > hello.sh
-chmod +x hello.sh
-./hello.sh


Output:

Hello Cybersecurity!

Conclusion 
Day 3 established a foundation in Linux navigation and file permissions.
Key takeaways:

-Confidently navigate Linux via CLI.

-Manage file access with chmod and chown.

-Write and execute basic shell scripts.

These skills are fundamental for cybersecurity professionals who often work in Linux environments.