# Walkthrough Studio

A single-file 3D floor-plan walkthrough for client meetings. Open `index.html`
in a browser (needs internet for three.js and fonts). You can also drop it into
Claude Design.

- **Coach House** (2965 Travis Ave, 1,481 sf + 841 sf garage) modeled from
  sheets A2 and A3, plus two sample plans (The Alder, Suite 210).
- **Add a plan**: upload a PDF or image, set the scale from a known
  dimension, trace rooms, doors, openings and windows, and save. In
  claude.ai, "Draft with Claude" can rough in the tracing for you.
- **Walk** in first person (W A S D or arrows, drag to look, on-screen pad on
  phones) or switch to **Overview** for a dollhouse view.
- **Live floor plan** shows where you're standing. Click it to jump anywhere.
- **Guided tour** walks room to room on its own.
- **Walk notes** pin to the spot you're standing. In claude.ai, notes and
  saved plans are shared with everyone who can open the page; opened as a
  plain file they save in that browser only.
- **Room schedule** with sizes, areas and floor finishes.

Built-in plans are room rectangles plus door and window openings in the
`PLANS` object near the top of the script. Modeled sizes are approximate;
the drawings govern.
