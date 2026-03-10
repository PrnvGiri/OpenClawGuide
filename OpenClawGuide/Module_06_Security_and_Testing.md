# Module 6: Security Hardening & The Final "Magic" Test

Before handing off sensitive web browsing, secure the application instance by applying a Gateway Token.

### 6.1 Securing Gateway Authentication
Run this command to establish a secure, personalized local access token for OpenClaw. Replace `"YourNewSecureToken123!"` with your own secure password.

```bash
openclaw config set gateway.auth.token "YourNewSecureToken123!"
```

### 6.2 Applying Configuration Changes
Restart the local instance so configurations can properly initialize:

```bash
openclaw gateway restart
```

### 6.3 The Final Test 
With Telegram properly configured and your browser fully synchronized, executing remote tasks is straightforward.

1. Keep your monitored Chrome browser and the OpenClaw tab open.
2. Open Telegram on your smartphone.
3. Message your Bot the following command:

> "Use the attached browser tab, go to amazon.in, search for iPhone 17, and select the first product."

Watch as OpenClaw physically manipulates the browser on-screen via Telegram orchestration!
