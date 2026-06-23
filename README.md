CryptoShield

CryptoShield is an advanced Android security tool designed to protect your sensitive files in real-time. By leveraging native C++ implementation and the inotify Linux kernel subsystem, it provides seamless encryption and decryption functionality directly on your device.

🚀 Features
Real-time Protection: Monitors the download directory and automatically encrypts new files using XOR-based encryption.

Native Performance: Core logic is implemented in C++ via JNI for maximum efficiency.

On-Demand Access: Easily decrypt your files with a single click within the application.

Background Security: Operates as a background service to ensure continuous file protection.

🛠 Technical Stack
Language: Kotlin (UI/Framework), C++ (Encryption Engine).

Encryption Method: XOR bitwise operation.

Kernel Monitoring: inotify API for real-time file system event tracking.

Build System: Gradle.

🔐 How it works
The app monitors the /sdcard/Download directory.

When a new file is detected, it is immediately encrypted with a predefined key.

Users can trigger the decryptFolder function to restore original file access.

🛡 Disclaimer
This tool is intended for educational purposes and personal file security. Always maintain backups of your important data.
