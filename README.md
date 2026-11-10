# FORMA — Fitness coaching web platform

FORMA brings training plans, progress records, weekly check-ins, and coach feedback into one place. The project is in private testing.

## Implemented workflows

- **Client workspace:** Follow a workout plan, record training and nutrition, review progress, and share a weekly summary with a coach.
- **Coach workspace:** Review client updates and suggest changes for up to three movements per session, with sets, reps, or duration. Once a suggestion is accepted, the client can preview the updated plan.
- **Records and communication:** Persistent training and nutrition records, coach-client communication, and data export and backup workflows.
- **Navigation and accessibility:** Separate client, coach, and admin workspaces, more consistent coach and admin navigation, and keyboard skip links across all three.

## Verified development milestones

| Version | Change |
| --- | --- |
| 0.54 | Regression baseline: 46 of 46 tests passed. |
| 0.57 | Added movement suggestions and client preview. Tested invalid targets, resubmission, and conflicts when a plan changed after a suggestion was created. |
| 0.58 | Unified coach and admin navigation and checked desktop transitions. |
| 0.59 | Added keyboard skip links. All 47 regression tests, TypeScript checks, the build, and desktop Chrome checks passed. |

The technical work included SQLite integration tests. The latest checks did not cover the full coach-to-client flow with two live accounts, live writes, narrow layouts, or iPhone/Safari.

## Planned work

Live AI coaching, personalized nutrition guidance, supplement and lab-record workflows, payments, and external notifications remain on the roadmap. This repository contains the portfolio case study only.

[Atakan Erez — Portfolio](https://atakanerez.tr/)
