# 🎂 Schedule Birthday Message Bot (Discord Webhook)

A lightweight Python automation that sends birthday wishes to a Discord channel using GitHub Actions and Webhooks.

## 🚀 How It Works
- **Automation:** Powered by GitHub Actions (Cron Job).
- **Timezone:** Configured to fire every day at **06:00 AM GMT+7**.
- **Security:** Discord Webhooks are handled via GitHub Repository Secrets to keep the URL private.

## 🛠️ Tech Stack
- **Language:** Python 3.9
- **Library:** `requests`
- **Automation:** GitHub Actions (YAML)

## 📁 Repository Main Structure
- `schedule_birthday.py`: The logic for date calculation (GMT+7) and sending the Discord Embed.
- `.github/workflows/cron.yml`: The schedule configuration.

## ⚙️ Setup Instructions
1. Clone this repository.
2. Create a Discord Webhook in your server settings.
3. Add the Webhook URL to your GitHub Repo:
   - `Settings` > `Secrets and variables` > `Actions` > `New repository secret`.
   - Name: `DISCORD_WEBHOOK`.
4. The bot will now run automatically based on the cron schedule in `cron.yml`.

## 🖼 Example Result
Below is a preview of the automated birthday greeting in action.

<img width="383" height="385" alt="image" src="https://github.com/user-attachments/assets/fa0214ff-960d-47af-a4f8-e4a6a698bf3d" />


    Note: The layout and message are fully customizable to fit your needs.


---
*Created by [Seinia/Sanakata]*
