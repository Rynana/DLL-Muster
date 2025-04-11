# DLL Muster

**DLL Muster** is a sleek, dnSpy-inspired Windows application for inspecting Unity-based .NET DLL files. It extracts class names, `void` methods, and fields, then exports the data to clean, formatted `.json` files.

Built for reverse engineers, modders, and curious developers.

---

## Features

- Drag & drop DLLs into the interface
- Multi-select `.dll` files via file picker
- Export each DLL to a standalone `.json` summary
- Custom output folder selection
- Dark theme UI with custom flat controls
- Built-in list viewer for loaded files
- Remove individual DLLs or clear the list entirely
- Custom icon, window chrome, and branding

---

## How to Use (Compiled EXE)

1. **Download or build the EXE**
   - You can compile it yourself using Visual Studio (see below)
   - Or grab the latest `.exe` release from the Releases tab

2. **Launch the app**
   - Double-click `DLLMuster.exe`
   - The app will open in a custom dark window titled "DLL Muster"

3. **Add DLLs**
   - Drag `.dll` files into the right panel
   - Or click **Select .dll files** and choose multiple files

4. **Manage the list**
   - Remove a selected file using **Remove Selected DLL**
   - Clear the full list with **Clear All**

5. **Extract to JSON**
   - Click **Extract to .json**
   - Choose an output folder
   - JSON files will be saved as `YourDllName.json` in the selected folder

6. **Open Output Folder**
   - Click **Open Output Folder** to quickly open the last export location

---

License
This project is licensed under the MIT License.
