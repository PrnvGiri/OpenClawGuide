# Module 3: Telemetry & Mobile Control (Telegram Integration)

One of OpenClaw's strongest features is its integration with Telegram, permitting you to control your AI directly from your smartphone. During setup, when prompted to select a channel, pick **Telegram**.

### 3.1 Creating a Telegram Bot
You need to create a dedicated Telegram Bot.
1. Open your Telegram app on your phone or desktop.
2. Search for the `BotFather`.
3. Send the command: `/start`.
4. Send the command: `/newbot`.
5. Name your Bot (e.g., *IntellipaatBot*).
6. Give it a unique username ending in "bot" (e.g., *IntelliClawBot*).

BotFather will provide a unique **HTTP API Token**. 
- Copy this token and paste it directly into your OpenClaw terminal wizard prompt.

### 3.2 Finding Your Telegram User ID
For security, you must restrict the bot so that it only listens to your commands.
1. In Telegram, search for the `@userinfobot`.
2. Send the command `/start`.
3. The bot will respond with your **User ID**.
- Copy this ID and paste it into the OpenClaw terminal prompt when asked.
