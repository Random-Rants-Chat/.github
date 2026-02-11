## ⚠️ Important:
Please read our [Terms of Use & Privacy Policy](https://randomrants-plus.onrender.com/legal) before using or contributing to [Random Rants +](https://randomrants-plus.onrender.com/).

# 🚀 How Can I Help?
We love community contributions! Whether you're fixing a bug in the WebSocket logic or styling a new notification type, here is how you can get started:

1. Reporting Bugs
   
   Check the Issues tab to see if the bug has already been reported.
   
   If not, open a new issue. Please include:
   - Your browser (e.g., Chrome on Chromebook).
   - Steps to reproduce the bug.
   - Screenshots of the console if there are errors.

3. Suggesting Features
   We want the "chaos" to be fun!
   If you have an idea for a new room type or a notification sound, open an issue labeled enhancement.

3. Pull Requests (PRs)
   1. Fork the repository.
   2. Create a Branch for your feature (git checkout -b feature/cool-new-notif).
   3. Commit your changes with clear messages.
   4. Push to your fork and open a Pull Request.

# 🛠️ Technical Guidelines

## UI & Styling
  - We aim for a clean, accessible look.
  - Use the existing `elements.js` (located in src/gp2/) helper for creating DOM elements to maintain consistency with the GP2 engine.
  - LocalStorage: Do not clear LocalStorage in your scripts, as this is where users store their clientSettings.js (themes, volume, etc.).

# ⚖️ Code of Conduct
- Be kind to fellow ranters.
- No code that facilitates harassment, spamming, or deanonymizing users.
- Keep the chaos "controlled"—features should enhance the fun, not break the app for everyone else.
