# Gies Sustainability Dashboard

A Pillar 3 entry for the **2025 Sustainability Expertise Case Competition**, sponsored by the **Center for Professional Responsibility in Business and Society (CPRBS)**. Our four-person team redesigned the user experience and visualizations of the Gies Sustainability Dashboard and built an interactive Figma Make prototype.

> **All dashboard data is simulated.** Metrics, publication records, faculty profiles, institutional comparisons, funding figures, success stories, and simulator outputs provide illustrative content for the interactive design.

[Explore the interactive prototype](https://www.figma.com/make/eoPnS9HrlcHqPfPAOvxH1E/Dashboard-Design-for-Metrics--final%EF%BC%89?code-node-id=1-5&p=f&t=R2nXAasMngESzVNB-0&fullscreen=1) · [Design case study](docs/case-study.md) · [My contribution](docs/my-contribution.md) · [Team report](reports/Group5_report.pdf) · [Presentation](reports/Group5_ppt.pdf)

![Dashboard homepage with an overview of simulated research indicators.](images/dashboard-home.png)

*Prototype homepage. All displayed values are simulated.*

## My role

**Ringing Song — Project Lead & Lead UX/Prototype Designer**

- Led the project's overall concept development and coordinated the four-person team.
- Conceived most of the journeys for leaders, students, and donors, connecting their goals to dashboard actions and relevant information.
- Built and iterated on most of the interactive website prototype using Figma Make and AI-assisted prototyping.
- Authored the Overview and Blueprint sections of both the team report and presentation.

The dashboard, report, and presentation are shared team deliverables. Team members: **Linyao Gao, Ringing Song, You (Mia) Wu, and Samyak Pokharna**.

## The design challenge

The selected track, **Pillar 3: The User Experience (Dashboard & Visualization Design)**, focuses on the landing page, advanced visualizations, and persona-specific navigation, search, filters, and drill-downs.

The team's evaluation identified a gap between the information presented in the original dashboard and the tasks different users wanted to complete. High-level research counts offered limited guidance for strategic comparison, publication discovery, faculty exploration, and donor scenarios.

The redesign asks: **How can a sustainability dashboard help different audiences move from an overview to information relevant to their next decision?**

## Three audiences, three journeys

| Audience | Goal | Designed journey |
| --- | --- | --- |
| University leaders | Understand research strengths and explore resource priorities | Overview → peer benchmarking → faculty and department performance → illustrative impact stories → scenario simulation → prioritization |
| Prospective students | Find a faculty mentor in sustainable finance | Overview → finance-related article search and filters → faculty discovery → individual profile exploration |
| Donors | Explore support for renewable-energy research | SDG 7 / clean-energy exploration → impact simulation → illustrative success stories → geographic and university comparison |

The team designed journeys for all three audiences, connecting each user's goal to relevant dashboard pages, search controls, filters, and detail views. The student and donor examples focus on sustainable-finance mentorship and renewable-energy research funding.

## Seven core modules

| Module | Design purpose |
| --- | --- |
| Guide | Provide entry points for the three persona journeys |
| Home | Summarize the research landscape with a clear KPI hierarchy and onward navigation |
| SDG Research Landscape | Explore coverage, distribution, theme roles, maturity, momentum, and growth |
| Research Impact | Examine journal trends, publication structure, departments, and peer comparisons |
| SDG Articles Explorer | Search and filter illustrative publication records |
| Faculty Impact | Explore illustrative faculty profiles, interests, and research connections |
| Donor Impact | Explore illustrative cases, universities, geography, and funding scenarios |

The prototype also includes supporting **Data & Methodology** and **About** pages.

![Seven-module dashboard information architecture from the team presentation.](images/information-architecture.png)

*Information architecture from the team's original presentation: blue indicates new or redesigned sections; orange indicates retained or partially retained sections.*

## Selected design decisions

- **Put orientation first.** Separate a concise homepage from deeper analytical views, with a Guide that maps user goals to relevant sections.
- **Give charts a task.** Organize SDG exploration from coverage and distribution through strategic positioning, momentum, and detailed breakdowns.
- **Connect overview and detail.** Provide publication search and faculty profiles so students can move beyond aggregate charts.
- **Make scenarios interactive.** Let donors adjust hypothetical inputs and inspect illustrative outputs. All figures and model assumptions are simulated.

Read the [case study](docs/case-study.md) for the design reasoning, user journeys, and visualization gallery.

## Interface gallery

### SDG research landscape

![Existing SDG theme positioning chart showing theme roles, two axes, bubble sizes, and a color legend.](images/sdg-theme-positioning.png)

*The original dashboard's theme-positioning view compares primary focus and supporting-theme intensity, with bubble size representing the tertiary role. All data is simulated. See the [visualization gallery](docs/case-study.md#visualization-gallery) for the existing network graph, state heatmap, and state-by-SDG matrix.*

### Article discovery

![Article explorer with SDG, department, year, and keyword controls and illustrative publication cards.](images/sdg-articles-explorer.png)

*Publication titles, authors, journal associations, and counts are simulated demo content.*

### Donor scenario exploration

![Impact simulator with hypothetical funding inputs and illustrative research and impact outputs.](images/donor-impact-simulator.png)

*The simulator demonstrates adjustable funding and timeframe inputs with illustrative outputs. All figures, matching-fund examples, and tax examples are simulated.*

## Project materials

```text
gies-sustainability-dashboard/
├── README.md
├── docs/
│   ├── case-study.md
│   └── my-contribution.md
├── images/
│   ├── dashboard-home.png
│   ├── sdg-research-landscape.png
│   ├── sdg-theme-positioning.png
│   ├── sdg-articles-explorer.png
│   ├── donor-impact-simulator.png
│   ├── faculty-network.png
│   ├── state-research-heatmap.png
│   ├── state-sdg-matrix.png
│   ├── information-architecture.png
│   ├── persona-module-blueprint.png
│   └── README.md
└── reports/
    ├── Group5_report.pdf
    ├── Group5_ppt.pdf
    └── README.md
```

The interactive prototype is hosted in the linked Figma Make project. This repository presents the design case study, user journeys, screenshots, personal contribution, and team deliverables.

## Prototype data

All dashboard content uses simulated data to demonstrate the designed interactions, visualizations, and funding scenarios. Institutional names provide the project context, and displayed metrics and outcomes are illustrative.

The [team report and presentation](reports/README.md) document the dashboard structure, user journeys, and design decisions.
