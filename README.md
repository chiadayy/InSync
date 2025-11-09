# InSync — Collaborative Calendar, At a Glance

**InSync** is a full-featured personal calendar with a powerful collaboration mode. Create shared spaces where members’ calendars **merge into one view**, each person assigned a **unique color**, so you can see the whole picture—month, week, or day—at once.

## How it works

1. **Sign in** → your personal calendar is created.
2. **Create a Shared Space** (e.g., “Exchange Group”, “Couple Calendar”) and invite others.
3. Members choose what to show (busy-only or full details) and get a **color**.
4. Open the **Merged View** to see everyone’s events layered in one calendar.
5. Create/drag events directly in the shared calendar (respecting permissions).

## Key concepts

* **Personal Calendar**: your private default calendar.
* **Shared Spaces**: collaborative calendars with members, roles, and a merged view.
* **Color Layers**: each member’s events render in their assigned color with a legend.
* **Visibility Modes**: Busy-only / Titles / Full details (per member, per space).

## Features

* Full calendar UI: **Month / Week / Day** views, drag-and-drop edits
* **Merged Calendar View** with per-member colors + legend
* **Filters**: toggle members on/off, focus hours, search by title/tag
* **Conflict Highlights**: subtle markers where events overlap
* **Quick Add**: click/drag to create events; add notes & locations
* **Recurring Events** (RRULE) and all-day support
* **Timezone-aware** rendering; per-user working hours
* **Roles & Permissions**: Owner/Admin/Member (create, edit, or view-only)
* **Privacy Controls**: choose what others see (busy-only to full details)
* **Offline viewing** with realtime sync when online

## Why it’s useful

* See **everything in one place** without jumping between calendars.
* Keep privacy by sharing only what you choose.
* Plan faster with colors, filters, and conflict cues instead of juggling tabs.

## (Optional) Tech stack

* Next.js + React + TypeScript
* Firebase Auth + Firestore (offline enabled)
* Cloud Functions (invites, notifications)
* Luxon + rrule (timezones & recurrence)

> TL;DR: It’s your calendar—**plus** a color-coded, merged view for groups.
