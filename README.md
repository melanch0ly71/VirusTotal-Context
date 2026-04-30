🛡️ **VT-Context: Right-Click VirusTotal Scanner**  
VT-Context is a Windows productivity and security tool that integrates VirusTotal's threat intelligence directly into the File Explorer. It allows SOC analysts and power users to triage suspicious files with a single right-click.  

**🚀 Key Features**  
1. **Context Menu Integration:** Adds a "Scan on VirusTotal" option to the Windows right-click menu.
2. **Privacy-First Hashing:** Calculates the SHA-256 hash locally. It only communicates with the API to check the reputation, saving bandwidth and keeping your files private.
3. **Dynamic Analysis:** If a file hash isn't found in the database, the tool offers a direct upload for fresh analysis (up to 32MB).
4. **Persistent Configuration**: Securely saves your API key in C:\ProgramData\VTContext so you only have to set it up once.
5. **Clean Uninstallation:** Includes a dedicated uninstaller to wipe Registry keys and local configuration files.

**🛠️ Technical Stack**  

Language: Python 3.x  
API: VirusTotal v3 REST API  
Libraries: requests for networking, tkinter for the GUI, and winreg for Windows Registry manipulation.  **

📥 **Installation & Usage**
1. Go to the Releases section on the right side of this page.  
2. Download the VT-Context-Project.zip.  
3. Extract the folder and run VT_Installer.exe.  
4. Enter your VirusTotal API key when prompted.
<img width="258" height="143" alt="Screenshot 2026-04-30 123744" src="https://github.com/user-attachments/assets/ca42fc01-2245-4f47-b212-3543aaaf714f" />
5. After successful installation, move towards execution.
<img width="367" height="189" alt="Screenshot 2026-04-30 124936" src="https://github.com/user-attachments/assets/832b2f99-8df6-4adf-bf59-8b04b0056190" />  
6. Right click any file on your computer and click show more options, find Scan on VirusTotal and press it.
<img width="293" height="697" alt="Screenshot 2026-04-30 125002" src="https://github.com/user-attachments/assets/740af33d-5044-45b7-b781-341396ca27b6" />  
7. A window appears that scans the selected file on VT.  
<img width="688" height="280" alt="Screenshot 2026-04-30 130812" src="https://github.com/user-attachments/assets/d86005ed-0b2a-42fd-bf61-e1b1c5bee100" />  
8. Match the results on VirusTotal manually to verify the accuracy of this tool.  
<img width="1902" height="915" alt="Screenshot 2026-04-30 130914" src="https://github.com/user-attachments/assets/25d62221-1ccd-4c69-8a5b-6d5cb198d0d0" />  
