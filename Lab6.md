
# Lab 6: User Management in Linux  

## 📌 Objective  
Learn how to create, manage, and remove users in Linux using `useradd`, `passwd`, `usermod`, and `userdel` commands.  

## 🛠️ Steps  

### 1️⃣ **Create Users**  
Run the following commands to create users:  

```bash
sudo useradd operator11
sudo useradd operator12
sudo useradd operator13
```

### 2️⃣ **Set Passwords for Users**  
Assign passwords to each user:  

```bash
sudo passwd operator11
sudo passwd operator12
sudo passwd operator13
```

### 3️⃣ **Verify That a User Exists**  
Check if `operator1` exists using `/etc/passwd`:  

```bash
grep '^operator11:' /etc/passwd
```

Alternatively, check the last few added users:  

```bash
tail -n 3 /etc/passwd
```

### 4️⃣ **Update User Information**  
Modify the comment field for `operator1`:  

```bash
sudo usermod -c "Primary Operator Account" operator11
```

### 5️⃣ **Remove a User**  
Delete `operator13` from the system:  

```bash
sudo userdel operator13
```

## 🖼️ **Screenshot**  
![image alt](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/38e3c60f809e3442926049ea0e12426f76247314/lab6.png)
