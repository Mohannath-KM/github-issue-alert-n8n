# github-issue-alert-n8n
A lightweight, self-hosted automation that monitors a GitHub repository and sends professional HTML email notifications when a new issue is created. Built with n8n, this project integrates GitHub and email seamlessly using scheduled workflows and custom logic.

# 🚨 GitHub Issue Alert Automation (n8n)

This project is an automated workflow that sends email notifications whenever a new issue is created in a specified GitHub repository.

## 🔧 Technologies Used
- [n8n](https://n8n.io/) (Self-hosted)
- Docker + Ubuntu WSL2
- GitHub REST API
- JavaScript (for logic)
- HTML Email Template

## 🧠 How It Works
1. A Cron trigger runs every 10 minutes
2. An HTTP Request fetches issues from GitHub
3. A Code node checks for new issue IDs
4. If new, an HTML email is sent
5. Last issue ID is saved to avoid duplicates


## ✅ Benefits
- Instant email alerts
- No duplicate notifications
- Self-hosted, no vendor lock-in
