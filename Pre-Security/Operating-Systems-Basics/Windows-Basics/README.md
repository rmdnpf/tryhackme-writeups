# TryHackMe — Windows Basics

**Path:** Pre-Security  
**Module:** Operating Systems Basics  
**Category:** Operating Systems  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/windowsbasics  
**Date Completed:** 21 September 2026

---

## 🎯 Skills Demonstrated

- Windows desktop navigation
- Windows user authentication and account types
- System information gathering
- Windows File Explorer and file paths
- Application installation and removal
- Windows Settings and Control Panel
- Task Manager
- Windows Security
- Microsoft Defender custom scanning
- Windows Defender Firewall
- Inbound and outbound firewall rules

---

## 📖 Overview

This room provides hands-on experience with the Windows operating system through a Windows Server 2019 environment.

The room covers everyday Windows administration tasks as well as basic security controls, including system information, application management, Task Manager, Windows Security, and Windows Defender Firewall.

---

## 🧩 Tasks

### Task 1 — Introduction

Introduces the room scenario, learning objectives, and the Windows Server 2019 lab environment.

**No answer required.**

---

### Task 2 — Exploring the Windows Workspace

This task focuses on the Windows graphical interface and basic system navigation.

#### Key Concepts

- **Desktop:** Main workspace for files, folders, and shortcuts.
- **Taskbar:** Provides access to applications, system tools, settings, and notifications.
- **Start Menu:** Central location for applications, settings, and power options.
- **File Explorer:** Used to browse and manage files and folders.
- **About your PC:** Provides device and Windows system information.
- **User accounts:** Windows permissions vary between Guest, Standard, and Administrator accounts.

#### Practical Findings

| Item | Observation |
|---|---|
| Device name | `TryHatMe` |
| Installed RAM | 4.00 GB |
| Windows version | Windows Server 2019 Datacenter, Version 1809 |

The task also involved navigating the `TryHatMe Onboarding` folder and reading `Welcome.txt`.

> Flags are intentionally omitted from this public writeup.

### Portfolio Evidence

![System Information](./task-2-system-information.jpg)

![File Explorer](./task-2-file-explorer.jpg)

---

### Task 3 — Configuring and Securing Windows

This task covers application management, Windows configuration, system monitoring, and built-in security controls.

#### Application Management

Windows applications can be:

- Updated through Windows Update or application-specific mechanisms.
- Installed through the Microsoft Store.
- Installed from trusted vendor websites using installers such as `.exe` or `.msi`.
- Removed through Settings, Control Panel, or application uninstallers.

#### Windows Settings and Control Panel

Windows Settings provides a modern centralized interface for system configuration, while Control Panel provides access to many legacy configuration options.

#### Task Manager

Task Manager can be used to monitor:

- Running applications and background processes
- CPU and memory usage
- Logged-in users
- Process details and PIDs
- Windows services

This is useful for basic system monitoring and identifying unusual resource usage or processes.

![Task Manager](./task-3-task-manager.jpg)

#### Windows Security

Windows Security provides several built-in security controls, including:

- Virus & threat protection
- Firewall & network protection
- App & browser control
- Device security

The task included performing a **custom scan** against the provided lab folder and reviewing the detected test file.

![Windows Security](./task-3-windows-security.jpg)

#### Windows Defender Firewall

Windows Defender Firewall controls network traffic based on configured rules.

The advanced firewall interface provides separate rule sets for:

- **Inbound Rules** — control incoming network connections.
- **Outbound Rules** — control outgoing network connections.
- Connection Security Rules
- Monitoring

Understanding these rule categories is important for basic Windows network security and troubleshooting.

![Windows Defender Firewall](./task-3-firewall.jpg)

> The screenshots show the TryHackMe lab environment and are included as portfolio evidence of the practical exercises.

---

### Task 4 — Conclusion

Reviews the Windows concepts covered throughout the room, including the desktop, File Explorer, Windows Update, Microsoft Store, Settings, Control Panel, Task Manager, Windows Security, and Windows Defender Firewall.

**No answer required.**

---

## 🔑 Key Takeaways

- Windows provides multiple interfaces for system administration, including Settings, Control Panel, and built-in management tools.
- File Explorer and Windows paths are fundamental for navigating and managing files.
- Task Manager provides useful visibility into processes, users, services, and system resource usage.
- Windows Security combines several endpoint protection features in one interface.
- Windows Defender Firewall uses inbound and outbound rules to control network traffic.
- Understanding these built-in tools provides a foundation for Windows administration and defensive security work.

---

## 🛡️ Cybersecurity Relevance

Windows is widely used in enterprise environments, making familiarity with its built-in administrative and security tools valuable for defensive security roles.

For a SOC or Blue Team workflow, tools such as **Task Manager**, **Windows Security**, and **Windows Defender Firewall** provide useful starting points for investigating processes, endpoint protection status, and network access rules.

---

## ⚠️ Note

- Flags are intentionally omitted from this public writeup.
- Device and environment-specific identifiers are not included where unnecessary.
- This writeup focuses on concepts, observations, methodology, and practical skills rather than publishing raw answers.
- All activity was performed in the official TryHackMe lab environment.
