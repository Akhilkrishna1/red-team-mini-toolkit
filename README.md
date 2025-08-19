# Red Team Mini-Toolkit

A clean, modular Python CLI toolkit for basic red team reconnaissance activities.

## Features

- **Port Scanning** (`portscan.py`) - Network port enumeration
- **Subdomain Discovery** (`subdomains.py`) - Subdomain enumeration
- **HTTP Information** (`httpinfo.py`) - Web server reconnaissance 
- **DNS Enumeration** (`dnsenum.py`) - DNS record analysis
- **User Spray** (`spray.py`) - Authentication testing
- **CLI Interface** (`cli.py`) - Command-line interface

## Installation

```bash
git clone https://github.com/Akhilkrishna1/red-team-mini-toolkit.git
cd red-team-mini-toolkit
pip install -e .
```

## Usage

```bash
# Port scanning
python -m src.redmini.portscan target.com

# Subdomain enumeration 
python -m src.redmini.subdomains target.com

# HTTP information gathering
python -m src.redmini.httpinfo https://target.com

# DNS enumeration
python -m src.redmini.dnsenum target.com

# User spray testing
python -m src.redmini.spray target.com

# Main CLI interface
python -m src.redmini.cli --help
```

## Structure

```
red-team-mini-toolkit/
├── pyproject.toml
├── src/
│   └── redmini/
│       ├── cli.py
│       ├── portscan.py
│       ├── subdomains.py
│       ├── httpinfo.py
│       ├── dnsenum.py
│       └── spray.py
└── README.md
```

## Legal Disclaimer

⚠️ **IMPORTANT LEGAL NOTICE** ⚠️

This toolkit is intended for **AUTHORIZED TESTING AND EDUCATIONAL PURPOSES ONLY**.

- Only use this software against systems you own or have explicit written permission to test
- Unauthorized access to computer systems is illegal and may violate local, state, and federal laws
- Users are solely responsible for ensuring compliance with all applicable laws and regulations
- The authors and contributors assume no liability for misuse of this software
- Always obtain proper authorization before conducting any security testing
- Use responsibly and ethically in accordance with applicable laws and professional standards

By using this software, you acknowledge that you have read, understood, and agree to be bound by these terms.
