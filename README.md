# Automatic Node.js Installation for Windows Instances

This script automates the installation of the latest version of Node.js on Windows instances using PowerShell.

## Usage

1. Copy the PowerShell script provided below.
2. When launching a new Windows instance on AWS, paste this script into the "User Data" field during the instance creation process.
3. Launch the instance and connect to it using RDP.
4. Once connected, Node.js will be automatically installed in the background.

## Description

- This script fetches the latest version of Node.js from the official Node.js website.
- It then downloads the Node.js installer and installs Node.js silently without any user interaction.
- After the installation, the script deletes itself to avoid unnecessary clutter.

