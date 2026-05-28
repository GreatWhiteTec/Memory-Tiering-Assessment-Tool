# Memory Tiering Assessment Tool (MTAT)

**MTAT** is a workload planning and sizing utility designed to help system administrators, engineers, and architects evaluate and plan memory tiering deployments. This tool analyzes system requirements and helps optimize memory allocation across different performance tiers.

## 🗂️ Repository Contents

This repository provides multiple ways to run the tool, depending on your operating system and environment:

## Version 1.0
* **`MemTierSizer.ps1`**: The standard PowerShell script for Windows environments. Version 1 Release
* **`MAC_Friendly_MemTierSizer.ps1`**: A macOS-optimized version of the PowerShell script (requires PowerShell Core). Version 1 ONLY
* **`MemoryTieringSizer.exe`**: A standalone, compiled Windows executable. No PowerShell scripting experience required to run. Version 1 Release
* **`Sizer_Tool.mp4`**: A video demonstration showing how to use the tool and interpret its output. Version 1 Release

## Version 2.0
* **`MTAT20.ps1`**: The standard PowerShell script for Windows environments. Version 2 Release
* **`MTAT20.exe`**: A standalone, compiled Windows executable. No PowerShell scripting experience required to run. Version 2 Release

## 🚀 Installation & Setup

### For Windows (Using the Executable)
1. Download `MTAT20.exe` from the repository.
2. Double-click the executable to launch the sizing tool.

### For Windows (Using PowerShell)
1. Clone the repository or download `MTAT2.0.ps1`.
2. Open PowerShell as an Administrator.
3. Ensure your execution policy allows scripts to run:
   ```powershell
   Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

Execute the script 
    .\MTAT20.ps1

   ### For Mac OS (Using PowerShell) 
   
   ## Version 1.0 ONLY
1. Ensure you have PowerShell for macOS installed.
2. Clone the repository or download MAC_Friendly_MemTierSizer.ps1.
3. Open your terminal and launch PowerShell by typing pwsh.
4. Navigate to the directory containing the script and run:
    .\MAC_Friendly_MemTierSizer.ps1

   
Version 2.0
Added per host visibility for active memory

## 📝 License

This project is licensed under a Custom Non-Commercial License. You are free to use the tool for personal or internal use, but you may not sell, sub-license, or commercialize this software. See the [LICENSE](LICENSE) file for full details.
