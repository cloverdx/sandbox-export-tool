# Sandbox Export Tool

## Overview
**Sandbox Export Tool** automates the process of preparing **CloverDX sandboxes** for upload to **Upgrade Analyzer**.  
It exports sandboxes with the option to remove sensitive data, ensuring compliance with security standards, and packaging the sandboxes automatically — saving time and reducing human error.

---

## Goals
- Simplify and speed up sandbox preparation  
- Ensure compliance with data protection policies  
- Reduce manual errors during data redaction  
- Provide clear reports of what was redacted or changed  
- Improve user experience through simple setup and guidance

---

## Key Features
- **Sandbox Selection:** Choose one or multiple sandboxes to process  
- **Sensitive Data Scan:** Automatically detects passwords, tokens, and credentials  
- **Redaction:** Removes or masks sensitive values in supported file types  
- **Packaging:** Creates a single ZIP file containing sandboxes  
- **Reporting:** Generates a summary report of exported files  
- **User Guidance:** Short tutorial video for setup and usage

---

## Technical Details
- **Target:** CloverDX Server 5.0+  
- **Output:** `SandboxExport_[timestamp].zip` + sanitization report (CSV/XLSX)  
- **Supported Files:** `.grf`, `.sgrf`, `.jbf`, `.rjob`, `.wjob`, `.properties`, `.cfg`, `.prm`, `.fmt`, `.ctl`, `.java`, `.sql`

---

## How-To Guide
- You can find a video explaining how to use it [**OLD VIDEO**](https://youtu.be/jbTs5eXZfAI)
