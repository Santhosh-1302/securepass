# 🔐 SecurePass

A Novel Password Security Algorithm — a browser-based password strength analyzer and salted-hash demonstration.

## 📌 Project Overview

SecurePass is a web-based security demonstration application designed to analyze password strength and demonstrate how salting and hashing can improve password security.

The application runs entirely in the user's browser. No password is sent to an external server.

## ✨ Features

- Password strength analysis
- Entropy estimation in bits
- Password visibility toggle
- Checks for:
  - 12+ characters
  - Lowercase letters
  - Uppercase letters
  - Numbers
  - Symbols
  - Common passwords
- Visual password-strength indicator
- Random salt generation
- SHA-256 hashing using the Web Crypto API
- Responsive design
- Light and dark mode support
- No backend or database required

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Web Crypto API
- GitHub Pages

## 🔐 Password Strength Analysis

The application estimates password entropy based on:

- Password length
- Character-set size
- Repeated characters
- Common password patterns

The password is classified as:

```text
Weak
Fair
Strong
Very Strong
