# QR Code Generator 🔳

[![Node.js CI](https://img.shields.io/badge/Node.js-Enabled-brightgreen)](https://nodejs.org/)
[![License](https://img.shields.io/badge/license-MIT-blue)](./LICENSE)
[![Made With](https://img.shields.io/badge/made%20with-Node.js-blue.svg)](https://nodejs.org/en)

A simple Node.js CLI tool that generates a QR code from a user-entered URL and saves both the QR image and input to local files.

## 📦 Features

- Prompt user for input using `inquirer`
- Generate a QR code using `qr-image`
- Save the QR code as a `.png` file
- Save original URL to a `.txt` file

## 🚀 How to Run

```bash
npm install
node index.js