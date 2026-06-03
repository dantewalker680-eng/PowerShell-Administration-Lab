# PowerShell Administration Lab

## Objective

Demonstrate basic PowerShell administration skills commonly used in help desk and IT support environments.

## Tasks Performed

### Verified PowerShell Version

Command:

```powershell
$PSVersionTable
```

### Gathered System Information

Command:

```powershell
Get-ComputerInfo | Select-Object WindowsProductName, WindowsVersion
```

### Reviewed Network Configuration

Command:

```powershell
Get-NetIPAddress
```

### Listed Running Processes

Command:

```powershell
Get-Process
```

### Created a Directory

Command:

```powershell
New-Item -Path C:\Temp -ItemType Directory
```

### Created a File

Command:

```powershell
New-Item -Path C:\Temp\LabFile.txt -ItemType File
```

### Verified File Creation

Command:

```powershell
Get-ChildItem C:\Temp
```

## Skills Demonstrated

- PowerShell Administration
- Windows Administration
- Process Monitoring
- Network Troubleshooting
- File Management
- Command Line Operations

## Screenshots

Screenshots are available in the screenshots folder.
