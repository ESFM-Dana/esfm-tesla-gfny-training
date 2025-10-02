# ESFM Tesla GFNY — Training Site: All-in-One Pack

This bundle contains everything you need to publish and maintain a public, mobile-friendly training hub for frontline, leads, managers, and projects.

## What's included
1. **Starter site** — Just-the-Docs theme, homepage, Restrooms, Cafés, Lobbies, Route Cards, About.
2. **Add-on pages** — Emergency Evacuation, Janitor’s Closet, Trash Collection.
3. **Role pages** — Managers, Shift Leads, Floor Techs, Factory EVS, Projects.
4. **Download Center + End-of-Shift** — Download Center page; EoS pages for frontline & managers; role folders for PDFs/DOCs.
5. **Project Workers Training** — Full training page + print-friendly Quick Card (HTML).

## Quick deploy (5 steps)
1. Create a **public** GitHub repo (e.g., `esfm-tesla-gfny-training`).
2. Unzip **Starter site** and upload all contents to the repo root.
3. In **Settings → Pages**: Source = **Deploy from a branch**, Branch = `main`, Folder `/ (root)` → Save.
4. Unzip and upload the **Add-on pages**, **Role pages**, **Download Center & EoS**, and **Project Workers** files to the repo root (and `assets/files/...` for PDFs/DOCs).
5. Wait ~1 minute; your site is live at `https://<user>.github.io/<repo>/`.

## Page filenames & nav order
- `index.md` (1) — Home
- `restrooms.md` (2) — Restrooms
- `cafes.md` (3) — Cafés
- `lobbies.md` (4) — Lobbies
- `route-cards.md` (5) — Route Cards
- `about.md` (6) — How to Contribute
- `emergency-evacuation.md` (7)
- `janitor-closets.md` (8)
- `trash-collection.md` (9)
- `managers.md` (10)
- `shift-leads.md` (11)
- `floor-techs.md` (12)
- `factory-evs.md` (13)
- `projects.md` (14)
- `project-workers-training.md` (15)
- `downloads.md` (16)
- `end-of-shift-frontline.md` (17)
- `end-of-shift-managers.md` (18)

## Download Center hook-up
- Put your PDFs/DOCs under `assets/files/<role>/` (frontline, shift-leads, managers, floor-techs, factory-evs, projects).
- Edit `downloads.md` to point links at your actual filenames, e.g.:
  `[End of Shift — Frontline (PDF)](/assets/files/frontline/End-of-Shift-Frontline.pdf)`

## Share links
- Site home: `https://<user>.github.io/<repo>/`
- Direct pages: `/restrooms`, `/cafes`, `/lobbies`, `/route-cards`, `/downloads`, `/project-workers-training`, etc.

## Email managers (paste & send)
Subject: EVS Training Hub is live (easy access for crews)

Hi all,

I’ve organized our EVS training and quick-reference docs into a single, mobile-friendly site for easy sharing with your crews:

Site: https://<user>.github.io/<repo>/  
Download Center: https://<user>.github.io/<repo>/downloads

What’s inside:
- Frontline SOPs: Restrooms, Cafés/Kitchenettes, Lobbies
- Route Cards & Frequencies
- Emergency Evacuation (EVS) & Janitor’s Closet
- Trash Collection
- Role pages: Managers, Shift Leads, Floor Techs, Factory EVS, Project Work
- Download Center for PDFs/DOCs
- Project Workers — full training page + quick card

Note: The master files still live on SharePoint for record-keeping and version control: <SharePoint link>. The GitHub site is for quick reference and easy distribution to the floor.

If you hit any issues or need a new one-pager, tell me and I’ll help.

Thanks,  
Dana