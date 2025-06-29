🔐 Chrome-Password-Dumper — Repository Description
Chrome-Password-Dumper is a Windows-based tool written in C++ that extracts saved passwords from Google Chrome's local user profile. It utilizes Windows APIs to access the encrypted login data stored in Chrome's SQLite database (Login Data), and then decrypts credentials using the CryptUnprotectData function — which leverages the current user's data protection key (DPAPI).

🧩 Key Features:
✅ Offline password dumping from local Chrome user data

🔍 Reads and queries Chrome's Login Data SQLite file

🔓 Uses Windows DPAPI to decrypt stored passwords

💡 Simple C++ implementation with minimal dependencies

🧪 Useful for educational, forensic, or red team research
