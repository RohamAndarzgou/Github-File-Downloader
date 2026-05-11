# ⬇️ Universal File Downloader & 🌐 Web Browser Integration

This repository provides a powerful, automated tool for downloading files from any source within GitHub and includes an integrated web browser feature.

## ✨ Key Features
*   ✅ **Universal Downloading:** Download any file from anywhere on GitHub.
*   ✅ **Large File Support:** Supports multi-gigabyte downloads.
*   🔐 **Encryption:** Optional password protection for downloaded archives.
*   ✅ **Reliable Downloads:** Utilizes the `aria2` package for robust downloading.
*   ✅ **Automatic Archiving:** Automatically compresses and archives all downloaded files into ZIP format, supporting chunking (e.g., 90MB parts).
*   ✅ **Automation:** Performs all operations automatically without complex manual configuration.
*   ✅ **Batch Downloading:** Supports simultaneous download of multiple URLs.
*   ✅ **Organization:** Files are grouped into dedicated folders named after the original file/group.
*   ✅ **Persistence:** Downloads are permanently saved within your own GitHub repository structure.
*   ✅ **High Capacity:** Tested successfully for large files (up to 28GB).

**⚠️ Important Notes:**
*   Please read the "Updates" section at the bottom of this README for the latest information.
*   Some local Iranian servers may block external IPs; therefore, downloading content from services like Soft98 might not be possible using this tool.
*   🌐 **Web Browser Added:** Check the Updates section for instructions on how to use the new web browser feature.
*   📹 A video tutorial on using this tool has been added to the end of this document.

## 🔧 Installation Guide
1.  On your fork of this repository, click the 'Fork' button at the top.
2.  If necessary, rename your fork and then click 'Create Fork'. Your repository is now ready for use via the Actions tab.

## 🎯 How to Download Files from GitHub
1.  Navigate to the **Actions** tab in your own (forked) repository.
2.  On the left sidebar, select the `download-from-url` workflow.
3.  Click 'Run workflow' on the right side panel.
4.  In the first input box, paste the URL or multiple URLs separated by spaces.
5.  If you require password protection for the archive, enter your desired password in the `password` field.
6.  Click 'Run workflow' to start the download process.

## 📂 Where are the Downloaded Files?
*   All downloaded files will be placed within a dedicated folder named after the original file/group inside the `/downloads` directory.
*   If your file is very large, it will be split into multiple ZIP parts (e.g., part.zip, part.z01). You must download and combine all parts using tools like 7-Zip or WinRAR to extract the complete file.

## 🔔 Stay Updated
We continuously update this tool to improve functionality and fix bugs. Before use, ensure your fork is synchronized with the main repository by clicking 'Sync fork' on your forked repo page, followed by running 'Update branch'. If no updates are available, the sync button will be disabled.

## 🌐 International Internet Download Support
If you cannot use this tool but require a specific file, please send us the file name or download link to our support team so we can assist you in accessing it via local Iranian internet connections. Please send your request via Iranian messaging apps to @ask_here or call 09354887344.
