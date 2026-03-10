# Module 5: Enabling Physical Browser Automation

OpenClaw supports advanced functionality, such as taking literal control over your Chrome web browser via its built-in Browser Relay extension.

### 5.1 Installing the OpenClaw Extension
Return to your main terminal and run the following command to securely fetch the browser relay plugin:

```bash
openclaw browser extension install
```

### 5.2 Retrieving the Extension Path
After the download finishes, you must pinpoint the folder where it downloaded by executing:

```bash
openclaw browser extension path
```

This output will return the exact physical local folder address. Copy this path to your clipboard.

### 5.3 Developing Chrome Extension Relay
To load this extension effectively into your browser:
1. Open your Google Chrome browser.
2. Navigate to your Extensions portal (`chrome://extensions`).
3. Turn on the **Developer Mode** toggle in the top right.
4. Click **Load Unpacked**.
5. Paste the folder path you copied in section 5.2 and load it in.
