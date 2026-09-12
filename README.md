Vistas

Search your media by meaning, not by filename.

A multimodal semantic search workspace that lets you find images and video using plain language — built with React, TypeScript, Vite, and Bolt Database.

The problem

Ever struggled to find a specific photo in a massive library? You remember what was in the picture — "a couple laughing at an outdoor cafe" — but the file is named IMG_4821.jpg.

Vistas fixes that. Describe what you're looking for in natural language, and it returns ranked visual matches with relevance scores.

✨ What's working in this MVP
Natural-language search — type "modern architecture with curves" and get semantically ranked results
Match-score badges and tag highlights on every result
A detail modal that explains why each asset matched your query
Drag-and-drop upload that indexes new images instantly
Save searches to revisit later (persisted in Bolt Database)
Filter by media type, sort by relevance or newest
Auto-seeded curated library so it works on first launch
🛠️ How it's built
Layer	Tech
Frontend	React + TypeScript + Vite
Styling	Tailwind CSS (custom dark design system)
Database	Bolt Database (PostgreSQL + RLS)
Icons	Lucide React
