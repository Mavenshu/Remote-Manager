🚀 Remote Manager - Quick Start Guide (Updated)
📦 Installation and Setup
⚡ Essential Quick Actions
🔗 Quick Actions Menu

Click on "Remote Manager" in the status bar to access:

Terminal – Open a new terminal

Sessions – Manage active sessions

Tools – Diagnostic tools and utilities

Settings – Configuration and preferences

Macros – Automation system (New!)

Help – Documentation and support

🎯 Recommended Workflow
Step 1: Create Your Credentials

Sidebar → "Credentials" section → "+" button

Enter username and password

Confirm with "Create Credential"

Step 2: Add a Connection

Sidebar → "Connections" section → "+" button

Fill in the information:

Host: IP or server name (e.g., 192.168.1.100)

Type: RDP, SSH, Telnet, VNC

Category: Server, Desktop, Router, etc.

Credential: Select from the list

Name: Descriptive name

Step 3: Connect

Double-click the connection in the sidebar

Or right-click → "Connect"

Or use Quick Actions → Sessions

📜 Macro System (New!)
Recording Macros
Ctrl+Shift+F9  → Start recording
Ctrl+Shift+F10 → Stop recording  
Ctrl+Shift+F11 → Play saved macro

Practical Usage

Plan your action sequence

Start recording (Ctrl+Shift+F9)

Name your macro (e.g., "Production server login")

Execute your actions normally

Stop recording (Ctrl+Shift+F10)

Test immediately with (Ctrl+Shift+F11)

Managing Macros

Quick Actions → Macros → Macro Library: Full interface

Edit Macros: Rename, delete, view details

Statistics: Usage count, last run

🔧 Recommended Configuration
Basic Settings

Quick Actions → Settings

Adjust according to your needs:

Connection timeout

Default directories

Log level

Macro behavior

Connection Organization

Use groups: Prod, Dev, Test

Consistent categories: Server, Desktop, Network

Descriptive names: "DB-PROD-01" instead of "Server1"

📥 Import/Export
Full Backup

Quick Actions → Tools → Export Configuration

Choose the format:

Complete: Connections + credentials (without passwords)

Connections only: Legacy format

Save the JSON file

Restore

Quick Actions → Tools → Import Configuration

Select your backup file

Follow the import wizard

Re-enter passwords if necessary

🚨 Quick Troubleshooting
Connection Fails

Check the IP address/hostname

Ping from a terminal

Verify credentials

Check logs: Quick Actions → Tools → Debug

Credentials Not Found

Recreate the credential if needed

Check username spelling

Use Debug Storage to diagnose

Extension Not Responding

Restart VS Code

Disable/Enable the extension

Open developer console (F12)

💡 Productivity Tips
Useful Macros to Create

Connection + opening specific tools

Network diagnostic sequences

New server setup

Automatic settings backup

Efficient Organization

One group per environment (Prod, Dev, Test)

Subgroups by function (Web, DB, Monitoring)

Consistent naming convention

Shared credentials for groups

Essential Shortcuts
Ctrl+Shift+P     → Remote Manager command palette
Ctrl+Shift+F9    → Record macro
Ctrl+Shift+F10   → Stop recording  
Ctrl+Shift+F11   → Play macro
F1               → Contextual help


You are now ready to use Remote Manager effectively! 🎉
