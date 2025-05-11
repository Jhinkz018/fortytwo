# FortyTwo Network Console App

This repository contains installation instructions and helper scripts for setting up the FortyTwo Network console application on Linux systems.

## 🚀 Quick Installation

Run the following commands to set up the FortyTwo console application:

### Step 1: Create a screen session (recommended)
```bash
screen -S FortyTwo
```

### Step 2: Create directory and navigate to it
```bash
mkdir -p ~/Fortytwo && cd ~/Fortytwo
```

### Step 3: Download and install the FortyTwo console app
```bash
curl -L -o fortytwo-console-app.zip https://github.com/Fortytwo-Network/fortytwo-console-app/archive/refs/heads/main.zip
unzip fortytwo-console-app.zip
cd fortytwo-console-app-main
chmod +x linux.sh && ./linux.sh
```

## ✅ Features

- Simple one-line installation process
- Screen session management for background execution
- Automated setup of all required dependencies
- Pre-configured for optimal performance

## 📋 Requirements

- Linux-based operating system
- curl, unzip, and screen utilities installed
- Internet connection for downloading the application

## 📝 Usage Notes

After installation, the FortyTwo console application will be ready to use. You can detach from the screen session using `Ctrl+A+D` and reattach later using:

```bash
screen -r FortyTwo
```

## 🔧 Troubleshooting

If you encounter any issues during installation:

1. Make sure you have sufficient permissions
2. Verify that all required utilities are installed:
   ```bash
   apt-get update && apt-get install -y curl unzip screen
   ```
3. Check your internet connection and firewall settings

## 📊 System Requirements

- Minimum 2GB RAM
- 2 CPU cores
- 20GB free disk space
- Ubuntu 20.04 LTS or newer recommended

## ⚠️ Disclaimer

This is an unofficial repository providing installation scripts and guidance for the FortyTwo Network console application. For official support, please refer to the [official FortyTwo Network repository](https://github.com/Fortytwo-Network/fortytwo-console-app).

## 🤝 Contributing

Contributions to improve the installation process or documentation are welcome. Please feel free to submit a Pull Request.

## 📜 License

This project is provided under the MIT License. The FortyTwo Network console application itself may be subject to different licensing terms.
