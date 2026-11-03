# GitHub Projects Board Setup

Use a GitHub Projects board to manage work while keeping this repository as the source of truth.

## Recommended board

Name: **Kev.exe IT & Cloud Engineering Roadmap**

### Columns / statuses

1. **Backlog** — tasks not started.
2. **Ready** — prerequisites are met; task can begin.
3. **In Progress** — currently studying or building.
4. **Blocked** — waiting on hardware, access, an error, or clarification.
5. **Testing** — implementation complete; validation and troubleshooting remain.
6. **Done** — acceptance criteria met and documentation committed.

### Suggested fields

- Phase (single select: 0–9)
- Skill area (Networking, Windows, PowerShell, Azure, AWS, Cloud Operations, Career)
- Priority (High, Medium, Low)
- Estimated effort (1, 2, 4, 6 hours)
- Certification (AZ-900, AZ-104, AWS CCP, Cloud+, None)
- Evidence URL (text)
- Due date (optional)

## How to create it

1. Open the repository on GitHub.
2. Select **Projects** → **New project**.
3. Choose **Board**.
4. Name it `Kev.exe IT & Cloud Engineering Roadmap`.
5. Add the statuses above.
6. Add the custom fields above if available.
7. Create one issue per substantial lab or milestone.
8. Add issues to the project and set Phase/Priority.
9. Move each issue across the board as you work.

## Recommended views

- **Roadmap:** group by Phase and sort by priority.
- **Current Work:** filter Status = In Progress or Testing.
- **Certification Tracker:** group by Certification.
- **Blocked:** filter Status = Blocked.

## Important distinction

Markdown checkboxes in `TRACKER.md` do not automatically synchronize with GitHub Projects. Use the tracker for the overall checklist and the board for active task management. Link each issue to its project report or evidence folder.
