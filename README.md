# My Web Projects

Hi, I'm **Bryan Cubeles**. I build personal web projects around interests and real needs, with the aim of making them useful, sustainable and a way to show what I am learning.

**[Explore my project list →](https://github.com/stars/bryancubeles7e9-ai/lists/my-web-projects)**

| Project | About | Status | Website |
| --- | --- | --- | --- |
| **[UFCinfo](https://github.com/bryancubeles7e9-ai/UFCinfo)** | An independent UFC companion built from a fan's perspective: events, fighters, rankings, fight comparisons and sourced rumors. | Online · validating automation and polishing the experience. | **[Visit UFCinfo →](https://ufcinfo.onrender.com)** |
| **Arroier** | A music project website. | Coming soon. | **[Visit Arroier →](https://arroier.onrender.com/)** |

## UFCinfo — Inside the fight

A place to check fight cards, discover fighters and follow your favorites without searching for every detail separately.

- Events with available main cards, prelims and results, plus calendar downloads.
- A fighter directory with compact and card views, quick filters, champions and retired legends.
- Profiles organized into overview, statistics and fight history from the available event cards.
- Division and pound-for-pound rankings, plus the **Fight Lab** comparison tool.
- **My Corner** for followed fighters and their announced bouts, with spoiler controls for fight results.
- Spanish, English and Catalan, light and dark themes, and responsive layouts.

### Current focus

**Automation validation comes first.** Rumor collection is working and considered validated in use. Post-event updates are partially validated, with a new recovery patch awaiting the next event. New-event discovery still needs to be checked against a fresh announcement.

Once those three flows are validated, the next steps are mobile and performance polish, feedback from UFC fans, and preparation for a wider public launch. An installable web app and a mobile application are future options; they are not available yet.

UFCinfo uses scheduled data snapshots rather than live, blow-by-blow coverage. Opening a fighter profile does not trigger an extra paid provider request. Sources and consultation dates help explain the scope and freshness of the information.

**[Read how UFCinfo works →](https://github.com/bryancubeles7e9-ai/UFCinfo#readme)**

## How I build

UFCinfo combines **HTML, CSS and JavaScript** with a **Python and SQLite** account server. Scheduled jobs use **GitHub Actions**, with external scheduling through **cron-job.org**, and the website is hosted on **Render**.

I use these projects to learn by building, improve reliability through real use, and turn personal interests into useful web experiences.

---

Built by **Bryan Cubeles** · Version controlled with GitHub · Hosted on Render
