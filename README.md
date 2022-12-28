<h1 align="center">Introduction</h1>

This port scan python script is designed to detect open ports on a remote server. By running this script, users can quickly gain insight into which ports are open on the server and which services are running. This allows users to make sure their systems are secure, and can identify potential vulnerabilities. Additionally, this port scan script can be used to identify open ports that can be used for malicious purposes, such as connecting to a server to gain access or launch attacks.

This Python script may and could be serious if used in unethical way or for malicious purposes, if discovered or used without authorization, could land you in jail. It serves only educational purposes.

• This script allows a user to input a remote host to scan. 
• A 60-character line of asterisks is printed to divide up the output.
• The script attempts to connect to every port from 1 to 1025.
• The script prints out any open ports that it finds.
• The script also prints the total time taken for the scan to complete.
• The script includes exception handling for various errors.

**Requirements:** socket,
subprocess,
sys,
datetime

**Installation:**
```
git clone https://github.com/SusanSantos7/SOP-ScanPort.git | cd SOP-ScanPort
```
