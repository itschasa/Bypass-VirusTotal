# Bypass VirusTotal / AntiVirus / Anti-VM
Bypasses most anti-viruses and [virus total](https://virustotal.com).
Works by detecting if the program is being run in a virtual machine.

### How it works
* Most anti-viruses use containers or vms to scan and detect malicious activity.
* The code tries to detect this and if it does, then it just closes the program.
* Therefore, the anti-virus doesn't have anything to detect and shows it as clear.
