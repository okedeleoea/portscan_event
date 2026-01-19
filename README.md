Python-Based Network Port Monitoring Tool

Overview

This project is a Python-based network port monitoring tool designed to continuously track the status of commonly used TCP ports and log real-time changes.

The tool simulates a Security Operations Center (SOC) monitoring use case by detecting when services unexpectedly open or close on a host system.


Why This Project Matters

In real-world environments, attackers often expose new services or open ports after gaining access. Continuous monitoring helps security teams quickly detect these changes.

This tool demonstrates:

- Defensive security thinking
- Python automation for cybersecurity
- Real-time change detection
- SOC-style monitoring logic


Features

- Monitors common TCP ports (e.g., 22, 80, 443, 3306)
- Logs port status changes (OPEN ↔ CLOSED)
- Runs in Linux and Termux environments
- Lightweight and easy to extend

Technologies Used

- Python 3
- Linux / Termux
- Socket programming
- Logging mechanisms

Example Use Case

- Detect unauthorized service exposure
- Monitor system hardening effectiveness
- Support incident response investigations
- Baseline vs deviation analysis

Skills Demonstrated

- Python scripting for security
- Network fundamentals
- Continuous monitoring
- Defensive cybersecurity practices
- Linux command-line usage


📂 Project Structure
`
projects/
├── bin/        # Executable scripts (Python, Bash)
├── logs/       # Output logs from scans
├── config/     # Configuration files and backups
├── notes/      # Documentation and markdown notes
└── tests/      # Experimental code or temporary files
`

🚀 Usage
1. Clone the repository:
   `bash
   git clone https://github.com/okedeleoea/portscan_event.git
   cd portscan_event
   `

2. Run the script:
   `bash
   python3 bin/portscan_event.py
   `

3. View logs:
   `bash
   tail -f logs/ports_event.log
   `

📖 Example Output
`
2026-01-15 10:59:00: Port 22 (SSH) changed to CLOSED
2026-01-15 10:59:00: Port 80 (HTTP) changed to CLOSED
2026-01-15 10:59:00: Port 443 (HTTPS) changed to CLOSED
`
<img width="720" height="1650" alt="1000229079" src="https://github.com/user-attachments/assets/916ad6b7-be44-475f-99d1-9b9c8465590a" />
<img width="720" height="1650" alt="1000229066" src="https://github.com/user-attachments/assets/faf2f0b4-c702-47b3-b4dd-56362626a90c" />
<img width="720" height="1650" alt="1000229034" src="https://github.com/user-attachments/assets/1f859d22-05a1-483a-9d67-d12914b02acd" />
<img width="720" height="1650" alt="1000229026" src="https://github.com/user-attachments/assets/2282afb1-e77a-4b1a-9653-68c7a7705968" />

Future Improvements

- Email or Telegram alerts
- JSON/CSV log export
- Configurable port lists
- Integration with SIEM tools

---
✨ Author
Olanrewaju Emmanuel Okedele  
Learning by doing — exploring Linux, Python, and cybersecurity through hands-on projects.

Disclaimer

This tool is intended for educational and defensive security purposes only.
