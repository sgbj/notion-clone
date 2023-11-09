# Notion Clone

A fullstack Notion clone built with Next.js, React, Tailwind, Clerk, Convex, Edge Store, and BlockNote.

## Landing page

![Screenshot 1](https://github.com/sgbj/notion-clone/assets/5178445/cc2bb741-4315-42f6-83f9-d1cfca072f0a)

## Editor

![Screenshot 2](https://github.com/sgbj/notion-clone/assets/5178445/592d8c74-6d3f-4dec-be20-dd5390fdf1be)

## Features

* 🔐 Authentication using Clerk
* 📊 Real-time backend and database powered by Convex.dev
* 🖼️ Upload images using Edge Store
* 📝 Create and edit notes using BlockNote editor
* 🙂 Emojis using Emoji Picker React
* 🌲 Create hierarchies of notes
* 🗑️ Archive, restore, and delete notes
* 📢 Publish notes to share with others
* ⬅️ Adjustable sidebar
* ✨ Responsive UI and light/dark mode built with Tailwind and shadcn/ui

## Getting Started

### Clone the repo

```bash
git clone https://github.com/sgbj/notion-clone.git
```

### Install dependencies

```bash
npm install
```

### Setup .env file

```env
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Start Convex

```bash
npx convex dev
```

### Start the app

```bash
npm run dev
```

### Credit

Created by following along with [AntonioErdeljac/notion-clone-tutorial](https://github.com/AntonioErdeljac/notion-clone-tutorial).
