# Mossura 🌿

Mossura is a powerful project management and collaboration mod for Minecraft 1.21.1, designed to bring agile workflows directly into your world. Whether you're building a massive base with friends or managing a complex modpack project, Mossura helps you stay organized.

[!WARNING]
This version was created for HackMT 2026 and merely serves as a vibe-coded proof of concept. It has not undergone rigorous testing for bugs or vulnerabilities. Use at your own risk, and consider writing your own mod (perhaps in other games too!) if you feel inspired.

## 🚀 Key Features

-   **Project Blocks**: Physical workstations that anchor your project data.
-   **Kanban Board**: A full-featured web-based Kanban board integrated directly into Minecraft (via MCEF) or accessible through your external browser.
-   **Sprint Management**: Plan iterations, set dates, and track progress with built-in sprint support.
-   **Ticket System**: Create tickets with titles, descriptions, priorities, labels, and subtasks.
-   **Team Collaboration**: Add members to your projects with granular permissions (Owner, Admin, Editor, Viewer).
-   **Real-time Notifications**: Get notified in game when you are assigned to a ticket or when someone comments on your tasks.
-   **Web Server Interface**: Access your projects from your phone or desktop browser with a secure token-based authentication system.

## 🌐 Web Interface

Mossura includes a lightweight web server that runs alongside your Minecraft server.

-   **Browser Access**: Navigate to `http://localhost:8080` (or your server's IP) to view your projects.
-   **Project Switcher**: Easily switch between all projects you own or are a member of.
-   **Auto-Sync**: The web view automatically refreshes to keep you up-to-date with ingame changes.

## 🔑 Authentication

To access your projects via an external browser, you must verify your identity:
1. Open the web view.
2. Observe the 6-character token provided in the login modal.
3. In Minecraft, run: `/mossura verify <TOKEN>`
4. Your browser session will be securely linked to your Minecraft account.

## 🛠️ Commands

-   `/mossura verify <token>`: Links your current web browser session to your Minecraft account.

## 📦 Requirements

-   **Minecraft**: 1.21.1
-   **Loader**: Fabric
-   **Dependencies**:
    -   Fabric API
    -   MCEF (Minecraft Chromium Embedded Framework) - *Used for ingame UI rendering*

## 📜 License

This project is licensed under the MIT License.
