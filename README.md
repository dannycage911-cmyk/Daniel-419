Lab 48: Browser Exploitation Framework (BeEF)

1. Objective

The aim of this lab was to understand the Browser Exploitation Framework (BeEF) and learn about browser security.

2. Tools Used

- Kali Linux
- BeEF
- Firefox

3. Procedure

Step 1: Open Kali Linux terminal.

Step 2: Start BeEF using this command:

beef-xss-start

📸 INSERT SCREENSHOT 1 HERE – BeEF Startup

"Screenshot 1 - BeEF Startup" (images/beef-started.png)

Step 3: Wait for BeEF to start and display the Web UI address.

📸 INSERT SCREENSHOT 2 HERE – Web UI Address

"Screenshot 2 - Web UI" (images/beef-webui.png)

Step 4: Open Firefox and visit:

http://127.0.0.1:3000/ui/panel

📸 INSERT SCREENSHOT 3 HERE – BeEF Dashboard

"Screenshot 3 - BeEF Dashboard" (images/beef-dashboard.png)

4. Observation

BeEF started successfully and displayed its local Web UI address. A warning also appeared indicating that the GeoIP database was missing.

5. Conclusion

This lab helped me understand BeEF and how it is used to study browser security. I also learned how to start the service and access its web interface.

All testing was carried out in a controlled lab environment.
