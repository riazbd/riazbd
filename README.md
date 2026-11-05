# Nur Uddin Riaz

**Full-stack developer, Dhaka — [riaznur.com](https://riaznur.com)**

[![Portfolio](https://img.shields.io/badge/riaznur.com-7c3aed?style=flat-square&logo=firefox&logoColor=white)](https://riaznur.com)
[![Email](https://img.shields.io/badge/hello@riaznur.com-111827?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@riaznur.com)

I build the web applications businesses actually run on — the ones with real rules inside
them, where being wrong has consequences that are not cosmetic. Five years of it: a
compliance platform banks screen customers with, a CRM that follows a student from a first
enquiry to a visa approval, a resort that cannot sell the same room twice, a mail server
that sends its own campaigns.

Most of that work is built for Bangladesh, which is its own engineering problem: prices in
Taka, payments through bKash and Nagad, interfaces that have to read correctly in Bangla
and English, and networks where a visitor's IP changes between two requests.

---

## What I have built

### [Resort Mela](https://resortmela.com) — multi-tenant resort management SaaS
`NestJS` · `Next.js` · `TypeScript` · `MySQL`

Bookings, front desk, restaurant, expenses, payroll, agent commissions and the reports an
owner reads on their phone at the end of the day — sold on subscription to resort owners
and travel agencies, each on their own plan.

The part worth stating: a room cannot be sold twice. Not *should not* — every room-night is
a row under a unique constraint, so two people booking the same room at the same moment get
exactly one success between them, decided by the database rather than by a check that two
requests can both pass. 759 API tests and 117 front-end tests hold it in place, and the
revenue grid matches the hand-kept books to 98.9%.

### [PEPS BD](https://pepsbd.com) — AML and PEP compliance screening
`Laravel` · `PostgreSQL` · `React` · `Redis` · `Docker`

Banks and financial institutions in Bangladesh screen their customers against a curated
database of politically exposed persons, with profiles linked to the news and media
exposure that explains why someone is on the list. Three tiers — super admin, organisation,
end user — with per-role permissions a bank's own admin can set, and case management on
top: search, bookmark, assign, track.

Built and maintained end to end by one engineer, from an empty database to a subscription
product in production.

### [RootMail](https://rootmail.rootcodebd.com) — email marketing on its own mail server
`Next.js` · `TypeScript` · `PostgreSQL` · `Node.js` · `Linux`

Campaigns, automations, segments and analytics for Bangladeshi businesses, sending from a
mail server I run rather than a reseller's — customer domains signed with their own DKIM
keys, an SMTP gateway and API for transactional mail, priced in Taka and paid through
bKash and Nagad.

### [Nobodigonto](https://nobodigonto.news) — bilingual news portal and newsroom
`Laravel` · `React` · `Tailwind CSS` · `PHP`

A Bangla and English news portal — reader site, e-paper and archive — with a newsroom
behind it: seven dashboards, one for every editorial role from reporter to
editor-in-chief, across ten page types.

### Globex Education — CRM, HRM and ERP in one system
`Laravel` · `MySQL` · `Vue.js` · `Redis`

The full student lifecycle for a visa and overseas education consultancy: leads captured
straight from Facebook and Instagram campaigns, through counselling and payments, to visa
approval — with SMS at the steps that matter and role-based access for admins, counsellors
and agents.

### [Toteddy Shop](https://toteddyshop.com) — e-commerce with two physical branches
`Laravel` · `Pathao Courier API` · `Payment Gateway`

A live Bangladeshi store with retail branches in Dhaka: courier handover automated through
Pathao, payment confirmation driven by webhooks rather than polling, and an affiliate
system on top.

### [riaznur.com](https://riaznur.com) — this profile's longer half
`Next.js` · `TypeScript` · `PostgreSQL` · `Docker` · `Caddy`

My own site, and the one project whose [source decisions are written up in
public](https://riaznur.com/blog): every word of it editable from a custom admin,
self-hosted on a VPS with a deploy that rolls itself back, and an AI assistant that answers
only from the site's own published rows — so it cannot invent a client, a number or a year.

---

## How I work

- **You own the code from the first commit.** The repository is in your account, the
  servers and third-party services are in your name, and nothing is licensed back to me.
- **Fixed price when the shape is clear**, so you are not carrying the risk of my estimate
  being wrong. Hourly or monthly when the next step depends on what the last one taught us.
- **A short paid review first** on existing codebases: what is there, what is risky, what
  it would take. Useful on its own even if you hand it to someone else afterwards.
- **I work with your team, your process and your repository** when there is one.

---

## Stack

Laravel and PHP, Node.js with NestJS and Express, TypeScript everywhere it fits.
React, Next.js, Vue, Tailwind. PostgreSQL and MySQL, Redis where it earns its place.
Docker, Caddy, GitHub Actions, Linux servers I administer myself.

Strongest where the schema meets the interface — I am as comfortable designing the indexes
as building the screen that reads them, and most interesting problems live on that border.

---

## Where I have worked

| Period | Role | Company |
|--------|------|---------|
| Jan 2025 – Present | Software Engineer | MHS Planet, Dhaka |
| Oct 2023 – Nov 2024 | Software Engineer | Solruf India (remote) |
| Nov 2022 – Nov 2023 | Full-Stack Developer | Dream Driver IT Solutions, Netherlands (remote) |
| Sep 2021 – Oct 2022 | Junior Software Engineer | Shiny Gleam Softwares, Dhaka |

Five years, across teams in Bangladesh, India and the Netherlands.

---

## About the repositories here

Nearly everything above is private or closed — client codebases and products that cannot be
opened. What is public here is older and smaller than what I do now. If you want to see how
I think about a problem, the write-ups at [riaznur.com/blog](https://riaznur.com/blog) are
the real answer, and I am glad to walk through any of this in detail.

---

**Open to freelance work — one project at a time — and to the right full-time role.**

[riaznur.com](https://riaznur.com) · hello@riaznur.com · nuruddinriaz5@gmail.com · +880 1521 323426 · Dhaka, Bangladesh
