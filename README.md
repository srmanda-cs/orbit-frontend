# Orbit Frontend

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

Flutter frontend for Orbit - my personal calendar management system.

## What is this?

Flutter app (Web/iOS/Android) that will:
- Display calendar with events
- Show synced calendars
- Allow event creation/editing
- Public booking page

## Tech Stack

- **Flutter** - Cross-platform framework
- **Dart** - Programming language
- **Deployment** - orbit.srmanda.com (planned)

## Setup

```bash
# Clone and setup
git clone https://github.com/srmanda-cs/orbit-frontend.git
cd orbit-frontend
git checkout development

# Install and run
flutter pub get
flutter run -d chrome  # For web
```

## Branches

- **master** - Production
- **development** - Active development

## Backend
Connects to [orbit-backend](https://github.com/srmanda-cs/orbit-backend)
