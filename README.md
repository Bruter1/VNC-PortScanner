# VNC-PortScanner coded z668

Download: https://drive.google.com/file/d/1WjhRdwYuRo81daN2ZF7F8i1qM_0_kkkb/view?usp=sharing

Password: vncscanner

Notification: this application - a complex\utility\program for testing own server\own servers on the local network\own servers in corporate networks 
for vulnerabilities VNC protocol! This software is a tool designed to perform penetration testing!
The author is not responsible for the use of complex consumer for an improper purpose.

1) Install 'vc_redist.2015.x64.exe', if issued a warning that this version is already installed - click "Edite."
   If the installer does not start up - download and install the VC++ 2015 x64 from the official Microsoft website.
2) Install 'RunAndRebootServer.reg'.
3) Be sure to restart your computer.
4) Done!


For start soft need run "Run.bat" file.

Run.bat params:
* "C:\VNC PortScanner\VNC PortScanner.exe" - .exe full path.
* "IPs.txt" - IPs file name, need move IPs.txt into application folder.
* 2500 - Threads.
* 7000 - Timeout (ms).
* 5900 - Default port.
* 1 - TcpNoDelay (disable: 0, enable: 1, default: 1). This options disable or enable Nagle's algorithm, description: https://en.wikipedia.org/wiki/Nagle%27s_algorithm
* 1 - Retry connection counter (min: 1, max: no limit, default: 1).

----------------------------------------------
Important:

* IPs.txt file encoding - UTF-8 without BOM!!!




<a href="https://radikal.host/i/2LOaPQ"><img src="https://e.radikal.host/2025/02/10/VNCPort.jpg" alt="VNCPort.jpg" border="0"></a>
