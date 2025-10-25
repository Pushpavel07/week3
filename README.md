Vulnerability Scanner
=====================

Overview
----------
This Python script scans specified IP addresses for common open ports and identifies potential vulnerabilities. It maps each open port to its likely service and provides a brief risk note with suggested mitigation strategies. The results are saved in a CSV file named `vulnerability_report.csv`.

Features
----------
- Scans for common ports: 21 (FTP), 22 (SSH), 80 (HTTP), 443 (HTTPS), 3306 (MySQL)
- Maps ports to known services
- Provides risk notes and mitigation suggestions
- Handles timeouts and exceptions gracefully
- Outputs results in CSV format

 Requirements
--------------
- Python 3.x
- No external libraries required (uses built-in `socket` and `csv` modules)

 How to Run
------------
1. Save the script as `vulnerability_scanner.py`
2. Open a terminal or command prompt
3. Run the script using:

4. The script will scan the IPs listed in `target_ips` and generate a report.

 Output
--------
The output file `vulnerability_report.csv` will contain:

- IP Address
- Port
- Service
- Risk Note

 Notes
-------
- Ensure you have permission to scan the target IPs.
- Unauthorized scanning may violate network policies or laws.
