Portscan Event Monitor

A Python-based tool for monitoring changes in the status of common network ports.  
Built and tested inside Termux/Kali Linux on Android.

📌 Features
- Monitors common ports (SSH, HTTP, HTTPS, MySQL, Web)
- Logs status changes (OPEN → CLOSED or CLOSED → OPEN) with timestamps
- Event-driven logging system for real-time updates
- Lightweight and portable — runs directly in Termux

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

🛠 Requirements
- Python 3
- Termux or any Linux environment

📖 Example Output
`
2026-01-15 10:59:00: Port 22 (SSH) changed to CLOSED
2026-01-15 10:59:00: Port 80 (HTTP) changed to CLOSED
2026-01-15 10:59:00: Port 443 (HTTPS) changed to CLOSED
`

✨ Author
Olanrewaju Emmanuel Okedele  
Learning by doing — exploring Linux, Python, and cybersecurity through hands-on projects.