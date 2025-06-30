# 📦 ec2-audit (Debian Package)

A lightweight CLI utility to **audit EC2 instances** running in your AWS account, packaged as a `.deb` file for easy installation and distribution across Linux systems.

---

## 🧰 What It Does

- Lists all running EC2 instances in the configured AWS account
- Calculates uptime in days using launch time
- Flags instances running beyond a threshold (default: 7 days)
- Prompts to stop long-running instances interactively
- Installs like a real Linux tool via `dpkg -i`

---

## 📦 Package Details

| Property     | Value                      |
|--------------|----------------------------|
| Package Name | `ec2-audit`                |
| Version      | `1.0.0`                    |
| Type         | `.deb` (Debian-based)      |
| Script Path  | `/usr/local/bin/ec2-audit` |
| Language     | Bash                       |

---

## 🛠️ Prerequisites

- Linux system (Debian/Ubuntu-based)
- AWS CLI installed and configured:
  ```bash
  sudo apt install awscli jq -y
  aws configure

Final result  [output](./output.png)

## Installation
    wget https://github.com/sanjeev275/ec2-audit-deb-package/releases/download/v1.0.0/my-ec2-audit-package.deb
    sudo dpkg -i ec2-audit_1.0.0_all.deb

    
