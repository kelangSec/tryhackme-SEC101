# 🐧 Linux Fundamentals – Part 2 Notes

## Why Linux Fundamentals 2 Matters
- Builds on basic Linux navigation skills  
- Introduces remote access using SSH  
- Focuses on permissions, users, and system structure  
- Essential for cybersecurity and system administration  

---

## Accessing Your Linux Machine Using SSH

- SSH (Secure Shell) is used to remotely access Linux machines  
- Common in servers, cloud environments, and cybersecurity labs  

ssh username@IP_address

- Used to log into a remote system securely  
- Requires username and password or key authentication  

---

## Introduction to Flags and Switches

- Flags (switches) modify command behavior  
- They make commands more flexible and powerful  

ls -l

- `-l` → long listing format  

ls -a  
ls -la  

- Flags extend command functionality  

---

## Filesystem Interaction Continued

pwd  
ls  
cd  
cat  
touch  
mkdir  
rm  

- Linux uses a hierarchical file structure  
- Everything starts from root `/`  

---

## Permission 101

- Linux permissions control access to files and directories  

r → read  
w → write  
x → execute  

ls -l  

-rwxr-xr--  

chmod 755 file.sh  
chmod u+x file.sh  

- Permissions define who can read, write, or execute files  

---

## Common Directories

/ → Root directory  
/home → User directories  
/etc → Configuration files  
/var → Logs and variable data  
/bin → System binaries  
/tmp → Temporary files  

---

## Key Takeaways

- SSH allows remote access to Linux systems  
- Flags modify how commands behave  
- Permissions control file security  
- Linux is structured in a hierarchical way  
- Understanding directories improves navigation speed  

---

## Screenshot

![complete](linux-fundamentals-02-done.png)

> Screenshot shows completion of Linux Fundamentals Part 2 on TryHackMe  

---

## Next: Linux Fundamentals Part 3
