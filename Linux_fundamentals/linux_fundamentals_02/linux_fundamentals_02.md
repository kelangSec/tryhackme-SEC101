🐧 Linux Fundamentals – Part 2 Notes

Why Linux Fundamentals 2 Matters

Builds on basic Linux navigation skills

Introduces remote access using SSH

Focuses on permissions, users, and system structure

Essential for cybersecurity and server management



---

Accessing Your Linux Machine Using SSH

SSH (Secure Shell) is used to remotely access Linux systems.

Used in servers, cloud environments, and labs

Provides secure encrypted connection



Basic SSH command

ssh username@IP_address



Used to log into a remote machine securely

Requires username and password or key authentication



---

Introduction to Flags and Switches

Flags (or switches) modify how commands behave

They make commands more flexible and powerful



Example:

ls -l



-l → long listing format



More examples:

ls -a
ls -la



---

Filesystem Interaction Continued

Basic Linux commands:

pwd      → Show current directory
ls       → List files and folders
cd       → Change directory
cat      → View file content
touch    → Create file
mkdir    → Create directory
rm       → Remove files



Key idea:

Linux uses a hierarchical file system

Everything starts from root /



---

Permission 101

Linux permissions control access to files and directories



Permission types:

r → read

w → write

x → execute



Check permissions:

ls -l



Example output:

-rwxr-xr--



Change permissions:

chmod 755 file.sh
chmod u+x file.sh



---

Common Directories

/ → Root directory

/home → User directories

/etc → Configuration files

/var → Logs and variable data

/bin → System binaries

/tmp → Temporary files



---

Key Takeaways

SSH is used for remote access to Linux systems

Flags modify command behavior

Permissions control file security and access

Linux structure is hierarchical and predictable

Understanding directories improves navigation speed



---

Screenshot



![complete](linux-fundamentals-02-done.png)



> Screenshot shows completion of Linux Fundamentals Part 2 on TryHackMe



---

Next: Linux Fundamentals Part 3
