<<<<<<< HEAD
# ClassOS

A shared workspace for a college class section. The class representative (CR) sets up
the timetable once, students join by link, and the whole class sees one live timetable
with changes (e.g. 3rd period cancelled). Each student also tracks their own
attendance privately and gets a safe-bunk planner so they never get detained.

## Features (MVP)
- CR sets up the section timetable once; students join via a link
- Live shared timetable showing changes and cancellations
- Private per-student attendance tracking (2-tap marking)
- Safe-bunk planner (attendance threshold rule, 75% is common; NIE's exact rule still to verify)
- Class sees aggregates only; individual attendance is private
- Calendar (ICS) export

## Tech stack
Python, FastAPI, PostgreSQL (SQLAlchemy, Alembic), React + TypeScript PWA,
pytest, Docker, GitHub Actions

## Status
Early development. Currently: Milestone 1 (foundation and core backend).

## Roadmap
- M1: repo, schema, bunk-math logic with tests
- M2: FastAPI, roles (CR/student), join links, ICS export
- M3: React + TypeScript PWA
- M4: Docker, CI, deployment, launch to my section

## Privacy
Attendance is private by default. No college ERP scraping.
