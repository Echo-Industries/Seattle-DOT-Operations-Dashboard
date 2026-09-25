# Seattle DOT Operations Dashboard

A real-time traffic operations and street maintenance management system for the Seattle Department of Transportation, built with Flask and designed for ER:LC (Emergency Response: Liberty County) game server integration.

## Features

- **Road Closure Logging**: Document street closures, detours, and traffic impacts
- **Safety Event Tracking**: Report and track roadway safety incidents and resolutions
- **Live Operations Hub**: Real-time synchronization with active SDOT personnel and units
- **Incident Analytics**: Interactive charts and metrics for closure patterns and response rates
- **Signal Infrastructure Map**: Visual corridor layout with signal locations and work zones
- **Multi-User Support**: Roblox OAuth2 authentication for secure access
- **Record Management**: Search, filter, and manage all historical incident reports

## Technology Stack

- **Backend**: Python Flask 3.0.2
- **Frontend**: HTML5, Tailwind CSS, Chart.js
- **Database**: SQLite3
- **Authentication**: Roblox OAuth2
- **API Integration**: ER:LC API for live server data

## Prerequisites

- Python 3.8+
- Roblox Developer Credentials (OAuth2 application)
- ER:LC Server Access (optional, for live unit sync)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Echo-Industries/Seattle-DOT-Operations-Dashboard.git
   cd Seattle-DOT-Operations-Dashboard