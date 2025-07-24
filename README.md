<div align="center">

# Server Monitor for SINEWAVE Development

A real-time statistics monitoring system for the SINEWAVE Development Discord server

</div>

## Overview

1. **Discord Bot**: Collects member count and message activity data every 10 minutes
2. **Web Dashboard**: Displays beautiful, interactive charts of server statistics
3. **Data Storage**: Maintains historical records in JSON files with automatic GitHub commits

<div align="center">

## ☕ [Support my work on Ko-Fi](https://ko-fi.com/thatsinewave)

</div>

## Features

### Live Statistics
- Real-time member count tracking (total and online)
- Message activity monitoring (messages per 10-minute interval)
- Historical data visualization with interactive charts

### Dashboard
- Sleek, dark-themed interface with SINEWAVE branding
- Responsive design that works on all devices
- Custom time range selection (hour, day, week, month, or all time)
- Auto-refresh capability

### Data Management
- Automatic data collection every 10 minutes
- Data retention for 7 days (configurable)
- Automatic Git commits and pushes to maintain version history

## Technical Details

### System Architecture
- **Backend**: Python Discord bot using discord.py
- **Frontend**: Modern HTML/CSS/JavaScript dashboard
- **Data Storage**: JSON files with Git version control
- **Visualization**: Chart.js for interactive graphs

### Key Components
- `monitor.py`: Discord bot that collects and stores statistics
- `index.html`: Dashboard interface
- `styles.css`: Custom styling for the dashboard
- `script.js`: Interactive functionality and chart rendering
- `member_count.json`: Historical member data
- `messages.json`: Historical message activity data

<div align="center">

## [Join my discord server](https://thatsinewave.github.io/Discord-Redirect/)

</div>

## Data Collection

The bot collects two types of data:

1. **Member Statistics**:
   - Total server members
   - Online members (any status except offline)

2. **Message Activity**:
   - Count of messages sent in all channels in 10-minute intervals

Data is stored in JSON format and automatically committed to GitHub every 10 minutes.

## Bot Commands

- `/stats`: Displays server statistics directly in Discord
  - Shows member counts and message activity for different time periods (1 day, 3 days, 7 days)

## Dashboard Usage

The web dashboard provides:

- Current status overview (total members, online members, recent messages)
- Interactive line charts for member and message statistics
- Time range selector to view different periods
- Manual refresh and auto-refresh options

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Discord.py for the Discord API wrapper
- Chart.js for beautiful data visualization
- GitHub for data storage and version control
