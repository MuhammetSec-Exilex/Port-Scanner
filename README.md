🛡️ PortScanner 1.0

PortScanner 1.0 is a lightweight, multithreaded CLI port scanning tool written in Python. It scans a specified range of ports on a target host and provides contextual security recommendations based on open ports found.

⸻

🚀 Features
	•	🔍 Multithreaded TCP Port Scanning
	•	🧠 Built-in Security Recommendations for Common Ports
	•	🎨 Animated ASCII Banner and Typewriter UI Effect
	•	📦 Easy to install via requirements.txt

⸻

📦 Installation
	1.	Clone the repo:

git clone https://github.com/yourusername/PortScanner.git
cd PortScanner

	2.	Create and activate a virtual environment:

python3 -m venv portscanenv
source portscanenv/bin/activate

	3.	Install dependencies:

pip install -r requirements.txt


⸻

🧪 Usage

python3 PortScanner_1.0.py -t <target> -sp <start_port> -ep <end_port>

Example:

python3 PortScanner_1.0.py -t scanme.nmap.org -sp 20 -ep 100


⸻

📌 Arguments

Argument	Description
-t, --target	Target IP address or domain (required)
-sp, --start_port	Start of the port range (required)
-ep, --end_port	End of the port range (required)


⸻

🔒 Example Output

[+] Port 22 is open
[+] Port 80 is open

Port 22: 🔐 SSH should have root login disabled and use key-based authentication.
Port 80: 🔁 Redirect HTTP to HTTPS and implement HSTS headers.


⸻

📄 License

MIT License. Feel free to fork and contribute.

⸻

🙋‍♂️ Author

Developed with ❤️ by Muhammet Alperen Şıvgın