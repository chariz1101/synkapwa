# 🛡️ SynKapwa

**"Synchronizing with your fellow, one quest at a time."**

**SynKapwa** is a gamified group project management platform built for students who are tired of the "lone wolf" dynamic in group work. By combining the Filipino philosophy of *Kapwa* (shared identity) with RPG mechanics and AI-driven task orchestration, SynKapwa transforms academic labor into a collaborative campaign.

---

## ✨ Key Features

### 🤖 The "Quest Master" (AI Integration)

Stop wasting time breaking down syllabi. Paste your project requirements, and our AI service (powered by LLMs) will:

* Parse deliverables into actionable "Quests."
* Assign difficulty tiers (Common, Rare, Epic).
* Suggest XP rewards based on task complexity.
* **Tech:** *OpenAI API, Zod validation, Prisma ORM.*

### 🎭 Evolving Avatars & XP

Every user starts as a "Novice" with a basic icon. As you complete tasks and gain XP, your avatar evolves visually.

* **XP Formula:** 
* **Visuals:** Dynamic SVG states driven by **Redux Toolkit** and **Framer Motion**.

### ⚔️ The Raid Room

Meetings shouldn't feel like a chore. Enter a "Raid" session where a synchronized timer tracks group collaboration. Staying active in the room grants a "Synergy Multiplier" to all participants’ XP.

### 🍻 The Tavern (Mini-Games)

When the "Burnout Meter" gets high, head to the Tavern. Play embedded React-based mini-games (like a stacking game) to unlock group-wide cosmetic rewards and take a mental break together.

---

## 🛠️ Tech Stack

### Frontend

* **Framework:** Next.js 15 (App Router)
* **State Management:** Redux Toolkit (RTK) for real-time XP and UI states.
* **Styling:** Tailwind CSS + Shadcn/ui.
* **Animations:** Framer Motion for that "game-like" feel.

### Backend & Safety

* **Database:** PostgreSQL (via Supabase/Neon).
* **ORM:** Prisma (Type-safe database queries).
* **Validation:** Zod (Strict schema validation for AI outputs and API requests).
* **Authentication:** NextAuth.js.

---

## 🚀 Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/chariz1101/SynKapwa.git

```


2. **Install dependencies:**
```bash
npm install

```


3. **Setup Environment Variables:**
Create a `.env` file and add your `DATABASE_URL`, `NEXTAUTH_SECRET`, and `OPENAI_API_KEY`.
4. **Initialize Prisma:**
```bash
npx prisma generate
npx prisma db push

```


5. **Run the development server:**
```bash
npm run dev

```



---

## 📈 Project Roadmap

* [ ] **Phase 1:** Core CRUD for Quests and Prisma Schema setup.
* [ ] **Phase 2:** Redux integration for real-time XP tracking and Level-up triggers.
* [ ] **Phase 3:** AI "Quest Master" implementation for syllabus parsing.
* [ ] **Phase 4:** Tavern mini-games and Framer Motion avatar evolutions.

---

## 🤝 Contribution

SynKapwa is built on the spirit of fellowship. If you have ideas for new RPG mechanics or mini-games, feel free to open an issue or a PR!

**Developed with 💙 by [Chariz**](https://www.google.com/search?q=https://github.com/chariz1101)**

*Computer Science Student (AI Major)*

---

### Why this project exists:

> "I wanted to make collaborating easier and more fun."
