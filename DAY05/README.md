

# Cybersecurity Notes – DAY 05

## 1. Ports and Port Numbers

* Think of **ports** like doors to your system — each service/application has its own.
* Port number = unique ID for that door.
* **Range**: 0 to 65535

  * **0–1023** → Well-known ports (common services like HTTP, FTP)
  * **1024–49151** → Registered ports (assigned to specific apps)
  * **49152–65535** → Dynamic/Private ports (temporary stuff)

---

## 2. Common Service Ports (Example: FTP – Port 21)

* **FTP (File Transfer Protocol)**

  * Port: **21** (Control)
  * Purpose: Upload/Download files between client ↔ server.
  * Not secure (data sent in plain text).
  * Alternative: **SFTP** (Port 22 – uses SSH).
* Other examples to remember:

  * HTTP → Port 80
  * HTTPS → Port 443
  * SSH → Port 22

---

## 3. Linux User Types

* **Root User** → The main user (full system access).
* **Regular User** →Daily account.
* **Service Accounts** → Used by apps/processes, not humans.

---

## 4. Privilege Escalation in Linux

* Gaining higher-level permissions than you’re supposed to.
* Types:

  * **Vertical escalation** → From normal user to root.
  * **Horizontal escalation** → Accessing other user’s stuff without extra privileges.
* Common methods:

  * Exploiting misconfigured `sudo`.
  * Weak file permissions.
  * Kernel vulnerabilities.

---

## 5. Linux Commands (Example: `watch`)

* **`watch`** → Runs a command repeatedly and shows updated output.

  * Syntax:

    ```bash
    watch [options] command
    ```
  * Example:

    ```bash
    watch -n 5 date
    ```

    (Shows current date/time every 5 seconds.)

---

## 6. Security Operations Center (SOC)

* Basically the **war room** for cybersecurity.
* Monitors, detects, and responds to threats in real-time.
* Roles inside SOC:

  * **Tier 1 Analyst** → First response.
  * **Tier 2 Analyst** → Deep investigation.
  * **Incident Responder** → Containment + recovery.

---

## 7. Cybersecurity Learning Platforms (Example: TryHackMe)

* Interactive cybersecurity labs and challenges.
* Learn via guided tasks + hands-on hacking simulations.
* Good for practicing: Recon, exploitation, privilege escalation, etc.
* Alternatives: HackTheBox, OverTheWire.

