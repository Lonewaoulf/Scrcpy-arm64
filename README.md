# scrcpy-arm64

Prebuilt packages of [scrcpy](https://github.com/Genymobile/scrcpy) for **ARM64 (aarch64)** systems, developed by **LoneWolf**.  
Ideal for use on mobile Linux environments like **Termux**, or any ARM64 Linux distribution.

## 📦 Files Included

- `scrcpy-arm64.zip` – Compressed ZIP archive of scrcpy binaries and scripts.
- `scrcpy-arm64.tar.gz` – TAR.GZ archive for easy extraction on Unix systems.
- `run.sh` – Shell script to run scrcpy easily.
- `install-deps.sh` – Optional script to install necessary dependencies.

## 📁 Directory Structure

scrcpy-arm64/ ├── scrcpy ├── scrcpy-server ├── run.sh └── install-deps.sh

## 🧠 How to Use

1. Extract the archive of your choice:
   ```bash
   unzip scrcpy-arm64.zip
   # or
   tar -xzvf scrcpy-arm64.tar.gz

2. Navigate into the directory:

cd scrcpy-arm64


3. Run the script:

./run.sh



⚙️ Dependencies

You may need to install:

ffmpeg

adb

libusb

x11 or wayland (for GUI display)


Use the included install-deps.sh script if needed.

👤 Author

Developed with ❤️ by LoneWolf


---
