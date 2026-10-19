# Walkthrough Studio

A single-file 3D floor-plan walkthrough for client meetings. Open `index.html`
in a browser (needs internet for three.js and fonts). You can also drop it into
Claude Design.

- **Two sample plans**: The Alder (3 bed / 2 bath residence) and Suite 210
  (office tenant improvement).
- **Walk** in first person (W A S D or arrows, drag to look, on-screen pad on
  phones) or switch to **Overview** for a dollhouse view.
- **Live floor plan** shows where you're standing. Click it to jump anywhere.
- **Guided tour** walks room to room on its own.
- **Walk notes** pin to the spot you're standing (saved in this browser only).
- **Room schedule** with sizes, areas and floor finishes.

Plans are defined as room rectangles plus door and window openings in the
`PLANS` object near the top of the script. Edit them to model a real job.
