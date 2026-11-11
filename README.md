# Cinema-beyond-Hollywood

## Topic
Has Cinema Gone Global? Origin, Reception and Commercial Success of Films since 2000

## About
This repository was created as part of the course
[DIS3.3 Data Integration](https://github.com/breuert/data-integration)
(Winter 2026/27, TH Köln) by [breuert](https://github.com/breuert).

## Team
| Name | GitHub |
|---|---|
| Finn Spiegel | [fespiegel](https://github.com/fespiegel) |
| Marlon Asah | [marlonasah](https://github.com/marlonasah) |
| Israel Nitu | [1sr4](https://github.com/1sr4) |
| Jonas Völler | [Saichiiro2133](https://github.com/Saichiiro2133) |

## Roadmap

- [ ] **Milestone 1 (13.11.26): Roadmap** – topic, datasets with licences, research questions, plan
  - [x] Finding a topic that suits the task (see [ideas.md](https://github.com/fespiegel/DIS-3.3-Data-Integration/blob/main/ideas.md) for the ideas we considered)
  - [x] Forming a team and creating the repository
  - [x] Inviting breuert as collaborator
  - [x] Adding `AI_USAGE.md`
  - [x] Formulating research questions and definitions ("Hollywood", "box office", ...)
  - [ ] Selecting data sources and listing the licence of every source
  - [ ] Planning the pipeline (Obtain → Scrub → Explore → Model → Interpret) for Milestone 2 & 3
  - [ ] Listing risks and mitigation
  - [x] Adding `LICENSE`
  - [x] Adding `About`
  - [ ] Sending e-mail to breuert: project name, full names, student IDs and GitHub handles of all members
- [ ] **Milestone 2 (18.12.26): Dataset** – enriched dataset, pipeline prototype, documentation (presented at the World Café, +10 bonus points)
  - Fixed deliverables:
    - [ ] Pipeline prototype (skeleton code) that builds the dataset from raw data
    - [ ] Jupyter notebook in the repository
    - [ ] Documentation: sources and licences, cleaning steps, data dictionary
    - [ ] Publish dataset online (DOI)
    - [ ] Present at the World Café
  - Data-specific tasks (planned, to be adjusted after the dataset check):
    - [ ] Query Wikidata for films 2000–2025
    - [ ] Scrape review scores from Wikipedia
    - [ ] Adjust box office for inflation
- [ ] **Milestone 3 (25.01.27): Presentation (exam)** – analysis, hypothesis tests, visualisations, demo notebook
  - [ ] Data analysis, hypothesis tests and visualisations
  - [ ] Running notebook for the live demo
  - [ ] Slides
  - [ ] Project documentation in the repository
  - [ ] Final repository state before the deadline (22.01.27, 23:59 – to be confirmed)
     
## Research Questions

1. **Globalization:** Has the share of non-US films among the top-grossing films of each year
   increased between 2000 and 2025?
2. **Recognition:** Are non-US films rated differently than US films (Rotten Tomatoes, IMDb), and has
   their share among Oscar nominees and winners changed since 2000?
3. **Success and reviews:** Is box office performance related to review scores, and does this
   relationship differ between US and non-US films?

## Definitions

**Box Office** - A term used to refer to the revenue any film generates during its theatrical run in $USD. Usually the box office records are reported domestically and those numbers are then tallied up to show how much any given film grossed worldwide.

For our project, domestic box office records refer to the US market (including CA) as reported by BoxOffice Mojo.

**Ratings and Accolades** - Aggregate Rating sites like IMDB, Letterboxd or Rotten Tomatoes allow their users to give any movie they watched a rating. The average, sometimes weighted, rating a film is them calculated by taking all user ratings for any given film on a site into account to create an aggregate user score. Rotten Tomatoes also showcasess a aggregrate score for critic ratings. 

This project also takes the best picture nominees and winners at the academy awards, the OSCARS, into account when evaluating the critical reception of any given film.

## Risks and Mitigations

## Risks and Mitigations

| Risk | Mitigation |
|---|---|
| **IMDb terms:** only personal, non-commercial use; no republishing or building a film database; IMDb may withdraw permission at any time ([terms](https://help.imdb.com/article/imdb/general-information/can-i-use-imdb-data-in-my-software/G5JTRESSHJBBHTGX), checked 11.11.2026) | Todo |
| **Box office sources:** Box Office Mojo is operated by IMDb, so its [conditions](https://www.boxofficemojo.com/conditions/) refer to the [IMDb Conditions of Use](https://www.imdb.com/conditions), which do not allow scraping of the website (checked 11.11.2026) | Todo |
| **Missing budget:** especially for non-US films | We leave budget out and only use box office, because budget is missing for too many films. Using it would not give all films the same conditions. |


