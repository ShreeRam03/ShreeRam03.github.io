# Malicious-website-scanner-and-blocker
A Windows desktop tool (Python, Tkinter) that blocks websites through the hosts file and checks the VirusTotal URL report API before allowing any site to be unblocked. Block and unblock actions are protected by a one-time password emailed to a registered owner.

## Setup

Requires Windows, Python 3, and admin rights (the tool edits the hosts file).

```
pip install requests pillow
set SENDER_EMAIL=you@example.com
set SENDER_APP_PASSWORD=your-gmail-app-password
set VT_API_KEY=your-virustotal-api-key
python project.py
```

Credentials are read from environment variables and are never stored in the code.

Write-up: https://shreeram03.github.io/website-blocker.html
