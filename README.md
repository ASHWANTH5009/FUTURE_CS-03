# 🔐 Secure File Sharing System using Python

A secure file sharing application built with Python, focused on ensuring **confidentiality**, **integrity**, and **authentication** of files shared over a network. This project leverages cryptographic methods such as AES, RSA, and hashing to provide a safe environment for file transmission.

---

## 📌 Features

- 🔒 **AES Encryption**: Symmetric encryption for securing file contents.
- 🔐 **RSA Encryption**: Asymmetric encryption for secure key exchange.
- 🧾 **Hashing (SHA-256)**: Ensures file integrity through hash validation.
- 👤 **Authentication**: Basic sender/receiver authentication system.
- 🌐 **Socket Communication**: Client-server architecture for sending/receiving encrypted files.

---

## 🛠️ Technologies Used

- Python 3.x
- `socket` – for network communication
- `cryptography` – for AES/RSA encryption
- `hashlib` – for hashing
- `os` & `sys` – for file handling and command-line operations

---

## 📁 Project Structure

secure-file-sharing/
│
├── client.py # Client-side script
├── server.py # Server-side script
├── crypto_utils.py # Cryptographic functions (AES, RSA, hashing)
├── README.md # Project documentation
├── requirements.txt # Dependencies
└── sample_files/ # Example files for testing


---

## 🚀 Getting Started

🔧 Configuration:

> Default host: 127.0.0.1

> Default port: 5000

> You can modify these in server.py and client.py as needed.

✅ Use Case

This project is useful for:

> Learning network and cryptographic security.

> Building a secure file exchange tool within trusted environments.

> Demonstrating concepts in cybersecurity interviews or academic projects.

🔒 Security Considerations:

> Key pairs should be generated securely and stored safely.

> In a production setup, secure transport layers (like TLS) should be added.

> Authentication and access control can be expanded using user tokens or certificates.

📈 Future Improvements:

> GUI interface using Tkinter or PyQt.

> Integration with secure cloud storage (e.g., AWS S3 with encryption).

> Multi-user access control and file history logs.

> Support for large files via chunked transfers.




🧑‍💻 Author
|
 Ashwanth P.G
 
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

