# Ankit Ghag

Backend developer based in Mumbai.

I spend most of my time thinking about how data moves through systems — how it gets stored, retrieved, transformed, and why it sometimes breaks in ways nobody expected.

My day job at CMIE involves migrating a large legacy codebase from C to Python and PostgreSQL. It's not glamorous work. You're not building new features — you're understanding a 30-year-old system well enough to rebuild it correctly, without breaking the data that thousands of people depend on. That kind of work teaches you to be careful before being clever.

---

## What I use at work

- **Python** — primary language, day to day
- **PostgreSQL** — not just as a storage layer. CTEs, query planning, transaction boundaries, data integrity. I think about the database as part of the design, not an afterthought.
- **ETL pipelines** — adapting and rebuilding data processing workflows
- **Git** — version control, obviously
- **Linux** — CLI-first, comfortable in a terminal

---

## What I'm building with on my own

Outside work I use personal projects to learn things my job doesn't cover yet.

- **FastAPI + SQLAlchemy** — building a web filesystem REST API with proper layered architecture (routes → services → repositories)
- **JWT authentication** — access and refresh token patterns, token rotation. Built this from scratch to actually understand it, not just use a library.
- **Docker** — containerizing the filesystem project. Understanding why environments differ and how to make them not.
- **Cloudflare R2** — object storage, separating file content from metadata in PostgreSQL
- **Python sockets + selectors** — built a multiplayer game using raw sockets to understand non-blocking I/O below the HTTP layer

---

## What pulls my attention

**Database internals** — how PostgreSQL decides to execute a query, what the planner does, when indexes help and when they don't. Reading about this doesn't feel like work.

**System design** — how large systems stay consistent when things go wrong. What happens during a network partition. Where data can lie to you. Working through *Designing Data-Intensive Applications* by Martin Kleppmann right now and it's changing how I think about everything I've built so far.

**Clean architecture** — routes should not talk to the database directly. Business logic should not know what framework it's running in. Not rules I follow blindly — things I've seen break when ignored.

---

## Projects

**[web-filesystem-api](https://github.com/ankitghag/web-filesystem-api)**
`FastAPI` `PostgreSQL` `SQLAlchemy` `JWT` `Cloudflare R2` `Docker`

Backend service simulating a filesystem. File and folder operations, Linux-style permissions (user/group/other), JWT auth with refresh tokens, R2 for file storage, soft delete. The interesting part wasn't the endpoints — it was deciding where responsibilities live and keeping them there.

**[tic-tac-toe-sockets](https://github.com/ankitghag/tic-tac-toe-sockets)**
`Python` `Sockets` `Selectors`

Real-time multiplayer game using raw Python sockets. One server, multiple concurrent clients, no threads. Built it to understand what actually happens below FastAPI.

---

## Currently

- Migrating legacy data pipelines at CMIE — Python, PostgreSQL, getting the numbers right
- Reading *Designing Data-Intensive Applications* — slowly, properly
- Preparing for AWS Solutions Architect
- Looking for a backend role where the problems are harder than adding endpoints

---

## Reach me

ankitghag16@gmail.com · Mumbai, India
