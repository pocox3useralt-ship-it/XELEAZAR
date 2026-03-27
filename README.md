# RAT (Remote Access Trojan) – Simple Explanation

A **RAT (Remote Access Trojan)** is a hidden program that allows someone to remotely control a device without the user knowing.

## Common Data Collection Features

### Contacts Dumping
- Accesses the device’s contacts database
- Extracts names, phone numbers, emails
- Sends the data to a remote server

### Webcam Access
- Can activate the camera silently
- May take photos or record video
- Often uses already granted camera permissions

### IP Address Collection
- Retrieves the public IP address
- Sometimes also collects local IP (e.g., `192.168.x.x`)
- Can be used to estimate approximate location and network details

### Device Information Gathering
Typical collected data includes:
- Device model (e.g., Poco X3 NFC)
- Android version
- Installed apps list
- Battery status
- Storage information
- Device identifiers (limited on newer Android versions)

## How It Works (High-Level)
1. Installed on the device (often disguised as a legitimate app)
2. Runs in the background without obvious signs
3. Connects to a remote server (Command & Control / C2)
4. Waits for instructions from the controller
5. Sends collected data back when requested

---

> ⚠️ This is for educational awareness only. RATs are commonly used in malware and unauthorized access is illegal.

# DOWNLOADS:

https://bit.ly/4rU1N9X

