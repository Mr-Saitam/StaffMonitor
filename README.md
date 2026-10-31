![StaffMonitor](assets/banner.png)

<p align="center">
  <strong>Staff activity monitoring for Minecraft servers.</strong>
  <br>
  Tracks sessions, AFK time, commands, and chat messages, featuring an integrated web dashboard with access protected by console approval.
</p>

<p align="center">
  <a href="https://mrsaitam.com/docs/#/staffmonitor/introduction">Documentation</a>
  ·
  <a href="https://github.com/Mr-Saitam/StaffMonitor/issues">Report an Issue</a>
  ·
  <a href="https://github.com/Mr-Saitam/StaffMonitor/releases">Downloads</a>
</p>

---

## What is StaffMonitor?

StaffMonitor is a plugin for **Paper** Minecraft servers that allows you to track and review the activity of your server's staff team.

It collects information about each staff member's sessions, online and AFK time, executed commands, and chat messages. All this information is presented through an integrated web dashboard, without requiring any additional services.

It is designed to work on both standalone servers and multi-server networks using a shared MySQL database.

## Features

- **Activity tracking:** sessions, connections, disconnections, commands, and chat messages.
- **AFK tracking:** records each staff member's inactivity time.
- **Web dashboard:** statistics, charts, rankings, history, and real-time activity.
- **Protected access:** each new browser requires approval through the server console.
- **Individual statistics:** review each staff member's performance and activity.
- **Weekly goals:** set online time targets based on LuckPerms groups.
- **Inactivity alerts:** receive notifications when a staff member has been inactive for too long.
- **Multi-server support:** share data across multiple servers using MySQL.
- **Language support:** English and Spanish, with editable language files.
- **Data management:** automatic data retention and player history deletion.

## Dashboard

The dashboard is built directly into the plugin. It allows you to monitor your staff team's activity without relying on external applications.

Its sections include:

- General activity overview.
- Currently online staff members.
- Online time rankings.
- Staff coverage by day and hour.
- Individual statistics and activity history.
- Weekly goal tracking.
- Alerts requiring attention.

## Requirements

| Requirement | Version |
|---|---|
| Minecraft | 1.21.x |
| Server software | Paper |
| Java | 21 |
| LuckPerms | Optional |
| Storage | SQLite / MySQL |

## Installation

1. Download `StaffMonitor.jar` from [Releases](https://github.com/Mr-Saitam/StaffMonitor/releases).
2. Place the file in your server's `plugins/` directory.
3. Start or restart your server.
4. Assign the `staffmonitor.track` permission to the staff members you want to monitor.
5. Check the server console for the dashboard URL.

StaffMonitor uses SQLite by default, so no additional configuration is required to get started.

**Important:** Dashboard access requires approval through the server console by default.

## Documentation

Full documentation is available at:

**[mrsaitam.com/docs – StaffMonitor](https://mrsaitam.com/docs/#/staffmonitor/introduction)**

It includes guides covering installation, configuration, commands and permissions, dashboard access, Pterodactyl integration, MySQL configuration, privacy, and frequently asked questions.

## Building from Source

You need JDK 21 and Maven.

```bash
git clone https://github.com/Mr-Saitam/StaffMonitor.git
cd StaffMonitor
mvn clean verify
```

The compiled JAR will be available at:

```text
staffmonitor-core/target/StaffMonitor.jar
```

## Reporting Issues

Found a bug or have a suggestion?

You can open a [GitHub Issue](https://github.com/Mr-Saitam/StaffMonitor/issues).

When reporting an issue, please include:

- StaffMonitor version.
- Paper version.
- Storage type (SQLite or MySQL).
- Description of the issue and steps to reproduce it.

Do not share tokens, passwords, or private server information.

For security vulnerabilities, please refer to `SECURITY.md`.

## Project Status

**Current version:** `1.0.0-beta.1`

StaffMonitor is currently in beta. This release represents the first beta version of the free edition (Core).

Feedback, suggestions, and bug reports are always welcome.

---

<p align="center">
  Developed by <a href="https://mrsaitam.com">MrSaitam</a>
</p>
