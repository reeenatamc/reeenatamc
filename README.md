# Renata Maldonado

Backend developer in Loja, Ecuador. Python, Django, FastAPI, PostgreSQL.
Open to remote work.

## What I build

### [lastseen-back](https://github.com/reeenatamc/lastseen-back)
Parses WhatsApp exports and rebuilds the emotional timeline of a conversation.
FastAPI, Celery, async SQLAlchemy on PostgreSQL, Alembic, Docker. The analyzers
only ever receive aggregated metrics, never raw message content.
[Frontend here](https://github.com/reeenatamc/lastseen-front).

### [ecg-pipeline](https://github.com/reeenatamc/ecg-pipeline) and [api-EKG](https://github.com/reeenatamc/api-EKG)
A photograph of a paper ECG becomes a digitized signal, gets quality-gated, and
is scored against 150 diagnostic classes. The pipeline is a packaged Python CLI
under mypy strict. The API is Django and DRF, and owns accounts, uploads and the
job queue. There is a [mobile client](https://github.com/reeenatamc/app-EKG-T)
as well.

### [seguros-arqsoft](https://github.com/reeenatamc/seguros-arqsoft)
Insurance asset management in Django and Celery: background report generation,
role-based access, audit history. I wrote the application layer and led the
project. It won UTPL's insurance systems contest.

### [feuoir](https://github.com/reeenatamc/feuoir)
NestJS API in hexagonal layers, with order state kept separate from payment
state behind a swappable payment provider port.

### [tracker-b](https://github.com/reeenatamc/tracker-b)
Offline training tracker built out of my own eight-sheet spreadsheet. The
progression rules are pure functions, and it will not suggest more weight when
pain is logged.

## Day job

Backend developer at SOLNUSTEC, working on Odoo and Django: PostgreSQL
concurrency and race-condition work, reporting systems. Around 90 merged pull
requests so far. Those repositories are private.

## Tech

Python · Django · FastAPI · PostgreSQL · Redis · Celery · Docker · Odoo
