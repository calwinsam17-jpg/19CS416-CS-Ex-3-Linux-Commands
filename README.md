# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
<img width="1417" height="202" alt="image" src="https://github.com/user-attachments/assets/f29979a0-e7df-4a7d-ac51-02f2cc8d4fd3" />


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

<img width="403" height="244" alt="image" src="https://github.com/user-attachments/assets/467e9cd8-516a-413e-82a3-585e0a73f9e1" />


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

<img width="764" height="148" alt="image" src="https://github.com/user-attachments/assets/5c6bc406-e290-469d-9d09-e507ce830c78" />


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

<img width="831" height="224" alt="image" src="https://github.com/user-attachments/assets/29ed8117-39de-48fe-951d-50eef8182ff1" />


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

<img width="542" height="184" alt="image" src="https://github.com/user-attachments/assets/2062a1cc-8124-4e5d-a7cb-38ce1d27d83e" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

<img width="344" height="194" alt="image" src="https://github.com/user-attachments/assets/447e6bcc-56b2-4427-afce-7c869d735fa2" />


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="299" height="197" alt="image" src="https://github.com/user-attachments/assets/6d0f12d4-9e2f-4864-ae72-661a6a15e1f5" />


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

<img width="457" height="70" alt="image" src="https://github.com/user-attachments/assets/4bc983e7-18aa-4d2b-95b9-ac328fcf07a3" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

<img width="469" height="178" alt="image" src="https://github.com/user-attachments/assets/421431ad-a4d6-4035-9340-491aeacc6260" />


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

<img width="646" height="568" alt="image" src="https://github.com/user-attachments/assets/1170e4c1-17ed-4b7a-8e0c-68430f7203d0" />


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

<img width="555" height="79" alt="image" src="https://github.com/user-attachments/assets/c1b0c5a8-460a-4368-ad7f-086aad9aeeeb" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
<img width="672" height="449" alt="image" src="https://github.com/user-attachments/assets/42c12f7c-232f-4209-89e7-4d8efc82e143" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

<img width="726" height="454" alt="image" src="https://github.com/user-attachments/assets/e322f684-0844-4a7b-8416-bdf9036d41e1" />


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

<img width="956" height="116" alt="image" src="https://github.com/user-attachments/assets/6caa7713-f7f1-4d63-8f6c-ef89ca01e78c" />


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

<img width="485" height="116" alt="image" src="https://github.com/user-attachments/assets/39c52784-1d3b-43fd-aa44-7c161f6b6b95" />


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

<img width="793" height="504" alt="image" src="https://github.com/user-attachments/assets/0e70a886-075d-4728-9566-0438a1cd4051" />

### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

<img width="286" height="80" alt="image" src="https://github.com/user-attachments/assets/ea109067-ad34-4a48-a763-cd26ab918add" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

<img width="368" height="68" alt="Screenshot 2026-08-21 165924" src="https://github.com/user-attachments/assets/4654c44d-bdeb-4553-b5b2-954dbd219a75" />




### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

<img width="314" height="91" alt="image" src="https://github.com/user-attachments/assets/52f05da3-779c-4d73-b094-dc5a4e218a7d" />

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

<img width="551" height="203" alt="image" src="https://github.com/user-attachments/assets/0a14d594-8a6d-4b5b-8573-e2f7c5869bd9" />


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

<img width="788" height="313" alt="image" src="https://github.com/user-attachments/assets/98ea5fa6-cd70-4bd1-8a84-eb9a539681cd" />


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

<img width="302" height="85" alt="image" src="https://github.com/user-attachments/assets/eebf8e3e-6b77-445e-8001-205c9fecd346" />


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

<img width="921" height="116" alt="image" src="https://github.com/user-attachments/assets/a133cfc0-e6be-40ca-9f06-2f42db16c095" />


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

<img width="569" height="237" alt="image" src="https://github.com/user-attachments/assets/8df4cc12-e7d8-4a53-879e-c11b596a573b" />


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

<img width="305" height="185" alt="image" src="https://github.com/user-attachments/assets/ea17c9e4-2932-4151-8363-e89a979a1e33" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

<img width="325" height="155" alt="image" src="https://github.com/user-attachments/assets/bc7c1f8a-a458-4cdd-b60d-f23b8f57a95c" />


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

<img width="278" height="38" alt="image" src="https://github.com/user-attachments/assets/626e9252-2a9f-4023-9c06-0a673158d588" />


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

<img width="353" height="76" alt="image" src="https://github.com/user-attachments/assets/bdf393ed-0688-4c76-bbc9-ea600780344b" />


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

<img width="781" height="218" alt="image" src="https://github.com/user-attachments/assets/1caca7a7-5677-41af-8d4c-b5e88ad3a280" />


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

<img width="449" height="216" alt="image" src="https://github.com/user-attachments/assets/3620026f-6ca4-414c-91d7-fdd7e874e406" />


## Result
Linux commands are executed in the linux terminal successfully.
