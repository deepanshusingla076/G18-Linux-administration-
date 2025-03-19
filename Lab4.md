# Lab 4: Directory Permissions and User Access Control  

## 📌 Objective  
Learn how to create directories, set permissions using symbolic and octal methods, and configure `umask` for user access control.  

## 🛠️ Steps  

### 1️⃣ **Create the `/home/consultants` Directory**  
Run the following command to create the directory:  

```bash
sudo mkdir /home/consultants
```

### 2️⃣ **Add Write Permission to the `consultants` Group**  
Use symbolic notation to grant group write access:  

```bash
sudo chmod g+w /home/consultants
```

### 3️⃣ **Restrict Access for Others**  
Use the octal method to set strict permissions (no access for others):  

```bash
sudo chmod 770 /home/consultants
```

### 4️⃣ **Create a New User `operator1` and Set Password**  
Run the following commands to add a new user and set their password:  

```bash
sudo useradd operator1
sudo passwd operator1
```

### 5️⃣ **Modify User ID and Configure `umask` for `operator1`**  
Change the user ID and set a restrictive `umask`:  

```bash
sudo usermod -u 0027 operator1
```

Verify the change by switching to `operator1` and checking the `umask`:  

```bash
su - operator1
umask
```

## 🖼️ **Screenshot**  
![image alt](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/6f6440fbbf80493ee289a015d668ab4c708a4b77/lab4.png)
