# Product Hunt launch page — Visual Study Codes

**Status:** Draft prepared; not published.  
**Product:** https://github.com/kkkkkkkaro-cyber/visual-study-codes

## Product listing

- **Name:** Visual Study Codes
- **Tagline (49/60):** 16 reusable commands for clearer AI study visuals
- **Description (under 500 characters):** Turn topics, notes and your own plans into structured visuals with 16 reusable slash commands. Make sketchnotes, roadmaps, flowcharts, timelines, decision matrices and planners in Claude or Codex. Bilingual English/Chinese instructions. ChatGPT users can follow the prompt-based setup guide.
- **Website:** https://github.com/kkkkkkkaro-cyber/visual-study-codes
- **Pricing:** Free / open source (MIT). No paid tier is being claimed.
- **Suggested tags:** Productivity; Education; Artificial Intelligence
- **Launch type:** Maker launch (the repository owner must select the maker role and connect their own Product Hunt account).

## Gallery order

1. `assets/01-sketchnotes.svg` — real example output, retrieval-practice sketchnotes.
2. `assets/02-flowchart.svg` — a decision flow for choosing the next study action.
3. `assets/03-decision-matrix.svg` — compare study techniques by use case.
4. `assets/logo.svg` — square logo.

Product Hunt's current help page recommends a 240×240 logo and a 1270×760 gallery image. The logo and gallery media must be uploaded in a supported raster format in the Product Hunt editor; these SVG masters should be exported to PNG before upload. Include at least one gallery image; three or more is preferable. See [Product Hunt's product-page guide](https://help.producthunt.com/en/articles/17834537-4-build-your-product-page).

## Maker's first comment (draft)

Hey Product Hunt 👋

I built Visual Study Codes because I kept seeing the same problem: asking an AI assistant to explain something visually often means writing a long prompt again and again, and the output format changes every time.

This project turns that into a small, reusable command system. Type a code such as `/sketchnotes`, `/flowchart`, `/roadmap`, or `/decision-matrix`, then add a topic or your own notes. There are 16 formats in total, with English and Chinese instructions.

It currently works as a Skill in Claude and Codex. ChatGPT has a documented prompt-based adaptation (it is not a native one-click Skill install).

It's free and MIT-licensed. I'd especially value feedback on three things:
1. Which visual format would you actually use more than once?
2. Is the setup clear enough for someone who has never installed an Agent Skill?
3. Where does a normal AI response already do this well enough, making a separate command system unnecessary?

Honest criticism is welcome. Thanks for taking a look.

## Product Hunt FAQ

**Is it free?**  
Yes. The repository is MIT-licensed and the current project is free.

**Which assistants are supported?**  
Claude and OpenAI Codex use the Skill instructions. ChatGPT users need to copy the prompt-based instructions from `CHATGPT.md`; ChatGPT does not automatically load `SKILL.md` from GitHub.

**Does it generate images?**  
The skill asks the assistant to create structured visual outputs, preferably with the visual tools available in that environment or as a self-contained HTML file. The exact rendering depends on the assistant and tools available.

**Does it make up tasks in planners?**  
No. The planner instructions say to use only the user's supplied tasks, dates and habits, leaving missing information blank.

## Pre-launch checks

- [ ] Export SVG masters to PNG at the required dimensions and inspect at mobile size.
- [ ] Confirm the maker's Product Hunt account and profile are ready.
- [ ] Confirm all three demo outputs render correctly in the repository.
- [ ] Test the installation from a clean Claude/Codex environment.
- [ ] Decide the launch date only after the above checks.
- [ ] Owner publishes and remains available to answer comments.

## Claims we must not make

- Do not say ChatGPT natively installs the GitHub Skill.
- Do not claim users, downloads, retention, ratings or revenue without evidence.
- Do not claim the tool is scientifically validated; the research references support example content, not product efficacy.
- Do not ask for upvotes or incentives in exchange for votes.
