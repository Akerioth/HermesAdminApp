# HermesAdminApp

HermesAdminApp is the full admin control panel for Hermes packet shop delivery. It is designed for one developer to manage vehicles, repairs, lost packets, fund packets, driver profiles, permissions, notes, and packetshop operations including opening times and shift management.

## Overview

This app covers:
- Vehicle management and repairs
- Lost packet tracking and recovery
- Funding packets and tracking funds
- Assigning fund sources and dates
- Packetshop opening times with two shifts
- Driver profile management
- Notes and task tracking
- Permissions and role control
- Admin workflow for delivery and shop operations

## Features

### Vehicle Management
- Add and update vehicles
- Track repairs and service history
- Assign vehicle status and availability
- Monitor vehicle usage for delivery operations

### Packet Management
- Create and track packets
- Mark packets as lost or delayed
- Attach recovery actions to lost packets
- Manage packet status from arrival to delivery

### Fund Management
- Record funded packets
- Track funding source (`fund by`)
- Assign funding date and reason
- Monitor packet funding history

### Packetshop Operation
- Configure packetshop opening times
- Two shifts support
  - Shift 1: morning
  - Shift 2: afternoon/evening
- Track shift schedules and staff availability

### Driver Profile Management
- Create and manage driver profiles
- Store driver contact details and license info
- Add notes for each driver
- Manage driver permissions and roles

### Admin Control
- Full admin dashboard
- Permissions management for users and staff
- Notes, alerts, and task assignment for admin users
- Issues and delivery monitoring

## Developer Setup

### Prerequisites
- Git installed
- Node.js and npm installed
- A code editor (Visual Studio Code recommended)
- Access to the repository and issue tracker

### Clone the repository

```bash
[link] git clone https://github.com/Akerioth/HermesAdminApp.git
cd HermesAdminApp
```

### Install dependencies

```bash
npm install
```

### Run the app locally

```bash
npm start
```

### Common scripts

- `npm start` - Run the app in development mode
- `npm test` - Run test suites
- `npm run build` - Build production files
- `npm run lint` - Run code linters

## Developer Tools

Recommended tools:
- Visual Studio Code
- Git CLI or Git GUI
- Node.js LTS
- npm or yarn
- Browser developer tools
- Postman or REST client for API testing
- VS Code extensions: ESLint, Prettier, GitLens

## Workflow

### Branching
- Create a feature branch from `main`:

```bash
git checkout main
git pull origin main
git checkout -b feature/main
```

### Commit messages
- Use clear commit messages
- Example: `feat: add vehicle repair logging`
- Include issue references when available

### Pull requests
- Push branch to remote:

```bash
git push origin feature/main
```

- Open a pull request with:
  - Summary of changes
  - Related issue numbers
  - Testing steps

### Issue tracking
- Submit issues for bugs and feature requests
- Use a clear title and description
- Include steps to reproduce and expected behavior
- Assign labels like `bug`, `enhancement`, `documentation`

## Requirements for Developers

Developers should know:
- JavaScript / TypeScript
- React, Vue, or chosen frontend framework
- Backend API concepts
- Git and version control workflow
- How to write clean, maintainable code
- Testing and debugging practices

## Release Process

1. Complete feature or fix
2. Update tests and run test suites
3. Update documentation if needed
4. Create a pull request
5. Review and merge
6. Deploy following release notes

## Submitting Issues and Commits

- Create an issue or ticket for every bug or feature.
- Reference issue IDs in commit messages.
- Keep commits focused on one change.
- Include a summary and testing details in PR description.

## Contact and Support

For questions, use the repository issue tracker or team communication channels.

## Notes

This README is the landing page for the HermesAdminApp developer. It includes steps from cloning the repo to submitting issues and commits, and outlines the application requirements and developer tools.
