---
title: Using AI to Assess Community Response to Climate Hazards
public_mode_toggle: true
---

# Using AI to Assess Community Response to Climate Hazards

![climate hazards figure](docs/assets/images/logos/climate_hazards.png)

---

## Day 1

### People

| Name | Affiliation | Contact | Github |
|---|---|---|---|
| Bridger | NSF ASCEND Engine | bridger@innosphere.org | @Innosphere-Bridger |
| Lauren Palermo | CU Boulder / USGS | lapa5054@colorado.edu | @palermolauren |
| Lise St. Denis | CU Boulder / CIRES Earth Lab | lise.st.denis@colorado.edu | @lisestdenis |
| Juan P. Maestre | University of Texas at Austin | juanpedro.maestre@utexas.edu | @drMaestre |
| Luca A Palasti | CU Boulder | luca.palasti@colorado.edu | @lucap1211 |

### Project Goal

Understand how AI-assisted analysis of social media can characterize community and emergency management responses to wildfire events, and whether formal and informal crisis narratives converge or diverge across Twitter.

Central question: How do official and public perceptions of a fire align, and what does convergence or divergence in Twitter narratives tell us about the information ecosystem during a wildfire?

### Brainstorming and Possibilities

- Thematic and sentiment analysis of Twitter data from the Chetco Bar (2017) and Klondike (2018) fires in Oregon
- Compare LLM-generated themes and sentiment against human-coded data from the same corpus
- Explore patterns of convergence and divergence between community members and emergency management personnel
- Extend validated pipeline to a new fire event as a downstream test
- Integrate structured incident data (ICS-209) to compare official fire narrative with public social media narrative
- Consider community characteristics (Social Vulnerability Index, WUI) as contextual variables
- Study area candidates for extension: Turner Gulch, Marshall, and Lower North Fork fires in Colorado

Promising prompting directions:

- Brainstorm things that do not work, studies that aren't mainstream
- Frame the charge question carefully before coding
- Probe "how do we define success in this realm?"

### Team Norms

- You can always pass
- Create a space where everyone feels comfortable contributing
- There are no dumb questions
- "Yes and" language
- Self-organize around what everyone is interested in
- Be explicit with requests
- Be clear about brainstorming versus action
- Use summaries to refine into action steps

**Decision making:** Silent voting for prioritization, everyone has the same number of votes. Clarify intensity of opinion before decisions.

---

## Day 2

### Norms Around AI Use

General comfort with AI-assisted generation, with explicit boundaries:

- **Documentation:** AI outputs must be documented and traceable
- **Domain expertise:** AI suggestions are subject to expert review before acceptance
- **Validation:** Results require validation beyond visual inspection

### Divergent Thinking: Ideas We Explored

- How would one operationalize convergence and divergence between user groups? What are the strengths and blind spots of different approaches?
- Computer-generated theming versus human theming: where do they agree and where do they part ways?
- What does it mean for a pipeline to be "lightly" versus "highly" engineered in terms of prompts, and how much does that matter for outputs?
- Can LLM-coded themes trained on one fire generalize to a different fire in a different geographic and policy context?
- Comparative sentiment by user group: do community members and emergency managers express the same events in emotionally different ways?

### Plan and Subgroups 📣 { #plan .oasis-report-out-section .oasis-report-out-day2 }

**Overall goal:** Produce a reproducible AI-assisted pipeline that codes themes and sentiment from wildfire Twitter data, validates it against human-coded data, and demonstrates its application across multiple fire events and user groups.

| Subgroup | Members | Aim |
|---|---|---|
| Theme prompt engineering | JP, Travis, Lauren, M | Develop and refine LLM prompts for thematic coding; compare lightly vs. highly engineered outputs against human-coded themes |
| Sentiment prompt engineering | Bridger, Branda | Develop and refine LLM prompts for sentiment classification; compare outputs by user group (community vs. EM) |

**Step-by-step plan:**

1. Run thematic and sentiment analysis on Chetco Bar and Klondike data using LLM (lightly engineered prompts)
2. Compare LLM outputs using the same data with highly engineered prompts
3. Compare both LLM outputs against human-coded themes and sentiment as ground truth
4. Apply the validated pipeline to a new fire (downstream test)
5. Analyze differences between user subgroups and characterize patterns of convergence and divergence

**Data sources in scope:** Scraped Twitter data (Chetco Bar, Klondike), ICS-209 incident reports, Social Vulnerability Index, WUI data.

### Analysis Started

- Inductive thematic analysis completed on combined community (n = 1,279) and emergency management (n = 1,529) tweet corpora
- Seven themes identified: Fire Progression, Evacuation, Smoke/Air Quality, Operational Coordination, Community Solidarity, Geospatial Mapping, and Public Accountability
- Initial comparison of AI-assigned themes against human-coded emerging themes underway (community data only, n = 388 hand-coded tweets)
- R script for human vs. AI theme cross-tabulation drafted and available for review

---

## Day 3

### Findings at a Glance 📣 { #findings .oasis-report-out-section .oasis-report-out-day3 }

Headline 1 —
...

Headline 2 —
...

Headline 3 —
...

### Visuals That Tell a Story 📣 { #visuals .oasis-report-out-section .oasis-report-out-day3 }

![Main result](assets/figures/main_result.png)

*Visual 1: ...*

### What's Next? 📣 { #whats-next .oasis-report-out-section .oasis-report-out-day3 }

Short term:
- ...

Long term:
- ...

Who should see this:
- ...

---

## Cite & Reuse { #cite-reuse }

St. Denis, L., Maestre, J.P., Palermo, L., & Bridger. (2026). *Using AI to Assess Community Response to Climate Hazards — ESIIL Innovation Summit 2026*. https://github.com/CU-ESIIL/Project_group_OASIS

License: CC-BY-4.0 unless noted.
