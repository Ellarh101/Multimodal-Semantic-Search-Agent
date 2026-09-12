# 🔭 Vistas

**Search your media by meaning, not by filename.**

Vistas is a multimodal semantic search workspace that lets you find images and videos using natural-language queries. Instead of searching by filenames, users can describe what they remember seeing and receive semantically ranked visual matches.

## ✨ Features

* 🔎 **Natural-language search** — Search for media using descriptions such as *"a couple laughing at an outdoor cafe"*.
* 🏷️ **Match scores** — View relevance scores and highlighted tags for each result.
* 💬 **Match explanations** — See why a particular asset matched your search query.
* 📤 **Drag-and-drop upload** — Upload new images and index them for search.
* 💾 **Saved searches** — Save searches and revisit them later.
* 🗂️ **Filtering and sorting** — Filter by media type and sort by relevance or newest.
* 🌱 **Seeded media library** — Explore a curated library immediately after launching the application.

## 🧩 Problem

Finding a specific image or video in a large media library can be difficult when filenames provide little useful information.

For example, you may remember:

> "A couple laughing at an outdoor cafe."

But the actual file might be named:

```text
IMG_4821.jpg
```

Traditional filename and keyword-based search cannot reliably connect these two pieces of information.

Vistas addresses this problem by allowing users to search for media based on **visual meaning** rather than filenames.

## 💡 How It Works

Vistas uses semantic search to match natural-language queries with visual content.

```text
User Query
    ↓
Query Processing
    ↓
Semantic Representation
    ↓
Similarity Search
    ↓
Ranked Visual Results
    ↓
Match Explanation
```

This allows users to search using concepts, objects, scenes, and descriptions instead of exact filenames or manually created tags.

## 🛠️ Tech Stack

| Layer           | Technology               |
| --------------- | ------------------------ |
| Frontend        | React                    |
| Language        | TypeScript               |
| Build Tool      | Vite                     |
| Styling         | Tailwind CSS             |
| Database        | Bolt Database            |
| Database Engine | PostgreSQL               |
| Security        | Row-Level Security (RLS) |
| Icons           | Lucide React             |

## 🚀 Getting Started

### Prerequisites

* Node.js
* npm

### Installation

Clone the repository:

```bash
git clone https://github.com/your-username/vistas.git
```

Navigate to the project directory:

```bash
cd vistas
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local development URL provided by Vite in your browser.

## 📁 Project Structure

```text
vistas/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── lib/
│   ├── types/
│   └── main.tsx
├── public/
├── package.json
├── vite.config.ts
├── tailwind.config.js
└── README.md
```

## 🖼️ Example Search

A user can search:

```text
modern architecture with curves
```

Instead of returning files based on their names, Vistas returns visual assets that are semantically related to the query and ranks them by relevance.

## 🔮 Future Improvements

* 🎥 Improved video semantic search
* 🖼️ Image-to-image similarity search
* 🧠 Multimodal AI-powered asset descriptions
* 🔤 OCR-based image search
* 🔊 Audio and video transcript search
* 🔀 Hybrid keyword and semantic search
* 📊 Advanced result reranking
* 🤖 Agentic multimodal search
* ☁️ Scalable cloud media storage
* ⚡ Background indexing for large media libraries

## 📌 Project Status

**Active Development**

Vistas is currently being developed as a multimodal semantic search workspace, with additional AI-powered search capabilities planned for future releases.

## 📄 License

This project is available under the terms of the license included in this repository.
