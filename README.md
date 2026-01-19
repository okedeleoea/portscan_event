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
<img width="720" height="1650" alt="1000229079" src="https://github.com/user-attachments/assets/916ad6b7-be44-475f-99d1-9b9c8465590a" />
<img width="720" height="1650" alt="1000229066" src="https://github.com/user-attachments/assets/faf2f0b4-c702-47b3-b4dd-56362626a90c" />
<img width="720" height="1650" alt="1000229034" src="https://github.com/user-attachments/assets/1f859d22-05a1-483a-9d67-d12914b02acd" />
<img width="720" height="1650" alt="1000229026" src="https://github.com/user-attachments/assets/2282afb1-e77a-4b1a-9653-68c7a7705968" />


✨ Author
Olanrewaju Emmanuel Okedele  
Learning by doing — exploring Linux, Python, and cybersecurity through hands-on projects.
