# 🔐 Password Manager

## 📌 Overview

The **Password Manager** is a simple yet secure Python program that allows users to store and retrieve their passwords safely using **encryption**. It ensures that sensitive information remains protected while providing an easy way to manage multiple passwords. 🛡️  

## 🛠 Features

- 🔑 **Secure Encryption** using `cryptography.fernet`
- 📁 **Stores Passwords** in an encrypted format
- 👀 **View Decrypted Passwords** securely
- 📝 **Easily Add New Credentials**
- 🛑 **Simple Command-Line Interface**

## 📜 Requirements

Ensure you have the following dependencies installed before running the project:

```sh
pip install cryptography
```

## 🖥️ Installation

1. **Clone the repository**:
   ```sh
   git clone <repository_url>
   cd password-manager
   ```
2. **Run the script**:
   ```sh
   python password_manager.py
   ```

## 🎮 How to Use

1. Run the script, and choose an option:
   - **Add** a new password 🔐
   - **View** saved passwords 👀
   - **Quit** the program 🚪
2. If adding a password:
   - Enter the **account name** 📛
   - Enter the **password** 🔑
   - The password is automatically encrypted and saved.
3. If viewing passwords:
   - The stored passwords will be displayed **decrypted** for easy access.

## 🔧 Troubleshooting

### Common Issues & Solutions

- ❌ **Missing Encryption Key (`key.key`)**
  - Ensure the `key.key` file exists before running the script.
  - If missing, uncomment and run the `write_key()` function to generate a new one.
- 🚫 **Incorrect Password Storage**
  - Check if `passwords.txt` exists and is properly formatted.
- 🔄 **Unable to Decrypt Passwords**
  - Ensure the same `key.key` file is used for encryption and decryption.

## 📸 Screenshot

*Coming Soon!* 📷

## 🔒 Security Tips

- **Never share** your `key.key` file. It is the only way to decrypt your passwords.
- Use **strong** passwords with a mix of letters, numbers, and symbols.
- Store your `key.key` file in a secure location **separate** from your passwords.

## 🌟 Future Enhancements

- 🖥️ GUI version using **Tkinter** or **PyQt**
- 📂 Cloud-based password storage with **AES encryption**
- 📱 Mobile app integration for cross-device access

## 🏗️ Contribution

Contributions are welcome! Feel free to **fork** the repository and submit a **pull request**. 🚀

## 📄 License

This project is licensed under the **MIT License**.

---

**Stay Secure & Manage Your Passwords Smartly!** 🔐🛡️

