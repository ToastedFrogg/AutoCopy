# ToastedFrogs AutoCopy 🐸
ToastedFrogs AutoCopy is a lightweight, automated tool designed to streamline the process of offloading footage and files from SD cards and USB drives. It runs in the background, automatically detects when a drive is inserted, and moves your files to a safe location.
## ✨ Features
- **Automatic Detection**: Instantly detects when a removable drive (SD Card, USB) is inserted.
- **Auto-Import**: Automatically copies files to your chosen destination folder.
- **Organized Storage**: Creates a new subfolder using the current date (`YYYY-MM-DD`) for each import session.
- **Move & Verify**: Files are copied, verified for integrity (size check), and then **deleted from the source** card to free up space.
- **Safe Eject**: Automatically safely ejects the drive once the import is complete.
- **System Tray Integration**: Minimized to the system tray to stay out of your way.
- **Startup Manager**: Option to launch automatically with Windows.
- **Dark Theme UI**: Easy on the eyes with a custom dark interface.
## 🚀 How to Use
1. **Launch the Application**: Run `ToastedFrogs AutoCopy`.
2. **First Setup**:
   - On the first run, go to the **Settings** tab.
   - Click **Browse** and select the folder where you want your files to be saved (e.g., `D:\MyFootage`).
   - Click **SAVE & START**.
3. **Importing Files**:
   - Insert an SD card or USB drive.
   - The dashboard will pop up and ask to confirm (or start automatically if configured).
   - Watch the progress bar as files are transferred.
4. **Completion**:
   - Once finished, you will hear a notification sound.
   - The program will notify you that it is "Safe to Remove" the drive.
## 🛠 Building from Source
If you have the source code and want to build the executable yourself:
1. Ensure you have Python installed.
2. Run the build script:
   ```cmd
   setup_and_build.bat
   ```
   This will install requirements and create a standalone `.exe` in the `dist` folder.
## ⚠️ Note
This program performs a **Move** operation (Copy + Delete). It is designed to clear your SD cards after backing them up. Ensure your destination drive has enough space!
