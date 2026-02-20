# 🥔 Sofapotato Team

Welcome to the official GitHub page of **Sofapotato**. We are a passionate development team dedicated to building high-quality tools, immersive gameplay scripts, and automation solutions for gaming communities.

## 🚀 What We Do

Our team focuses on two main pillars of development: **FiveM Resources** and **Discord Bot Solutions**.

### 📊 Activity & Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sofapotatoes&show_icons=true&theme=radical&count_private=true" alt="Sofapotato's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sofapotatoes&layout=compact&theme=radical" alt="Top Languages" />
</p>

### 🎮 FiveM Resource Ecosystem
We specialize in creating robust, optimized, and cross-framework resources for FiveM servers. Our ecosystem is built upon the **Sofapotato Bridge (`sp_bridge`)**, ensuring seamless compatibility across QBCore, ESX, and standalone environments.

**Key Resources:**
*   **`sp_bridge`**: The core foundation of our ecosystem. A unified compatibility layer that powers all our scripts.
*   **`sofapotato_mail`**: A feature-rich in-game mailing system with a modern, responsive UI.
*   **`sofapotato_menu`**: Advanced interactive menu solutions for player management.
*   **`sofapotato_npc`**: Dynamic NPC management for creating lively server environments.
*   **`sp_adminmenu`**: Comprehensive administrative tools for server staff.

### 🤖 Discord Bot Development
Beyond game scripts, we develop custom Discord bots to bridge the gap between your game server and community platform.

*   **FiveM Integration**: Seamless syncing between in-game actions and Discord logs (powered by our `sofapotato_Discord_API`).
*   **Community Management**: Tools for server status monitoring, whitelist management, and automated moderation.
*   **Custom Solutions**: Tailored bots designed to meet specific community needs.

---

## 📂 Repository Contents

This repository hosts our collection of open-source FiveM modules.

| Module | Description |
| :--- | :--- |
| **`sp_bridge`** | **[CORE]** The required dependency for all Sofapotato scripts. Handles framework logic. |
| **`sofapotato_mail`** | Advanced mail system with database storage. |
| **`sofapotato_Discord_API`** | API bridge for sending server events to Discord webhooks/bots. |
| **`sofapotato_guidemenu`** | Interactive server guide for new players. |
| **`sofapotato_ui_template`** | Development template for consistent UI design. |

## 🛠️ Usage Guide

If you are using resources from this collection:

1.  **Prerequisites**: Ensure you have `oxmysql` installed for database connectivity.
2.  **Installation**:
    - Place the desired folders into your `resources` directory.
    - **Important**: Always start `sp_bridge` **before** any other Sofapotato resource in your `server.cfg`.
3.  **Configuration**: Each module contains its own `config.lua` for customization.

## 🤝 Connect With Us

*   **GitHub**: [Sofapotato](https://github.com/sofapotato)
*   **Support**: Open an issue in this repository for bug reports or feature requests.

---
*Crafted with ❤️ by the Sofapotato Team*
