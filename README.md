# 📂 DriveLink – Flutter File Sharing App with Google Cloud

**DriveLink** is a Flutter-based file-sharing application that allows users to upload files, generate QR codes and download links, and easily share files with others. Built using Firebase and Google Cloud, the app ensures secure storage and seamless access to shared content.

---

## ✨ Features

- 🔐 **User Authentication**
  - Google Sign-In
  - Manual Sign-Up (Name, Email, Password)

- 📤 **File Upload**
  - Upload any type of file to cloud storage
  - Support for multiple file selection

- 🔗 **Smart File Sharing**
  - Generate public download links
  - Auto-generate downloadable QR codes
  - Save QR to gallery
  - Copy file link to clipboard

- 📲 **QR Scanner**
  - Scan QR codes to instantly download shared files

- 👤 **Account Management**
  - Secure logout option

---

## 🛠 Tech Stack

| Layer       | Technology                |
|-------------|---------------------------|
| Frontend    | Flutter (Dart)            |
| Backend     | Firebase Authentication, Firestore, Cloud Storage |
| QR Handling | `qr_flutter`, `qr_code_scanner` |
| Utilities   | Firebase Dynamic Links    |
| Hosting     | Firebase Hosting (for file download page) |

---

## 📱 App Flow

1. **Login / Sign-Up Page**
2. **File Upload Screen**
3. **Drive Screen**
   - View Uploaded Files
   - Generate Link & QR
   - Save QR to Gallery
   - Copy Link
4. **QR Scanner**
   - Scan QR → Download File
5. **Logout**

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/YOUR-USERNAME/drivelink.git
cd drivelink
