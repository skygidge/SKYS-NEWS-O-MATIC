# The Prompt Response // ICS

Industry news feed for Insta360 ICS creative studio. Auto-sourced. Human-curated.

**Website:** https://skygidge.github.io/prompt-response-ics/

## Categories

| Filter | Full Name | What goes here |
|--------|-----------|---------------|
| Trends | Emerging Visual Trends | Shooting styles, spatial video, 360/VR trends, platform format shifts |
| Campaigns | Interesting Campaigns | Brand campaigns worth studying, UGC strategies, influencer activations |
| Production | Production Techniques | Workflow innovations, gear techniques, editing approaches |
| Creators | Creator Content Worth Studying | Specific creators doing something new, YouTube trends |

## Company Watch
DJI, GoPro, Apple, Nothing

## How it works
1. Claude Code Routine searches web sources daily
2. Stories evaluated against editorial gates (relevance, angle, shareability)
3. Qualifying stories written as bilingual blurbs (EN/ZH) with double-meaning headlines
4. Pushed to GitHub Pages as a filterable, searchable feed

## Story fields
Each story includes: headline (EN + ZH), blurb (EN + ZH), category, editorial score (1-10), source URL, article date, verification notes, and tags.

## Files
- `docs/index.html` — website SPA
- `docs/all_stories.json` — story data (copy for GitHub Pages)
- `data/results/all_stories.json` — story data (primary)
- `data/focus.md` — editorial steering
- `data/style-guide.md` — writing rules
- `data/sources.json` — web sources config
- `data/learnings.json` — search intelligence (evolves over time)
