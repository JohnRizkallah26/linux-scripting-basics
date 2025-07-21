# 🐧 Linux Scripting Basics

This repository contains basic Linux shell scripts created as part of a system administration assignment. The focus was on automating user management tasks, practicing control structures like loops, and using executable permissions with `chmod`.

---

## 🧠 Objectives

- Write executable Bash scripts for user management
- Use `for` loops to automate repetitive tasks
- Implement basic error handling and input validation
- Apply `chmod` to manage script permissions

---

## 🛠️ Tools Used

- **Bash & Linux CLI** – for scripting and command-line execution  
- **`useradd` & `passwd`** – to create and configure new users  
- **`for` loop** – for iterating over user creation or task automation  
- **`chmod`** – to set executable permissions on scripts  

---

## 📁 Project Files

- `add_user.sh` – Adds a single user with basic parameters  
- `create_multiple_users.sh` – Uses a `for` loop to create multiple users from a list  
- `new_user_config.sh` – Creates a user and sets default shell, home directory, and password  
- `README.md` – Project overview and usage instructions

---

## 🚀 Usage

Make the scripts executable:
```bash
chmod +x add_user.sh
chmod +x create_multiple_users.sh
chmod +x new_user_config.sh
Run the scripts:

bash
./add_user.sh
./create_multiple_users.sh
./new_user_config.sh
