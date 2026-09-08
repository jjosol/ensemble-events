# Ensemble Events

Event operations web application for **event management, registrations, and attendee coordination**.

**Role:** Founder & Full-Stack Developer · Elevate General Trading  
**Type:** Production client web app

Client production source stays private. This repo documents the product, architecture, and stack.

---

## Problem

Event teams needed one place to run an event: who is registered, who is attending, and how coordination happens before and during the event — without spreading that work across spreadsheets and chat.

---

## What it does

- Event setup and operational overview
- Registration capture and attendee records
- Attendee coordination for organizers
- Admin workflows for day-of operations

---

## Stack

| Layer | Choice |
| --- | --- |
| Frontend | React, TypeScript, Next.js |
| Design | Figma / Framer → implemented UI |
| Backend | Supabase (PostgreSQL), auth, REST-style APIs |
| Delivery | Full lifecycle: discovery, build, deploy, support |

---

## Architecture (high level)

```
Organizers & staff  →  Web app (Next.js)
                           │
                           ▼
                    Supabase Auth + PostgreSQL
                    (events, registrations, attendees)
```

---

## My role

Scoped the product with the client, designed the UI, implemented frontend and data layer, deployed, and provided post-launch support.

---

## Related

Portfolio hub: [github.com/jjosol](https://github.com/jjosol)
