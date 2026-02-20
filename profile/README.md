# 🥔 Sofapotato Project

Welcome to the **Sofapotato Project**! This is a collection of high-quality, integrated resources for FiveM servers, designed to provide seamless functionality across various frameworks (QBCore, ESX, etc.) through our custom bridge system.

## 🌟 Overview

The Sofapotato suite includes a variety of scripts ranging from core utilities to interactive gameplay features. All resources are built with performance and customization in mind.

### 📦 Included Resources

| Resource | Description |
| :--- | :--- |
| **`sp_bridge`** | The core compatibility layer. Handles framework detection and provides a unified API for other scripts. **Required for all other modules.** |
| **`sofapotato_mail`** | A complete in-game mail system with a modern UI and database integration. |
| **`sofapotato_menu`** | An advanced menu system for player interactions. |
| **`sofapotato_npc`** | NPC management system for creating interactive peds. |
| **`sofapotato_guidemenu`** | A helpful guide menu for new players to learn server features. |
| **`sofapotato_Discord_API`** | Integration tools for Discord status updates and event logging. |
| **`sp_adminmenu`** | Administrative tools for server staff. |
| **`sofapotato_ui_template`** | A starter template for creating consistent UI designs across resources. |
| **`sofapotato_role`** | Role management system. |

## 🛠️ Requirements

Before installing, ensure your server has the following dependencies:

- **FiveM Server Artifacts** (Latest recommended)
- **[oxmysql](https://github.com/overextended/oxmysql)** (Required for database interactions)
- **sp_bridge** (Included in this repository - must be started first)

## 🚀 Installation

1.  **Download the Repository**:
    Clone or download this repository to your computer.

2.  **Copy Files**:
    Place the `sofapotato` folder (or the individual resource folders inside it) into your server's `resources` directory.

3.  **Database Setup**:
    - Locate any `.sql` files within the resource folders (e.g., `sofapotato_mail/install/sofapotato_mail.sql`).
    - Import these SQL files into your database using a tool like HeidiSQL or phpMyAdmin.

4.  **Server Configuration**:
    Add the following lines to your `server.cfg` file. Ensure `sp_bridge` is started **before** other Sofapotato resources.

    ```cfg
    # Sofapotato Dependencies
    ensure oxmysql
    
    # Sofapotato Core
    ensure sp_bridge
    
    # Sofapotato Modules
    ensure sofapotato_menu
    ensure sofapotato_mail
    ensure sofapotato_npc
    ensure sofapotato_guidemenu
    ensure sofapotato_Discord_API
    ensure sp_adminmenu
    # Add other modules as needed
    ```

## ⚙️ Configuration

Each resource comes with its own `config.lua` file located in its root directory or `shared/` folder. Open these files to customize settings such as:
- Framework selection (QBCore/ESX/Standalone)
- UI colors and text
- Permission levels
- Gameplay variables

## 🤝 Support

If you encounter issues or have suggestions, please check the existing issues or open a new one on our GitHub repository.

---

*Made with ❤️ by Sofapotato Team*
