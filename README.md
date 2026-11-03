![PitchLab wordmark](assets/logo.svg)

# PitchLab — Find the player. See the fit.

**Mathematical scouting, tailored to your game.**

Football Manager gives you thousands of players and plenty of ratings. Finding the right fit still means deciding which qualities matter to *your* team.

PitchLab turns those priorities into a personalized player ranking. Define who qualifies, choose what matters most, and see why each player fits your recruitment brief.

**Created by Guy Luzon**

> **WORK IN PROGRESS · CLOSED BETA** — PitchLab is still being tested. No public download or release is available yet.

## Join the closed beta waitlist

PitchLab is preparing a **free, invitation-only closed beta**. The beta is **not publicly available yet**; access will be offered by invitation.

**[Join the free closed beta waitlist](https://docs.google.com/forms/d/e/1FAIpQLSfLi4yWDYLnSig5TSiR0Mjir2EllGWryFnjp4EgvKJ1OkrKwg/viewform)**



## 1. Start with your save

Begin with a read-only compatibility check, then build your scouting brief. Selecting a file does not automatically run a search.

![PitchLab home screen with the save uploader and three-step scouting workflow](screenshots/01-home.png)

## 2. Define your kind of player

Use positions, age limits and minimum attribute requirements as **hard filters**. Then distribute **100 importance points** across the attributes that matter to you. Those weights influence the ranking, while the eligibility requirements remain separate. Balance current ability against potential to reflect the player you need now and the development you value.

![Scouting configuration showing weighted attribute priorities and importance controls](screenshots/02-configuration.png)

## 3. Find the fit

Explore a sortable shortlist with prominent match scores and player details. Each score is calculated using a **deterministic mathematical scoring formula developed for PitchLab**, shaped by your selected attributes and preferences. Scores are shown on an absolute **0–100 heuristic scale**. They are **not probabilities of success** or percentiles within the player pool.

Choose **Quality Only** for no price deduction, or use **Price Range** to apply a transparent, gradual deduction. Within your chosen reference range, cheaper players receive a modest advantage; above the maximum, the deduction grows logarithmically. An adjustable in-range sensitivity controls how strongly price matters. Price is a **soft ranking factor, not a maximum-price exclusion filter** (Price Range still requires a known transfer value). Players are ranked by their *unclipped* score so their ordering remains meaningful even when a displayed score reaches zero.

![Scouting shortlist with fictional players ranked by their absolute match scores](screenshots/03-shortlist.png)

## 4. Understand the score

Open a player profile to inspect strengths, concerns, selected attributes, football quality and any price deduction. The explanation connects the result to your own priorities, so you can understand the ranking and make your own decision.

![Explainable player profile showing strengths, concerns and the match-score breakdown](screenshots/04-player-profile.png)

## Current scope

**Planned initial closed-beta environment:** Windows 11 (64-bit), at least 8 GB RAM (16 GB recommended), and a locally available FM27 `.fm` save. Saves over 100 MB remain outside the measured performance envelope. Football Manager itself does not need to be installed on the same PC to read a supplied save file.

PitchLab is in active development. Current scouting focuses on **outfield players**; dedicated goalkeeper scouting is planned. FM27 integration remains **experimental**, and compatibility checks do not independently validate every field's meaning. Full-data evaluation can reveal information normally hidden during gameplay.

Experimental price-aware evaluation treats unchanged extracted values as EUR; internal save-value units have not been independently verified. No currency conversion is applied.

All screenshots show the actual application using **fictional demonstration players and clubs**. They contain no private save data and illustrate the local development experience, not a hosted public service.

This repository is a **public product showcase**. Application source code, datasets and private saves are not distributed here.

## Unofficial project

PitchLab is an independent, unofficial project. It is not affiliated with, endorsed by or sponsored by Sports Interactive or SEGA. Football Manager, Sports Interactive and SEGA names and marks remain the property of their respective owners.
