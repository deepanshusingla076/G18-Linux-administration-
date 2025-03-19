# Lab 2: Self Expansion in Linux

## 📌 Objective  
Understand and use different types of expansions in Linux, including history expansion, tilde expansion, and brace expansion.

## 🛠️ Steps  

### 1️⃣ **History Expansion**  
History expansion allows you to reuse previously executed commands.  

#### **Execute the Last Command**  
```bash
!!
```
This command reruns the last executed command.  

#### **Execute a Specific Command from History**  
```bash
!n
```
Replace `n` with the command number from the history list to execute it.

---  
### 2️⃣ **Tilde Expansion (~)**  
Tilde `~` is a shortcut for the home directory.  

#### **Navigate to the Home Directory**  
```bash
cd ~
```
This command moves you to your home directory.  

#### **Access a Specific User's Home Directory**  
```bash
cd ~username
```
Replace `username` with the actual username to go to that user’s home directory.  

---  
### 3️⃣ **Brace Expansion**  
Brace expansion generates a sequence of values based on a pattern enclosed in `{}`.

#### **Generate a List of Files**  
```bash
echo file{A,B,C}.txt
```
**Output:** `fileA.txt fileB.txt fileC.txt`

#### **Generate a Numeric Sequence**  
```bash
echo {1..5}
```
**Output:** `1 2 3 4 5`

#### **Generate a Letter Sequence**  
```bash
echo {a..e}
```
**Output:** `a b c d e`

---  
### 4️⃣ **Using the man Command**  
The `man` command displays manual pages for Linux commands.

#### **View the ls Man Page**  
```bash
man ls
```
Displays the manual for `ls` (list directory contents).

#### **Install gedit Using apt**  
```bash
sudo apt install gedit
```
Installs the `gedit` text editor on Debian-based systems.

#### **View the gedit Man Page**  
```bash
man gedit
```
Displays the manual for `gedit`.

#### **Search for Commands Related to ext4**  
```bash
man -k ext4
```
Lists manual pages related to `ext4`.

#### **View the tune2fs Man Page**  
```bash
man tune2fs
```
Displays the manual for `tune2fs`, a tool used to adjust ext2/ext3/ext4 file system parameters.

---  
## 🖼️ **Screenshots**  
![Self Expansion Screenshot](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/03715a861e1a5a70a815d3150c263289777ee377/Screenshot%202025-01-21%20100055.png)  

![History Expansion Screenshot](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/03715a861e1a5a70a815d3150c263289777ee377/Screenshot%202025-01-21%20100129.png)  

![man ls Screenshot](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/82c1c7443747627d0d818c2f4f49d7cee032d7d2/Screenshot%202025-01-21%20122511.png)  

![Install gedit Screenshot](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/81f67d39f6950b3f9032184791f81443a137eb43/Screenshot%202025-01-21%20123210.png)  

![man -k ext Screenshot](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/e4c25b6d08012b0a7cd5674f1b16ad0a33eb694e/Screenshot%202025-01-21%20123954.png)  

![man tune2fs Screenshot](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/e4c25b6d08012b0a7cd5674f1b16ad0a33eb694e/Screenshot%202025-01-21%20124039.png)

