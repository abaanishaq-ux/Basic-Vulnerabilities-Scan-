# Basic-Vulnerabilities-Scan-
🔍 Basic Vulnerability Scan – Task 3

For this task, I performed a basic vulnerability scan on my PC using Nessus Essentials.
The goal was to find out what common security issues exist on my system and learn how to fix them.

🛠 Tool Used

Nessus Essentials (Free Edition)

Target: My own computer (IP: 192.........)

Report generated on: 25th September 2025

📊 Scan Results

Total Issues Found: 34

Severity Levels:

🔴 Critical → 0

🟠 High → 0

🟡 Medium → 2

🟢 Low → 0

ℹ️ Info → 32

Most findings were informational (system details, open ports, service versions), but 2 were important to look at.

⚠️ Key Vulnerabilities
1. SSL Certificate Cannot Be Trusted (Medium)

👉 My system was using an untrusted/self-signed SSL certificate.
🔧 Fix: Use a valid SSL/TLS certificate or configure trusted certs for local services.

2. SMB Signing Not Required (Medium)

👉 My SMB (file-sharing service) did not enforce signing, which makes it easier for attackers to tamper with data.
🔧 Fix: Enable SMB signing in Windows security settings.

📌 Takeaways

My system doesn’t have critical risks, but some medium issues need fixing.

Even on personal PCs, services like SMB and SSL/TLS can expose weaknesses.

Regular scanning helps to stay aware of hidden security risks.

✅ Conclusion

This task gave me hands-on experience with a real vulnerability scanner.
I learned how to:

Run a scan on my own PC

Interpret results and severity

Research simple fixes for common issues
