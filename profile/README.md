# NEXUS

**The student club at the University of St. Thomas that builds things with AI.**

<p align="center">
  <a href="https://ustnexus.club">ustnexus.club</a> ·
  <a href="https://build.ustnexus.club">Build workshop</a> ·
  <a href="https://ustnexus.club/buildfest/">Buildfest</a> ·
  <a href="https://ustnexus.club/board.html">The board</a>
</p>

---

NEXUS is a student-run organisation in St. Paul, Minnesota. We run workshops, build projects, and
host Buildfest, the campus hackathon. Everything in this organisation was written by students, it is
all deployed and running right now, and most of it is meant to be copied — the workshop repository in
particular exists so that any club, anywhere, can re-run the same session without asking us first.

## What we do

- **Workshops.** Short, practical sessions with no prerequisites. The flagship is *Build Your Personal
  Website*: from nothing to a live site in about twenty minutes, first run 4 December 2025.
- **Buildfest.** A campus hackathon on the theme *AI for the Common Good*, open to students of any
  major and any experience level, judged by working practitioners. The 2026 winners — Sofa, CarryOn
  and RoutesForGood — are credited on the event site.
- **Projects.** Members take an idea to something other people can actually open in a browser.
- **The club itself.** Eight board members run recruitment, events, sponsorship and the website, and
  every one of them is named and linked on [the board page](https://ustnexus.club/board.html).

## The repositories

| Repository | What it is |
|---|---|
| [ClubPage](https://github.com/NEXUS-UST/ClubPage) | The club site — [ustnexus.club](https://ustnexus.club). Homepage, board page, the Buildfest microsite and a branded 404. Static HTML, CSS and vanilla JavaScript on GitHub Pages. |
| [build-workshop](https://github.com/NEXUS-UST/build-workshop) | *Build Your Personal Website*, start to finish, at [build.ustnexus.club](https://build.ustnexus.club). The slides, the live demo script, the presenter notes and the follow-up reference — one page, no build step. |
| [nexus-forum](https://github.com/NEXUS-UST/nexus-forum) | An earlier attempt at a community forum. Archived, and not deployed. |

Two more repositories — an internal members site and the original Buildfest event build — are private,
because they carry member and registration data. They are not linked here on purpose.

## How this is built, and why it looks like this

Every site in this organisation is hand-written HTML, CSS and vanilla JavaScript served by GitHub
Pages on a custom domain. No framework, no bundler, no build step, no CI. That is a deliberate choice
for a club whose maintainers change every year: a new member with a text editor can fix a typo and
watch it go live two minutes later, and nothing rots between semesters because there is nothing to
upgrade. The whole stack is a repository, a `CNAME` file and a push to `main`.

The house style is shared across the sites: a dark theme, University of St. Thomas purple, Inter for
text and JetBrains Mono for code. Read [`style.css`](https://github.com/NEXUS-UST/ClubPage/blob/main/style.css)
if you want to lift it.

## Get involved

Students: come to an event, then join. Start at [ustnexus.club](https://ustnexus.club) and use the
contact details there. You do not need to know how to code — the workshops assume you do not.

Mentors, judges and sponsors: [Buildfest](https://ustnexus.club/buildfest/) is the one to look at.
It runs on the common-good theme, and the schedule, judging format and FAQ are all on the public page
so you can decide in five minutes whether it is worth your Saturday.

Other student organisations: take the workshop. It is a complete session — outline, slides, demo path
and handout — and re-running it costs you one afternoon of preparation instead of six.

<p align="center"><sub>Hosting and engineering support from <a href="https://github.com/ever-just">EVERJUST</a>.</sub></p>
