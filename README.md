# TSTP-ITSAR-Development-IITH👨‍💻
# Device Security Test Suite for Government IoT Project

## Project Overview🪶

This repository contains a collection of test cases designed for evaluating the security requirements of IoT devices, specifically focusing on:
1. Unique Password/Token Detection.
2. Manipulation of User and Data Attributes.
3. Pentesting Strategies for Network Port Vulnerabilities.

These test cases are developed as part of a Government of India (GOI) project, assigned to IIT Hyderabad, in collaboration with external hires. The primary goal is to ensure the safety and integrity of consumer IoT devices such as Smart Energy Meters.

### Technologies Used🔨
- **Python** (version 3.6+)
- **Machine Learning** (for pattern detection and classification)
- **Linux Networking** (for pentesting strategies)
  
## Project Structure🔨

```bash
📂 Project Root
├── 📂 tests
│   ├── test_password_strength.py     # Test cases for unique password detection
│   ├── test_data_attributes.py       # Test cases for data attribute manipulation
│   ├── test_pentesting_ports.py      # Test cases for port scanning and pentesting
├── 📂 src
│   ├── password_detection.py         # Core logic for password/token validation
│   ├── data_attribute_validation.py  # Core logic for manipulating data attributes
│   ├── port_scanner.py               # Pentesting script for port vulnerabilities
└── README.md                         # Project instructions and documentation
