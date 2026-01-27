# PS2 BlueLink 🔵🔗

**PS2 BlueLink** is a desktop utility written in Python designed to streamline the transfer of game files (ISOs and archives) to USB storage for PlayStation 2, specifically optimized for **OPL (Open PS2 Loader)**.

The tool automates extraction, handles correct naming conventions using Game IDs, and organizes files into the appropriate directory structure.

## ✨ Features
* **Automatic Game ID Detection:** Scans ISO files to extract the serial code (e.g., `SLES_543.21`) and renames the file for OPL compatibility.
* **Multi-Format Support:** Directly handles `.iso`, `.zip`, `.7z`, and `.rar` files.
* **Smart Skip:** Automatically skips files already present on the USB drive if the file size matches, saving time on slow transfers.
* **Modern GUI:** A clean, dark-mode interface powered by `CustomTkinter`.
* **Real-Time Stats:** Monitor transfer speed (MB/s) and estimated time remaining (ETA).
* **USB Management:** Automatically detects removable drives and sets up the required `DVD` folder.

## 🚀 Getting Started

### Prerequisites
* Python 3.9 or higher.
* `unrar` (required for `.rar` support via the `rarfile` library).

### Installation
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/ps2-bluelink.git](https://github.com/your-username/ps2-bluelink.git)
   cd ps2-bluelink
