<p align="center">
  <a href="https://chaplain.davishiggins.com"><img src="assets/hero.svg" width="100%" alt="Chaplain Platform for Phi Delta Theta NC Epsilon. Animated cover with the chapter shield and title beside an October calendar whose Thursday studies light in turn and the semester scripture plan rolling through a 'This week' frame." /></a>
</p>

<h1 align="center">Chaplain Platform</h1>

<p align="center"><strong>A chapter website that gives Phi Delta Theta's NC Epsilon chapter one place for weekly Bible study, the semester scripture plan, and chaplain resources.</strong></p>

<p align="center">
  <a href="https://chaplain.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="Visit the platform" /></a>&nbsp;
  <a href="https://www.higginsd.com/work/phi-delta-theta"><img src="assets/btn-case.svg" height="44" alt="Case study" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="Davis Higgins" /></a>
</p>

<p align="center"><sub>Live and in use · Built by Davis Higgins, Chaplain of NC Epsilon at UNC Charlotte</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="800" alt="Screen recording of the Chaplain Platform: moving from the home page to the Bible study calendar for October 2026, then to the semester scripture plan showing this week's passage." />
</p>

<p align="center"><sub>Real capture of chaplain.davishiggins.com: home, calendar, and scripture plan. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **This week, first.** The home page leads with this week's message and passage, and it moves to the next study automatically each week. Nobody has to remember to update it.
- **A calendar members can trust.** A month view marks every Thursday Bible study with its passage, so the whole semester is visible at a glance.
- **A semester with a shape.** A 16-week scripture plan moves through John, Philippians, and Colossians, with a title, a theme, and a short summary for discussion each week.

## Why I built it

As chaplain, I found that everything the chapter needed for its spiritual life was scattered across group chats and documents. Devotionals and weekly direction lived wherever they were last posted, and the same information got re-sent every week.

So I built the chapter one home organized around how it actually works: the current week leads, and the full semester sits underneath it.

## What I built

I designed and built the site end to end, and I wrote and maintain the semester plan it presents:

- Home, calendar, scripture plan, about, and contact views
- Scheduling that always shows the right study for the current week
- One place that holds the whole semester plan, so updating the site is quick
- Chapter-branded visuals, motion, and a phone-first layout

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    C[Semester plan<br/>16 weeks · passage · theme · summary] --> D[Weekly scheduling]
    D --> H[Home: this week's message]
    D --> K[Calendar: Thursday studies]
    C --> S[Scripture plan: full semester]
```

| Decision | Why |
|---|---|
| **The calendar drives the content** | The current study updates itself on schedule, so the site stays accurate all semester without anyone touching it. |
| **One plan for the whole semester** | Every passage, title, and summary lives in one place, so planning next semester means replacing the plan, not editing pages. |
| **Dates that mean the chapter's dates** | A Thursday study always shows on Thursday, wherever a member's phone thinks it is. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.png" alt="Chaplain Platform home page: 'Chaplain Platform' with this week's message, Control Your Thoughts, Philippians 4:8." /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.png" width="300" alt="Chaplain Platform home page on a phone." /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-calendar.png" alt="Bible Study Calendar for October 2026 with each Thursday's study and passage." /></td>
  </tr>
</table>

<sub>Home with this week's message · Bible study calendar · Home on mobile</sub>

## Technology

| Layer | Technology |
|---|---|
| App | React, Vite, JavaScript |
| Styling | Tailwind CSS |
| Motion | Framer Motion, GSAP |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://chaplain.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="Visit the platform" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. The Phi Delta Theta name, letters, and shield are marks of Phi Delta Theta Fraternity and appear here as used on the chapter's own site.</sub></p>
