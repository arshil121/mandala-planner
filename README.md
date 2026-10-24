# Mandala Planner

A free, single-file goal planner built on the Mandala Chart method. Turn one big goal into 64 concrete actions, pick your weekly priorities, and schedule them. No sign-up, no server, no tracking.

**Live demo:** `https://<your-username>.github.io/<repo-name>/`

## How it works

1. **Name your main goal.** Write an outcome, not an activity.
2. **Fill the 3×3 grid.** Add the eight strategic areas around your goal.
3. **Expand each area.** Every strategic goal becomes the center of its own 3×3 block with eight actions.
4. **Refine.** Warnings flag vague or outcome-based actions, such as "get 1 million views". They only advise and never block saving.
5. **Pick 5–8 actions for the week**, set dates and times, and export them to your calendar.
6. **Track progress** with separate planning, execution and weekly completion numbers.

## Features

- Linked 3×3 and 9×9 views of one dataset: 1 goal, 8 strategic goals, 64 actions
- Brain dump for quick idea capture, then move ideas into action slots
- Action plan with status, date, start time, duration and overlap warnings
- Weekly priorities with reordering, plus today's agenda
- Calendar export (`.ics`), full backup and import (`.json`), and actions export (`.csv`)
- Undo and redo, light and dark themes, keyboard-accessible, works on mobile

## Your data

Everything is saved automatically in your browser's `localStorage`. It stays after you close the tab or browser. Each visitor has their own private copy.

- It is not a cloud backup and does not sync between devices or browsers.
- Clearing site data or using private mode erases it.
- Use **Data → Backup (JSON)** now and then, and **Import** to restore.

## Run it

Open `index.html` in any modern browser. To host it for free, push it to a GitHub repo and enable **Settings → Pages** on the main branch (root folder).

## Tech

Plain HTML, CSS and JavaScript in one file. No build step and no dependencies. The only external request is an optional Google Font, which falls back to system fonts.
