# Basic Windows Command

## Basic Windows Command

### 🔧 Network Commands

| Command | Description |
| --- | --- |
| `ipconfig` | Displays IP address, subnet mask, and default gateway. |
| `ipconfig /all` | Shows detailed network configuration (MAC, DNS, DHCP, etc.). |
| `ipconfig /all | findstr IPv4` | Filters to show only IPv4 addresses. |
| `getmac /v` | Displays MAC addresses of all network interfaces with additional info. |
| `net share` | Lists shared resources on the local system. |

### 👤 User & System Identity

| Command | Description |
| --- | --- |
| `net user` | Lists all local user accounts. |
| `hostname` | Shows the system’s network name. |
| `whoami` | Displays the current logged-in user. |

### ⚙️ System Utilities (Run via `Win + R` or Command Prompt)

| Command | Description |
| --- | --- |
| `ncpa.cpl` | Opens Network Connections window. |
| `firewall.cpl` | Opens Windows Firewall settings. |
| `appwiz.cpl` | Opens Programs and Features (uninstall programs). |
| `sysdm.cpl` | Opens System Properties. |
| `optionalfeatures` | Opens Windows Features dialog (enable/disable features). |
| `lusrmgr.msc` | Opens Local Users and Groups Manager (Not in Home edition). |

### 🪪 Licensing & Version

| Command | Description |
| --- | --- |
| `winver` | Shows Windows version and build number. |
| `slmgr /xpr` | Displays Windows activation status (expiration info). |