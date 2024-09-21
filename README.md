Name: Nandini Rai
Company: CodeTech IT Solutions
ID: CT08DS7717
Domain: CyberSecurity and Ethical Hacking
Duration: September to October
Mentor: Neela Santosh Kumar

Vulnerability Scanner:

Overview:

The Vulnerability Scanner is a Java-based tool designed to identify security vulnerabilities in web servers. It performs three primary functions:

Port Scanning: Scans the target server for open ports within a defined range, helping to identify potential entry points for attacks.

Software Version Check: Retrieves the software version information from the server's HTTP headers, allowing users to determine the technologies in use and their potential vulnerabilities.

Misconfiguration Check: Analyzes HTTP response headers for common security misconfigurations. It checks for the presence of essential security headers and provides guidance on how to improve server configurations.

Features:

Concurrent port scanning using multithreading for efficient performance.
Detection of open ports within a configurable range (default: 1-1024).

Assessment of HTTP response headers for common security headers:

X-Frame-Options

Strict-Transport-Security (HSTS)

X-Content-Type-Options

X-XSS-Protection

Content-Security-Policy

X-Permitted-Cross-Domain-Policies
