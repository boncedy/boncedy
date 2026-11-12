# Hi, I'm Daranpob (Ball) 👋

Third-year Computer Science student at **Mahidol University** (Faculty of ICT),
taking a minor of **Software Engineering**.

## Featured work

### [Water Kiosk Sync Backend](https://github.com/boncedy/kiosk-sync-backend) · NestJS · Prisma · PostgreSQL

An ingestion API for water-vending kiosks that go offline for days at a time. Readings
are replayed over an unreliable link without duplication or loss, and every accepted
reading returns a **tamper-evident receipt** (`SHA-256` checksum + `HMAC-SHA256`
signature, verified with a timing-safe compare). Includes a fault-injecting network
simulator that tests offline queueing, dropped ACKs, captive portals and blackholed
links end to end. **249 unit tests**, `oxlint` clean.

### [Hotel Booking REST API](https://github.com/boncedy/hotel-booking-api) · NestJS · TypeORM · MySQL · Redis · Docker

A booking service with role-based auth, room inventory, image uploads and availability
search. Double bookings are prevented inside a transaction with a pessimistic row lock,
so concurrent requests serialise and the loser gets `409`. Caching uses versioned keys
so a whole namespace invalidates with a single increment. **57 tests** across unit,
integration and end-to-end suites; Swagger docs and a two-stage Docker build.

### [SketchRef](https://sketch-ref.vercel.app) · React · Vite · Express

A deployed drawing-reference gallery with per-user progress tracking, category
filtering and file uploads. **Live at [sketch-ref.vercel.app](https://sketch-ref.vercel.app)**.

## Toolbox

| | |
| --- | --- |
| **Languages** | TypeScript, JavaScript, Python, Java, C#, SQL |
| **Backend** | NestJS, Express, FastAPI, Prisma, TypeORM, REST, JWT, role-based access control |
| **Data** | PostgreSQL, MySQL, Redis (caching, invalidation), SQLite |
| **Testing** | Jest, Supertest, integration and end-to-end testing, fault injection |
| **Infra** | Docker, Docker Compose, GitHub Actions, Linux, Git |
| **Also** | React, Vite, HTML/CSS, Processing |

## Currently

- Building my portfolio from future works.
- Enhancing software skills and get more familiar with tools.
- Hardening current skills and fundamentals.

## Reach me

- **Email** — [boncedy@gmail.com](mailto:boncedy@gmail.com) · [daranpob.sia@student.mahidol.edu](mailto:daranpob.sia@student.mahidol.edu)
- **LinkedIn** — [daranpob-sianghen](https://www.linkedin.com/in/daranpob-sianghen-603032305/)
