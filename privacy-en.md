# Privacy Policy — Silver Chat Studio

**Effective Date:** May 28, 2026

## 1. General Provisions

**Silver Chat Studio** ("the Application") respects your privacy. This document describes what data we collect, how we use it, and how we protect it.

## 2. What Data We Collect

The Application collects and stores data **locally only** on your device:

- **Twitch OAuth tokens** (access token, refresh token) — for connecting to chat and retrieving stream information
- **Application settings** (WebSocket port, sound settings, reaction triggers, interface preferences)
- **Twitch username and channel ID** — for display in the interface and forming API requests

## 3. How We Use Data

Collected data is used **solely for application functionality**:

- Connecting to Twitch API to read chat and get stream information
- Sending messages to OBS via local WebSocket server
- Saving user settings between sessions
- Automatic refresh of access tokens when they expire

## 4. Data Storage and Protection

- **All data is stored locally** in the application folder on your computer
- We **do not transfer** your data to third parties, advertising networks, or analytics services
- We **do not send** data to external servers except official platform APIs (Twitch, YouTube, etc.)
- Files `tokens.json` and `settings.json` contain sensitive information — do not share them with others

## 5. Integration with External Platforms

The Application uses official APIs:

- **Twitch API** — for reading chat, getting stream information and user avatars
- **Google OAuth** (optional) — for YouTube authorization (if enabled)

By using the Application, you agree to the terms of service of the respective platforms:
- [Twitch Terms of Service](https://www.twitch.tv/p/legal/terms-of-service/)
- [Google Privacy Policy](https://policies.google.com/privacy)

## 6. Your Rights

You have the right to:

- **Delete all data** — delete files `tokens.json`, `settings.json`, `triggers.json` from the application folder
- **Revoke access** — in your platform account settings: [Twitch Connections](https://www.twitch.tv/settings/connections)
- **Uninstall the Application** — simply delete the program folder

## 7. Security

We take reasonable measures to protect your data:

- Tokens are stored locally, not in the cloud
- All connections to external APIs use HTTPS
- The Application does not contain ads, trackers, or hidden data collection modules

## 8. Changes to This Policy

We may update this policy. The current version is always available in the project repository:
🔗 [https://github.com/DeSjeT/SilverChatStudio](https://github.com/DeSjeT/SilverChatStudio)

## 9. Contact

For privacy-related questions, contact:
- **GitHub:** [https://github.com/DeSjeT](https://github.com/DeSjeT)
- **Email:** desjet89@hotmail.com
---

**By using Silver Chat Studio, you confirm that you have read and agree to this Privacy Policy.**
