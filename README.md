# FilmHall

A web application that allows users to browse movies, view showtimes, select seats, and book cinema tickets.

## Project structure

```text
FilmHall/
├── client/                 # React + Vite frontend
│   └── src/
│       ├── components/     # Shared UI
│       ├── features/       # booking/, movies/, showtimes/
│       ├── hooks/
│       ├── pages/
│       ├── services/       # API calls
│       ├── styles/
│       └── utils/
├── server/                 # Node.js + Express API
│   ├── src/                # config, controllers, middleware, models, routes, services
│   └── tests/
├── database/               # Reserved for the team's database choice
└── docs/                   # Requirements, backlog, team roles, and workflow
```

## Week 1 documents

- [Week 1 checklist](docs/week-1-checklist.md)
- [Requirements draft](docs/requirements.md)
- [Prioritized product backlog](docs/product-backlog.md)
- [Team roles](docs/team-roles.md)
- [Git workflow](docs/git-workflow.md)

These are working drafts for the team to review onsite and submit for supervisor approval. Do not treat proposed requirements, role assignments, or workflow as agreed until the team confirms them.

## Run locally

Install Node.js 20.19+ or 22.12+ and npm, then run in a terminal from the repository root:

```sh
npm install
npm run dev
```

The frontend runs at <http://localhost:5173> and the API at <http://localhost:3000>. Check the API at <http://localhost:3000/api/health>.

The database folder is a placeholder until the team chooses a database. Copy `server/.env.example` to `server/.env` to configure the API locally.