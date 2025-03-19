# Lab 2: Command Expansion in Linux  

## 📌 Objective  
Understand various types of command expansions in Linux, including history, tilde, and brace expansions, to enhance efficiency in the terminal.  

## 🛠️ Steps  

### 1️⃣ **History Expansion**  
History expansion allows recalling and executing previous commands quickly.  

- **Repeat the last command:**  
  ```bash
  !!
  ```
- **Execute a specific command from history:**  
  ```bash
  !<command-number>
  ```

### 2️⃣ **Tilde Expansion (`~`)**  
The tilde (`~`) symbol represents a user’s home directory.  

- **Navigate to the home directory:**  
  ```bash
  cd ~
  ```
- **Access a specific user’s home directory:**  
  ```bash
  cd ~username
  ```

### 3️⃣ **Brace Expansion (`{}`)**  
Brace expansion generates sequences based on patterns enclosed in curly braces.  

#### **Sequence Expansion**  
- **Generating a range of numbers:**  
  ```bash
  echo {1..5}
  ```
  **Output:** `1 2 3 4 5`  

- **Generating a range of letters:**  
  ```bash
  echo {a..e}
  ```
  **Output:** `a b c d e`  

#### **Using Comma-Separated Values**  
- **Expanding multiple words in a command:**  
  ```bash
  echo {apple,banana,grape}
  ```
  **Output:** `apple banana grape`  

### 📸 **Screenshots for Reference**  
![History Expansion](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/03715a861e1a5a70a815d3150c263289777ee377/Screenshot%202025-01-21%20100055.png)  
![Brace Expansion](https://github.com/deepanshusingla076/G18-Linux-administration-/blob/03715a861e1a5a70a815d3150c263289777ee377/Screenshot%202025-01-21%20100129.png)  

---
