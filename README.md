# Golden Arrow Tracking

## Focus
- Build and ship the **weekly-time** MVP with core task timing, weekly budget tracking, and Sunday review.

## Projects

### 1) Weekly Timer Mobile App (Frontend)
**Goal:** Deliver a usable cross-platform app (iOS/Android/Web) for weekly time budgeting.

**Status:** In progress

**Current scope:**
- Task list with per-task weekly hour budgets
- Start/stop timer per task
- Weekly progress bars (planned vs actual)
- Weekly reset + review summary

### 2) API and Data Layer (Backend)
**Goal:** Add persistence and sync for tasks, sessions, and weekly summaries.

**Status:** Planned

**Current scope:**
- CRUD for tasks and budgets
- Time session tracking endpoints
- Weekly summary endpoint

## Backlog
- User authentication (email/social)
- Cloud sync between devices
- Editable weekly templates
- Category tags (coding, school, gym, etc.)
- Reminders/notifications for active timers
- Data export (CSV)
- Streaks and weekly insights
- Basic onboarding flow
- Offline-first caching strategy

## This Week
- Replace starter screens with actual weekly-time UX
- Define core task and session models
- Add local persistence for tasks and active timer state
- Add weekly totals and remaining-time calculation
- Prepare simple Sunday review screen

## In Progress
- Product framing and initial app scaffold cleanup

## Next Up
- Task creation/edit UI
- Timer controls (start, pause, stop)
- Weekly budget progress components

## Blocked / Risks
- Backend shape not finalized yet
- Weekly rollover behavior decisions needed (timezone + reset timing)

## Done
- Repository initialized
- Expo starter app bootstrapped
- Initial project concept documented

## Tracking Cadence
- Daily: update In Progress / Blocked
- Weekly (Sunday): move completed work to Done and refresh This Week
