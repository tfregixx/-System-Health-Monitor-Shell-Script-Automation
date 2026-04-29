# -System-Health-Monitor-Shell-Script-Automation
System Health Monitor is a lightweight full-stack project that collects and displays system performance data using a Bash script integrated with a simple web interface. It helps users quickly check system health including CPU usage, memory, disk space, uptime, and running processes

🚀 Features:

📊 System Health Report – Generates real-time system status
💾 Disk Usage Monitoring – Displays storage usage
🧠 Memory Usage Tracking – Shows RAM usage
⏱️ Uptime Monitoring – Tracks system running time
⚙️ Process List – Displays active processes
🌐 Web Interface – View report via browser
🔁 Automation Ready – Can be scheduled for periodic execution

📦 Prerequisites

Ensure the following are installed:

1.Python 3.x
2.Flask
3.Bash / Git Bash (Windows)
4.Web Browser

🛠️ Technologies Used

>Frontend:
HTML5
CSS3
JavaScript

>Backend:
Python (Flask)
Bash Shell Script

>Tools:
VS Code
Git & GitHub
Git Bash / Linux Terminal

📁 Project Structure

system-health-monitor/
├── backend/
│   ├── app.py
│   └── ps-health-report.sh
├── frontend/
│   ├── index.html
│   └── script.js
├── logs/
│   └── ps-health-report.txt
├── README.md


⚙️ Installation

1️⃣ Clone the repository
git clone https://github.com/your-username/system-health-monitor.git
cd system-health-monitor

2️⃣ Start Backend Server
cd backend
pip install flask
python app.py

3️⃣ Run Frontend

Open in browser:

frontend/index.html

▶️ How It Works

1.User clicks Run Report on UI

2.Flask backend triggers the Bash script

3.Script collects system data using Linux commands

4.Data is saved in a log file

5.Frontend fetches and displays the report

Workflow Diagram
<img width="938" height="708" alt="image" src="https://github.com/user-attachments/assets/3bfddd0c-c104-4dfc-9ece-33691723bf53" />



📌 Example Use Cases

1.Monitoring system performance
2.Learning shell scripting & automation
3.Beginner DevOps practice
4.Academic mini-project

🚀 Future Enhancements

1.Real-time CPU graphs
2.User authentication
3.Cloud deployment
4.Docker support
5.Alert notifications

📄 License

This project is for educational purposes. Free to use with attribution.

🙌 Acknowledgments

1.Open-source community
2.Linux documentation
3.Academic guidance

🔗 Repository Clone
git clone https://github.com/your-username/system-health-monitor.git

