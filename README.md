# Fife Run — Sep 11–16, 2026 🛳️

A living itinerary for Robert & Suzanne (over from Belfast by ferry) and SO & Emily
(in from Buffalo via London), meeting at **The 1881 – A Period Home, Aberdour** for the
week — then everyone onward to Crete.

The whole plan lives in `index.html`. Edit that file, push, and the website updates.
No build step, no framework — it's one self-contained page.

**Photos:** the page has framed photo slots (the 1881, Cafebar 1912, Loch Ness). Drop JPEGs
into the [`img/`](img/) folder with the filenames listed in [`img/README.md`](img/README.md)
and they appear; until then each slot shows a neat placeholder. The ferry / house / Nessie /
castle artwork is drawn in SVG inside the page, so it needs no files.

---

## The shape of it

- **Fri 11** — Robert & Suzanne sail Belfast → Cairnryan (07:30), drive up via a lunch
  stop in Bathgate (Cafebar 1912), park at Waverley and meet SO & Emily off their train
  (~15:30), then over the Forth to Aberdour.
- **Sat 12 – Tue 15** — five nights in Fife. The "days in between" are the open part,
  meant to be filled in together.
- **Wed 16** — away early; drop SO & Emily at Edinburgh Waverley, then the group splits
  for Crete: SO & Emily via London, Robert & Suzanne via Belfast (Stena 15:30), meeting
  back up out in Crete.
- **Crete** — both parties at **Castello Village Resort, Sissi** (4★, bed & breakfast,
  7 nights from **Thu 17 Sep 2026**). Robert & Suzanne fly **Belfast Intl ⇄ Heraklion** with
  Jet2 (LS321 out Thu 17 15:10; LS322 back Thu 24 22:55); SO & Emily fly **London Gatwick ⇄
  Heraklion** with easyJet (EZY8217 out Thu 17 16:45; EZY8218 back Thu 24 23:40). Full
  door-to-door legs live on the **Travel** tab.

The page has four tabs: **Itinerary** (the plan), **Travel** (every flight/crossing), **Stay**
(accommodation), and **Build** (the running log). Booking references and payment details are
deliberately kept off this public page.

Full timings, addresses and the Stena timetable are all in the page.

---

## How to get it online (easiest first)

You only need **one** of these. Both are free for a static page like this.

### Option A — Vercel (recommended, ~3 minutes)
1. Push this folder to a new GitHub repo (steps below).
2. Go to **vercel.com**, sign in with GitHub.
3. **Add New → Project → Import** this repo.
4. Framework preset: **Other**. Leave build/output settings blank — it's plain HTML.
5. **Deploy.** You get a live URL like `fife-run.vercel.app`.
6. Every future `git push` redeploys automatically.

### Option B — GitHub Pages (no extra account)
1. Push to GitHub (below).
2. Repo → **Settings → Pages**.
3. Source: **Deploy from a branch** → `main` → `/ (root)` → **Save**.
4. Live in a minute or two at `https://<your-username>.github.io/<repo>/`.

> Vercel gives a tidier URL and instant redeploys; Pages is one less login. Either is fine.

### Getting it onto GitHub
```bash
cd trip
git init
git add .
git commit -m "First draft of the Fife itinerary"
# create an empty repo on github.com first, then:
git remote add origin https://github.com/<your-username>/<repo>.git
git branch -M main
git push -u origin main
```

---

## So both of you can edit

Add SO as a **collaborator** (repo → Settings → Collaborators) and you can both push
changes. Or he forks it and opens pull requests — either works. Because the plan is in
the repo rather than a frozen chat link, anything either of you adds shows up for the
other on the next push.

---

## 📋 For SO's Claude — start here

Robert's Claude drafted this. If you're SO's Claude picking it up, here's the context so
you can carry it forward:

- **Trip:** Belfast ⇄ Cairnryan by Stena ferry + car; based at *The 1881*, 44 Main St,
  Aberdour KY3 0UG; **Sep 11–16, 2026**; four adults.
- **Fixed points:** the **07:30** Belfast→Cairnryan sailing on the 11th, and meeting
  SO & Emily at **Edinburgh Waverley ~15:30** the same day. The return is the **15:30**
  Cairnryan→Belfast on the 16th.
- **Roles:** Robert & Suzanne do both ferry crossings with the car. SO & Emily arrive from
  Buffalo via London, leave on the 16th via London, and everyone reconvenes in Crete.
- **What's still open / where help is wanted:**
  - The **Sat 12 – Tue 15** days are unplanned — suggestions welcome (Edinburgh, Fife
    coast, East Neuk, Stirling, etc.).
  - **Onward Crete flights** aren't booked yet — SO & Emily route via London, Robert &
    Suzanne via Belfast. Once the dates and airports are set, the Wed 16 tracks can be
    firmed up.
- **To contribute:** edit `index.html` (the structure is plain, labelled sections) and
  push. Keep the departures-board style; times are in the mono font for a reason.

---

## A note on what's *not* in here

Booking confirmation codes and payment details are deliberately left **out** of this
public page. If you want those in the repo too, make the repo **private** first.
