# OutreachHub

A multi-tenant SaaS platform for businesses to manage contacts, message templates, and run targeted outreach campaigns. Built progressively while learning core full-stack technologies.

## Portals

- **Admin Portal** — admins manage workspaces and workspace users.
- **OutreachHub Portal** — workspace users manage contacts, templates, campaigns, and analytics.

## Features

- Multi-tenant workspaces
- Role-based access (Editor / Viewer)
- Contacts with tagging
- Message templates (Text / Text & Image)
- Campaigns with draft → running → completed status (via polling)
- Workspace analytics dashboard
- Support for users belonging to multiple workspaces

## Tech Stack

TBD

## Getting Started

### Prerequisites

- Node.js (LTS)
- npm or yarn
- Database (TBD)

### Installation

\```bash
git clone <repo-url>
cd <repo-name>
npm install
\```

### Configure Environment

\```bash
cp .env.example .env
# update .env with your database and auth settings
\```

### Run

\```bash
# start backend
npm run dev:backend

# start frontend (in a separate terminal)
npm run dev:frontend
\```

App should now be running locally (check the terminal output for the exact URL/port).

### Build for Production

\```bash
npm run build
npm start
\```

## Status

🚧 Work in progress — built module by module. See [Issues](../../issues) / [Projects](../../projects) for progress.

## License

TBD