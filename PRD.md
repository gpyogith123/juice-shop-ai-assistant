# 🧃 **The Conversational Commerce Revolution**
## *From Browsing to Chatting — Build an AI Shopping Assistant*

> **Audience:** Complete beginners — no coding experience needed!
> **Format:** Interactive presentation + Live demos
> **Duration:** ~6-8 hours (flexible)
> **Theme:** 🎨 Visual-first, beginner-friendly, no jargon

---

<!-- ============================================================ -->
<!-- TITLE SLIDE -->
<!-- ============================================================ -->

# 👋 WELCOME!

### *"You're about to build something AMAZING — an AI that helps people shop just by chatting!"*

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║     🧃  JUICE SHOP AI ASSISTANT                              ║
║     ─────────────────────────────                             ║
║                                                              ║
║     Today's Journey:                                          ║
║                                                              ║
║     GitHub → Codespaces → E-Commerce Site                    ║
║         → Pain Points → AI Chatbot → RAG                     ║
║             → The Future of Shopping                         ║
║                                                              ║
║     🎯 No experience needed!                                  ║
║     🎯 We learn by DOING                                     ║
║     🎯 You'll BUILD something real!                          ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 🗺️ **The Big Picture — What We're Building Today**

```
                    ┌─────────────────────┐
                    │   TODAY'S MISSION   │
                    └─────────────────────┘
                               │
           ┌───────────────────┼───────────────────┐
           ▼                   ▼                   ▼
┌──────────────────┐  ┌──────────────────┐  ┌──────────────────┐
│   PART 1         │  │   PART 2         │  │   PART 3         │
│   🏗️ SETUP      │  │   🛒 EXPLORE     │  │   🤖 BUILD       │
├──────────────────┤  ├──────────────────┤  ├──────────────────┤
│ • GitHub Account │  │ • Juice Shop     │  │ • AI Assistant   │
│ • Codespaces     │  │ • Browse & Order │  │ • Chat Interface │
│ • Tools Install  │  │ • See Pain Points│  │ • RAG Knowledge  │
│   (Node, Docker) │  │ • Navigate Pages │  │ • Demo Time!     │
└──────────────────┘  └──────────────────┘  └──────────────────┘
```

---

## 💡 **The BIG Idea — Why Are We Here?**

### 🏬 **E-Commerce TODAY:**

```
You open a shopping website:
    │
    ├──→ 🏠 Landing Page
    │         ├──→ 📂 Categories
    │         │         ├──→ 🥤 Juices
    │         │         │         ├──→ 🍎 Apple Juice
    │         │         │         ├──→ 🍊 Orange Juice
    │         │         │         └──→ 🥭 Eggfruit Juice
    │         │         └──→ 👕 Merchandise
    │         │                   ├──→ 👚 T-Shirts
    │         │                   └──→ 🧢 Hats
    │         ├──→ 🛒 Cart
    │         │         └──→ 💳 Checkout
    │         │                   └──→ 📦 Shipping
    │         └──→ 🔍 Search
    │
    └──> Total: 7-10+ CLICKS to order! 😫
```

### 💬 **E-Commerce with AI TOMORROW:**

```
You open a chat window:
    │
    ├──→ 💬 "Hi! What juices do you sell?"
    │         └──→ 🤖 "We have Apple ($1.99),
    │                   Orange ($2.49), and more!"
    │
    ├──→ 💬 "I want something cheap and fruity"
    │         └──→ 🤖 "Try Eggfruit Juice at $1.99!"
    │
    └──→ 💬 "Great, I'll take it!"
              └──→ 🤖 "Added to cart! Any more?"
    
    Total: Just 3 MESSAGES to order! 🚀
```

---

## 🎯 **Course Roadmap**

```
LEGEND:    🔧 Setup     🛒 Explore     🤖 Build     🎉 Celebrate

LESSON 1:  🔧 GitHub Account → Your Digital Identity
LESSON 2:  🔧 Project Requirements → What Are We Building?
LESSON 3:  🔧 Codespaces → Your Cloud Computer (4vCPU, 16GB!)
LESSON 4:  🛒 Launch Juice Shop → See a Real E-Commerce Site
LESSON 5:  🛒 Experience Pain Points → Why Navigation Sucks
LESSON 6:  🤖 Meet the AI → Building the Chatbot Brain
LESSON 7:  🤖 RAG Knowledge → Smart Product Search
LESSON 8:  🤖 Connect Everything → AI + E-Commerce
LESSON 9:  🎉 Final Demo & The Future → Conversational Commerce
```

---

### 📚 **GitHub Education — Free Tools for Students!**

GitHub offers **FREE** resources for students through [GitHub Education](https://education.github.com/):

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│  🎓 GITHUB EDUCATION — FREE FOR STUDENTS!                       │
│                                                                  │
│  ✅ GitHub Codespaces — 180 hours/month (normally 60!)          │
│  ✅ GitHub Copilot — AI code completion (FREE for students!)    │
│  ✅ GitHub Student Developer Pack — $200k+ in free tools        │
│                                                                  │
│  📍 Apply at: https://education.github.com/pack                  │
│     (Use your .edu email or student ID)                         │
│                                                                  │
│  💡 With GitHub Education you get:                               │
│  • FREE access to professional developer tools                   │
│  • Real-world skills for your resume                             │
│  • Everything we need for THIS course — for FREE!                │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 1: GitHub Account -->
<!-- ============================================================ -->

# 🔧 **LESSON 1: GitHub — Your Digital Identity**

### *"Every developer needs a home for their code"*

---

## 🧑‍💻 **What is GitHub?**

```
GitHub = Social Media for Code 🚀
────────────────────────────────────

┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  LinkedIn   │     │  Instagram  │     │   GitHub    │
│  = Your job │     │  = Your     │     │  = Your     │
│  profile    │     │  photos     │     │  code       │
└─────────────┘     └─────────────┘     └─────────────┘
                                              │
                    ┌─────────────────────────┴──────────────┐
                    │  Think of it as:                        │
                    │  • Google Docs for code ✍️              │
                    │  • Time machine for your files ⏰       │
                    │  • Portfolio to show employers 💼       │
                    └────────────────────────────────────────┘
```

---

## 📝 **Step 1: Create Your GitHub Account**

```
┌───────────────────────────────────────────────────────────┐
│                    SIGN UP FLOW                            │
├───────────────────────────────────────────────────────────┤
│                                                           │
│  ① Go to → https://github.com                            │
│                                                           │
│  ② Click → "Sign up" button                              │
│                                                           │
│  ③ Enter → • Your email                                  │
│             • A password (use a strong one!)              │
│             • A username (pick something professional)    │
│                                                           │
│  ④ Verify → Check your email for the code                │
│                                                           │
│  ⑤ Choose → Free plan (it's FREE forever!)               │
│                                                           │
│  🎉 Done! You're a developer now!                         │
│                                                           │
└───────────────────────────────────────────────────────────┘
```

> **💡 Pro Tip:** Your GitHub username will appear on your code forever. Choose wisely! Something like `yourname-dev` or `yourname-code` works great.

---

## 🏠 **GitHub Dashboard — Your New Home**

After signing up, you'll see your dashboard:

```
┌─────────────────────────────────────────────────────────────────┐
│  🔍 [Search GitHub]                     [🔔] [📷] [+] ↓        │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌─────────────────────────────────────────┐                    │
│  │ 📊 Your Dashboard                        │                    │
│  │                                          │                    │
│  │ Top Repositories:                        │                    │
│  │   (empty — you'll create one next!)     │                    │
│  │                                          │                    │
│  │ Activity:                                │                    │
│  │   🎉 Welcome to GitHub!                  │                    │
│  │                                          │                    │
│  │ 📌 Your Learning Path:                   │                    │
│  │   1. Create a repository  ← YOU ARE HERE │                    │
│  │   2. Add your code                       │                    │
│  │   3. Make your first commit              │                    │
│  │                                          │                    │
│  └─────────────────────────────────────────┘                    │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🎮 **Activity: Create Your First Repository**

A **repository** (or "repo") = a project folder on GitHub

```
┌───────────────────────────────────────────────────────────┐
│           HOW TO CREATE A REPOSITORY                       │
├───────────────────────────────────────────────────────────┤
│                                                           │
│  📍 Click the [+] button → "New repository"              │
│                                                           │
│  ✏️ Fill in:                                              │
│     • Repository name: juice-shop-ai-assistant            │
│     • Description: My first AI project! 🚀               │
│     • Public (so everyone can see your amazing work)      │
│     • ✅ Add a README file                                │
│                                                           │
│  🖱️ Click "Create repository"                             │
│                                                           │
│  🎉 YOU DID IT! Your first repo exists!                   │
│                                                           │
└───────────────────────────────────────────────────────────┘
```

---

## 📋 **What's in a Repository?**

```
┌─────────────────────────────────────────────────────────────────┐
│  📁 juice-shop-ai-assistant  (Public)            [⭐] [🍴] [🔗]│
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌─ 📄 README.md  ← The welcome page for your project          │
│  │   "This is where I'll build my AI assistant!"               │
│  │                                                              │
│  └─ ✏️ [Edit] — Click to add a description!                    │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │  📁 Files (empty for now — we'll add code later!)        │    │
│  │                                                          │    │
│  │  💡 A repo is like a project folder on the cloud!       │    │
│  │  📂 It holds all your code files                         │    │
│  │  📸 It takes snapshots (commits) of your changes         │    │
│  │  👥 It lets you collaborate with others                  │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📝 **Lesson 1 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ CHECKLIST                      │
│                                            │
│  [ ] GitHub account created               │
│  [ ] GitHub Education signed up (optional)│
│  [ ] First repository created             │
│  [ ] README file added (auto)             │
│  [ ] Repository set to Public             │
│                                            │
│  🎯 WHAT YOU LEARNED:                      │
│  • GitHub = code hosting + collaboration  │
│  • Repo = project folder on the cloud     │
│  • README = welcome page for your project │
│                                            │
│  📸 Screenshot your repo page!             │
└────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 2: Project Requirements (PRD) -->
<!-- ============================================================ -->

# 📋 **LESSON 2: Project Requirements — What Are We Building?**

### *"Before we code, let's PLAN!"*

---

## 📄 **What is a PRD?**

### PRD = Product Requirements Document

```
Think of it like a RECIPE before cooking:
────────────────────────────────────────────


┌─────────────────────────────────────┐
│      🍰 CAKE RECIPE (PRD)           │
├─────────────────────────────────────┤
│                                     │
│  WHAT:   Chocolate cake             │
│  WHY:    Friend's birthday          │
│  WHO:    10 people                  │
│  HOW:    Mix → Bake → Frost        │
│  INGREDIENTS:                       │
│    • Flour (2 cups)                 │
│    • Eggs (3)                       │
│    • Chocolate (200g)               │
│    • Sugar (1 cup)                  │
│                                     │
└─────────────────────────────────────┘

  Without a recipe → 🥴 Mess!
  With a recipe   → 🎉 Perfect cake!
```

---

## 📝 **Our PRD — The AI Shopping Assistant**

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   📋 PRODUCT REQUIREMENTS DOCUMENT                           ║
║   Project: Juice Shop AI Shopping Assistant                  ║
║                                                              ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  🎯 PROBLEM:                                                 ║
║  Shopping websites require too many clicks and page          ║
║  navigations to find products and place orders.              ║
║                                                              ║
║  💡 SOLUTION:                                                ║
║  An AI chatbot that answers questions about products         ║
║  through simple conversation — no browsing needed!           ║
║                                                              ║
║  🤔 WHY AI?                                                  ║
║  Customers can ask: "What's the cheapest juice?"             ║
║  and get an answer instantly — instead of clicking           ║
║  through 5+ pages to find out.                               ║
║                                                              ║
║  🔧 TECH STACK:                                              ║
║  • GitHub Codespaces (cloud computer — 4vCPU, 16GB!)        ║
║  • Node.js (runs Juice Shop website)                        ║
║  • Python + FastAPI (our AI server)                         ║
║  • ChromaDB (AI memory database)                            ║
║  • OpenRouter API (access to AI models)                     ║
║  • Freebuff coding agents (AI coding assistant)             ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 🎯 **User Stories — What Can Our Customers Do?**

```
┌───────────────────────────────────────────────────────────────┐
│                    USER STORIES                                │
│  (Simple sentences describing what users want)                │
├───────────────────────────────────────────────────────────────┤
│                                                               │
│  👤 As a customer, I want to...                               │
│                                                               │
│  🥤 "What juices do you sell?"                                │
│     → AI lists all products with prices                       │
│                                                               │
│  💰 "What's the cheapest item?"                               │
│     → AI finds the best deal automatically                    │
│                                                               │
│  👕 "Do you sell t-shirts?"                                   │
│     → AI searches merchandise category                        │
│                                                               │
│  🍊 "I want something with Vitamin C"                         │
│     → AI understands meaning, not just keywords               │
│                                                               │
│  💬 "I'll take 2 apple juices please"                         │
│     → AI understands order intent                             │
│                                                               │
└───────────────────────────────────────────────────────────────┘
```

---

## 🏛️ **Architecture Diagram — The Big Design**

```
┌─────────────────────────────────────────────────────────────────┐
│                   SYSTEM ARCHITECTURE                            │
│                                                                  │
│   👤 USER (Browser)                                              │
│      │                                                           │
│      │ 💬 "What juices do you sell?"                            │
│      ▼                                                           │
│   ┌─────────────────────────────────────────────────────┐       │
│   │              🧃 CHAT INTERFACE (chat.html)           │       │
│   │          Beautiful chat window in the browser        │       │
│   └─────────────────────┬───────────────────────────────┘       │
│                         │ POST /chat                             │
│                         ▼                                        │
│   ┌─────────────────────────────────────────────────────┐       │
│   │              🚀 FASTAPI SERVER (main.py)             │       │
│   │          The brain that processes requests           │       │
│   └──────┬──────────────────────────────┬──────────────┘       │
│          │                              │                        │
│          ▼                              ▼                        │
│   ┌──────────────┐            ┌──────────────────┐              │
│   │  🔍 RAG      │            │  🧠 AI ASSISTANT │              │
│   │  SEARCH      │            │  (assistant.py)  │              │
│   │  (rag.py)    │            │  Talks to        │              │
│   │  Finds       │            │  OpenRouter AI   │              │
│   │  products    │            │  Models          │              │
│   └──────┬───────┘            └────────┬─────────┘              │
│          │                             │                         │
│          ▼                             ▼                         │
│   ┌──────────────┐            ┌──────────────────┐              │
│   │  📊 ChromaDB │            │  ☁️ OpenRouter   │              │
│   │  Vector DB   │            │  Cloud AI API    │              │
│   │  (Docker)    │            │  (Free tier)     │              │
│   └──────────────┘            └──────────────────┘              │
│                                                                  │
│   ┌─────────────────────────────────────────────────────┐       │
│   │  🗄️ SQLite Database  (Juice Shop product data)      │       │
│   └─────────────────────────────────────────────────────┘       │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🎮 **Activity: Create Your PRD File**

Let's create a PRD in your GitHub repository!

```
📝 FILE: PRD.md in your GitHub repo

In your GitHub repo, click "Add file" → "Create new file"
Name it: PRD.md
Paste this content:
─────────────────────────────────

# 🧃 Juice Shop AI Assistant - PRD

## Problem
Shopping online requires too many clicks.
Customers waste time navigating pages.

## Solution
An AI chatbot that answers questions through conversation.
No browsing needed — just ask!

## Features
1. List all products with prices
2. Find cheapest items
3. Understand natural language (not just keywords)
4. Have multi-turn conversations (follow-up questions)

## Tech Stack
- GitHub Codespaces (4vCPU, 16GB RAM cloud computer)
- Node.js + Python
- ChromaDB + OpenRouter API
- Freebuff AI coding agents

## Success Metrics
- 0 navigation clicks needed to get product info
- Answers in under 3 seconds
- Understands 100% of product questions
```

---

## 📝 **Lesson 2 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ CHECKLIST                      │
│                                            │
│  [ ] Understand what a PRD is             │
│  [ ] Read the project PRD                 │
│  [ ] Understand the architecture diagram  │
│  [ ] Create PRD.md in your GitHub repo    │
│                                            │
│  🎯 KEY INSIGHT:                           │
│  Planning FIRST saves hours of rework!    │
│  PRD = Recipe before cooking              │
│                                            │
└────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 3: GitHub Codespaces -->
<!-- ============================================================ -->

# ☁️ **LESSON 3: GitHub Codespaces — Your Cloud Computer**

### *"A complete development computer in your browser!"*

---

## 💻 **What is a Codespace?**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│   CODESPACE = A VIRTUAL COMPUTER IN THE CLOUD ☁️                 │
│                                                                  │
│   ┌─────────────────────────────────────────────────────────┐   │
│   │  YOUR CODESPACE SPECS:                                   │   │
│   │                                                          │   │
│   │  ⚡ CPU: 4 cores (4vCPU) — Fast processing              │   │
│   │  🧠 RAM: 16 GB — Run many apps at once                  │   │
│   │  💾 Storage: 32 GB — Plenty for your code               │   │
│   │  🌐 OS: Linux (Ubuntu) — Industry standard              │   │
│   │  🖥️ VS Code in browser — Full IDE!                      │   │
│   └─────────────────────────────────────────────────────────┘   │
│                                                                  │
│   🆚 Compare to an average student laptop:                      │
│                                                                  │
│   ┌──────────────────┬──────────────┬──────────────┐            │
│   │ Specification    │ Your Laptop  │  Codespace   │            │
│   ├──────────────────┼──────────────┼──────────────┤            │
│   │ CPU Cores        │ 2-4          │ 4 (dedicated)│  🏆       │
│   │ RAM              │ 4-8 GB       │ 16 GB        │  🏆       │
│   │ Storage Speed    │ HDD/SSD      │ SSD (cloud)  │  🏆       │
│   │ Internet Needed  │ ❌ No        │ ✅ Yes       │            │
│   │ Works on Any PC  │ ❌           │ ✅ YES!      │  🏆🏆🏆   │
│   └──────────────────┴──────────────┴──────────────┘            │
│                                                                  │
│   💡 It's like having a GAMING PC for coding!                   │
│      All running in your browser! 🎮                             │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🌍 **How Codespaces Works**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│   YOUR LAPTOP                                 CLOUD (Microsoft) │
│   ┌────────────────┐                       ┌────────────────┐   │
│   │                │                       │                │   │
│   │  🌐 Browser    │────── Internet ──────▶│  🖥️ Codespace  │   │
│   │                │                       │                │   │
│   │  VS Code in    │◀─────── Stream ───────│  • 4 CPU cores │   │
│   │  the browser   │      video back       │  • 16 GB RAM   │   │
│   │                │                       │  • Linux OS    │   │
│   │  You type ↔    │                       │  • VS Code IDE │   │
│   │  You see ↔     │                       │  • Terminal    │   │
│   └────────────────┘                       └────────────────┘   │
│                                                                  │
│   💡 YOU DON'T NEED:                                             │
│   ❌ A powerful laptop                                            │
│   ❌ To install anything                                          │
│   ❌ Windows/Mac/Linux — browser is enough!                      │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🚀 **Step 1: Create Your Codespace**

```
┌───────────────────────────────────────────────────────────┐
│           LAUNCHING YOUR CODESPACE                         │
├───────────────────────────────────────────────────────────┤
│                                                           │
│  📍 Go to your GitHub repo:                               │
│     https://github.com/YOUR_USER/juice-shop-ai-assistant │
│                                                           │
│  🖱️ Click the GREEN "Code" button → "Codespaces" tab     │
│                                                           │
│  🖱️ Click "Create codespace on main"                     │
│                                                           │
│  ⏳ Wait 30-60 seconds...                                 │
│     (GitHub is setting up your cloud computer!)           │
│                                                           │
│  🎉 WELCOME TO YOUR CODESPACE!                           │
│                                                           │
│  ┌──────────────────────────────────────────────────┐    │
│  │  ⬛ Left: File Explorer                           │    │
│  │  📝 Center: Code Editor                          │    │
│  │  ⬛ Bottom: Terminal (where we type commands!)   │    │
│  └──────────────────────────────────────────────────┘    │
│                                                           │
│  🔥 PRO TIP: You can also use github.dev —              │
│     just press . (dot) on any GitHub repo to open        │
│     a web editor instantly! (No Codespace needed!)       │
│                                                           │
└───────────────────────────────────────────────────────────┘
```

---

## 🖥️ **Your Codespace — A Tour**

```
┌─────────────────────────────────────────────────────────────────┐
│  📁 EXPLORER  │  📝 EDITOR (main area)              │  ... MENU │
├────────────────┤                                      ├──────────┤
│                │                                      │          │
│  📂 YOUR-REPO │    Welcome to Codespaces! 🎉         │  ☰       │
│  │             │                                      │          │
│  ├─ 📄 PRD.md │    ┌────────────────────────────┐    │  🔍      │
│  ├─ 📄 README │    │  This is your cloud IDE!   │    │          │
│  │ .md        │    │                            │    │  🔔      │
│  │             │    │  Left: Files (Explorer)    │    │          │
│  │             │    │  Center: Code (Editor)     │    │  👤      │
│  │             │    │  Bottom: Commands (Term)  │    │          │
│  │             │    └────────────────────────────┘    │          │
├────────────────┴──────────────────────────────────────┴──────────┤
│  ⬛ TERMINAL (BOTTOM PANEL)                                      │
│                                                                  │
│  $ echo "Hello from Codespaces!"                                │
│  Hello from Codespaces!                                         │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🎮 **Activity: Test Your Codespace Terminal**

The **terminal** is where we type commands. Let's test it!

```bash
# Type these commands one by one (press Enter after each)

# 1. Say hello!
echo "Hello from my cloud computer! 👋"

# 2. Who am I?
whoami

# 3. What's my computer's name?
hostname

# 4. Show current folder
pwd
# "pwd" = "print working directory" — shows where you are

# 5. List files
ls -la
# "ls" = "list" — shows all files in current folder
```

**Expected output:**
```
Hello from my cloud computer! 👋
codespace
juice-shop-ai-assistant-xxxx
/home/codespace/juice-shop-ai-assistant
total 16
drwxrwxrwx+ ... .
drwxr-xr-x  ... ..
-rw-r--r--  ... PRD.md
-rw-r--r--  ... README.md
```

---

## 🔧 **Step 2: Install Required Tools**

Your Codespace comes with some tools pre-installed. Let's check and install what's missing:

```bash
# Check Node.js
node --version
# Should show v22.x.x — if not, we'll install it

# Check Python
python3 --version
# Should show 3.10+

# Install Docker (we need this for ChromaDB)
curl -fsSL https://get.docker.com -o /tmp/get-docker.sh
sudo sh /tmp/get-docker.sh
sudo chmod 666 /var/run/docker.sock

# Verify Docker
docker --version

# Install uv (fast Python package manager)
curl -LsSf https://astral.sh/uv/install.sh | sh
export PATH="$HOME/.local/bin:$PATH"
uv --version
```

---

## 🆓 **Introducing Freebuff — Your AI Coding Assistant!**

Right inside your Codespace, you have **Freebuff** — an AI that helps you code!

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│  🆓 FREEBUFF = Your personal AI coding assistant                 │
│                                                                  │
│  Press Ctrl+I or Cmd+I in your Codespace editor                  │
│  to open the Freebuff chat panel. Then type your question!       │
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │  🆓 FREEBUFF: "How can I help?"                         │    │
│  │                                                          │    │
│  │  YOU: "Explain what this terminal command does"          │    │
│  │                                                          │    │
│  │  FREEBUFF: "This command installs Docker on your         │    │
│  │  system. Docker lets you run apps in containers..."      │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
│  💡 TRY IT NOW: Select the Docker install command above,        │
│     press Ctrl+I and ask: "What does this do?"                  │
│                                                                  │
│  Freebuff can:                                                   │
│  ✍️ Write code for you                                           │
│  📖 Explain code in simple terms                                 │
│  🐛 Help fix errors                                              │
│  🏗️ Suggest how to structure your project                       │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## ⚡ **Understanding Terminal Commands**

```
TERMINAL COMMANDS — YOUR NEW SUPERPOWERS 🦸
────────────────────────────────────────────

📌 Basic Commands:
─────────────────
📂 ls     = List files in current folder
📂 cd     = Change directory (go into a folder)
📂 pwd    = Where am I? (print working directory)
📂 mkdir  = Make a new folder
📂 rm     = Remove a file
📂 cp     = Copy a file
📂 mv     = Move or rename a file

📌 Running Code:
─────────────────
🐍 python3 script.py  = Run a Python file
🟢 node app.js        = Run a JavaScript file
📦 npm install        = Install packages

📌 Tips:
─────────────────
🔄 Ctrl+C = Cancel a running command
⬆️ Up arrow = Repeat previous command
📋 Tab = Auto-complete what you're typing
```

---

## 🎮 **Activity: Practice Terminal Commands**

```bash
# 1. Create a project folder
mkdir juice-shop-project

# 2. Go into the folder
cd juice-shop-project

# 3. Create a file
echo "My AI Project" > README.md

# 4. See what's in the folder
ls -la

# 5. Go back to parent folder
cd ..

# 6. Remove the test folder (cleanup)
rm -rf juice-shop-project

echo "🎉 You just learned terminal basics!"
```

---

## 📝 **Lesson 3 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ CHECKLIST                      │
│                                            │
│  [ ] Codespace created and running         │
│  [ ] VS Code in browser is working        │
│  [ ] Terminal works (echo, ls, pwd)       │
│  [ ] Node.js installed (v22+)             │
│  [ ] Python installed (v3.10+)            │
│  [ ] Docker installed                     │
│  [ ] uv installed                         │
│  [ ] Freebuff - tried Ctrl+I!            │
│                                            │
│  🎯 WHAT YOU LEARNED:                      │
│  • Codespace = Cloud computer in browser  │
│  • Terminal = Talk to your computer       │
│  • Commands are like text-based superpowers│
│  • Freebuff = AI assistant for coding     │
│                                            │
└────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 4: Launch Juice Shop -->
<!-- ============================================================ -->

# 🛒 **LESSON 4: Launch Juice Shop — See a Real E-Commerce Site!**

### *"Let's see how online shopping works TODAY!"*

---

## 🧃 **What is OWASP Juice Shop?**

```
OWASP Juice Shop = An intentionally insecure e-commerce website
──────────────────────────────────────────────────────────────

┌─────────────────────────────────────────────────────────────┐
│                                                             │
│  🏪 IT'S A REAL ONLINE JUICE STORE!                        │
│                                                             │
│  • Sells juices 🥤                                          │
│  • Sells merchandise 👕                                     │
│  • Has shopping cart 🛒                                     │
│  • Has checkout 💳                                          │
│  • Has customer reviews ⭐                                  │
│  • Has search 🔍                                            │
│                                                             │
│  🎯 It's design is SIMILAR to:                              │
│  • Amazon                                                   │
│  • Walmart                                                  │
│  • Any online store you've used!                            │
│                                                             │
│  🤔 BUT it has SECURITY FLAWS (intentional!)                │
│     We won't focus on that today —                          │
│     we're using it as an example e-commerce site!            │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 📥 **Step 1: Clone the Juice Shop Code**

Cloning = Downloading a copy of the code to your Codespace

```bash
# Go to your projects folder
cd ~

# Clone (download) the Juice Shop
git clone https://github.com/juice-shop/juice-shop.git

# This downloads the entire project!
# ⏳ Takes about 1-2 minutes
```

**What just happened?**
```
┌─────────────────────────────────────────────────────────────────┐
│                    GIT CLONE VISUALIZED                          │
│                                                                  │
│   🌐 GitHub (juice-shop/juice-shop)                             │
│       │                                                          │
│       │ 📦 ZIP file containing:                                  │
│       │   • All code files (500+)                               │
│       │   • All images                                           │
│       │   • Database structure                                   │
│       │   • Configuration files                                  │
│       │                                                          │
│       ▼                                                          │
│   💻 YOUR CODESPACE                                              │
│   ┌────────────────────────────────────────────────────┐        │
│   │  📁 juice-shop/                                     │        │
│   │    ├── 📄 server.ts (main server code)              │        │
│   │    ├── 📁 routes/ (page handlers)                   │        │
│   │    ├── 📁 frontend/ (the website you see)           │        │
│   │    ├── 📁 data/ (products, users, etc.)             │        │
│   │    ├── 📄 package.json (list of dependencies)       │        │
│   │    └── 📁 ... hundreds more files!                  │        │
│   └────────────────────────────────────────────────────┘        │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📦 **Step 2: Install Dependencies**

```bash
# Go into the Juice Shop folder
cd ~/juice-shop

# Install all required packages
npm install
# ⏳ Takes 2-3 minutes
# 📦 Downloads ~500+ packages
```

**What is npm install doing?**

```
npm install = Like going to a hardware store for tools 🔧
────────────────────────────────────────────────────────

┌─────────────────────────────────────────────────────────────┐
│  package.json (the shopping list)                            │
│  ┌─────────────────────────────────────────────────────┐    │
│  │  "dependencies": {                                   │    │
│  │    "express": "^4.18.0",     ← Web server           │    │
│  │    "sqlite3": "^5.1.0",     ← Database engine      │    │
│  │    "sequelize": "^6.0.0",   ← Database helper      │    │
│  │    ... 100+ more packages                           │    │
│  │  }                                                    │    │
│  └─────────────────────────────────────────────────────┘    │
│                              │                               │
│  npm install                 ▼                               │
│                              │                               │
│  ┌──────────────────────────▼────────────────────────┐     │
│  │  node_modules/ (the toolbox)                       │     │
│  │  ├── 📂 express/ → Web server ✓                    │     │
│  │  ├── 📂 sqlite3/ → Database ✓                     │     │
│  │  └── 📂 ... 500+ folders                          │     │
│  └───────────────────────────────────────────────────┘     │
└─────────────────────────────────────────────────────────────┘
```

---

## 🚀 **Step 3: Start the Juice Shop**

```bash
# Build the frontend (creates the website you'll see)
npm run build
# ⏳ Takes 2-3 minutes

# Start the server
npm start &
```

**What's happening?**

```
npm start → The server wakes up
───────────────────────────────

┌─────────────────────────────────────────────────────────────────┐
│  SERVER STARTUP LOG:                                            │
│                                                                  │
│  [INFO] Starting Juice Shop...                                  │
│  [INFO] Loading configuration...                                 │
│  [INFO] Connecting to database...                                │
│  [INFO] Database initialized (juiceshop.sqlite created!)        │
│  [INFO] 56 products loaded from database                        │
│  [INFO] Server started on http://localhost:3000                 │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐     │
│  │  🖥️ NOW VISIT: http://localhost:3000                    │     │
│  │  (In your browser — see the Juice Shop!)               │     │
│  └────────────────────────────────────────────────────────┘     │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🧭 **Step 4: Explore the Juice Shop!**

**OPEN http://localhost:3000 IN YOUR BROWSER** 🔗

```
┌─────────────────────────────────────────────────────────────────┐
│                     JUICE SHOP LANDING PAGE                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  🧃 OWASP Juice Shop                    [🛒 Cart: 0] [👤 Login]│
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │  🔍 [Search products...]                    🔎          │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐         │
│  │ 🥤            │  │ 🍊           │  │ 🥭           │         │
│  │ Apple Juice   │  │ Orange Juice │  │ Eggfruit     │         │
│  │ $1.99         │  │ $2.49        │  │ Juice $1.99  │         │
│  │ ⭐⭐⭐⭐☆       │  │ ⭐⭐⭐⭐⭐       │  │ ⭐⭐⭐☆☆       │         │
│  │ [Add to Cart] │  │ [Add to Cart] │  │ [Add to Cart]│         │
│  └──────────────┘  └──────────────┘  └──────────────┘         │
│                                                                  │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐         │
│  │ 👚           │  │ 🧢           │  │ 🏷️           │         │
│  │ Logo T-Shirt │  │ Cap          │  │ Sticker Sheet│         │
│  │ $14.99       │  │ $9.99        │  │ $0.99        │         │
│  │ ⭐⭐⭐⭐☆       │  │ ⭐⭐⭐☆☆       │  │ ⭐⭐⭐⭐⭐       │         │
│  │ [Add to Cart] │  │ [Add to Cart] │  │ [Add to Cart]│         │
│  └──────────────┘  └──────────────┘  └──────────────┘         │
│                                                                  │
│  Page 1 of 5  [1] [2] [3] [4] [5] [▶]                        │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🎮 **Activity: Complete These Tasks on Juice Shop**

```
🎯 YOUR MISSION — Complete these tasks on the live Juice Shop!
────────────────────────────────────────────────────────────────

TASK 1: Find the cheapest juice
────────────────────────────────
① Browse the first page
② Click "Next" (▶) to see more products
③ Keep track of prices you see
④ Which page had the cheapest item?
   Answer: __________________________

TASK 2: Find the OWASP hoodie
────────────────────────────────
① Search for "hoodie" in the search bar
② Click on the result
③ What's the price?
   Answer: $__________________________

TASK 3: Try to order something
────────────────────────────────
① Click "Add to Cart" on any item
② Click the cart icon (🛒)
③ Click "Checkout"
④ What happens next?
   Answer: __________________________

TASK 4: Count the clicks
────────────────────────────────
How many CLICKS does it take from landing
page to seeing product details?
Answer: _________ clicks
```

---

## 📊 **The Navigation Problem — Visualized**

```
JOURNEY TO ORDER A JUICE — TODAY'S E-COMMERCE
══════════════════════════════════════════════

🟢 = One page/action     🔴 = User must click/decide

Start ──────────────────────────────────────────────────────┐
  │                                                          │
  ▼                                                          │
🟢 LANDING PAGE                                              │
  │                                                          │
  ▼                                                          │
🔴 Decide: Browse or Search?                                 │
  │                                                          │
  ├──→ 🔴 Type search query                                  │
  │         │                                                │
  │         ▼                                                │
  │       🟢 Search Results Page                             │
  │         │                                                │
  │         ▼                                                │
  │       🔴 Which result to click?                          │
  │         │                                                │
  │         ▼                                                │
  │       🟢 Product Details Page                            │
  │         │                                                │
  │         ▼                                                │
  │       🔴 Click "Add to Cart"                             │
  │         │                                                │
  │         ▼                                                │
  │       🟢 Cart Page (item added!)                         │
  │         │                                                │
  │         ▼                                                │
  │       🔴 Continue shopping or Checkout?                  │
  │         │                                                │
  │         ├──→ 🔴 "Checkout" → Login page                 │
  │         │         │                                      │
  │         │         ▼                                      │
  │         │       🟢 Login Page                            │
  │         │         │                                      │
  │         │         ▼                                      │
  │         │       🔴 Type email + password                 │
  │         │         │                                      │
  │         │         ▼                                      │
  │         │       🟢 Shipping Address Page                 │
  │         │         │                                      │
  │         │         ▼                                      │
  │         │       🔴 Type address                          │
  │         │         │                                      │
  │         │         ▼                                      │
  │         │       🟢 Payment Page                          │
  │         │         │                                      │
  │         │         ▼                                      │
  │         │       🔴 Enter card details                    │
  │         │         │                                      │
  │         │         ▼                                      │
  │         │       🟢 Order Confirmation                    │
  │         │         │                                      │
  │         │         ▼                                      │
  │         │       🎉 Order placed!                         │
  │         │         (After 10-15+ clicks and 5+ pages!)    │
  │         │                                                │
  └─────────┘                                                │

😫 TOO MANY STEPS! TOO MANY PAGES! TOO MANY CLICKS!
```

---

## 🤔 **Realization Time — What Did You Notice?**

```
GROUP DISCUSSION:
─────────────────

❓ How many clicks to find a product's price?
   Answer: ______

❓ How many pages did you visit?
   Answer: ______

❓ Was it easy or frustrating?
   Answer: ______

❓ What if you couldn't find the search bar?
   Answer: ______

❓ What if you're on a phone with small screen?
   Answer: ______

❓ What if you have visual impairment?
   Answer: ______

💡 KEY INSIGHT:
   Navigation-based shopping is:
   • Time-consuming  😤
   • Confusing       🤔
   • Inaccessible    ♿
   • Mobile-unfriendly 📱

   THERE HAS TO BE A BETTER WAY!
```

---

## 💡 **The Better Way — Conversational Commerce**

```
TODAY (Navigation)                           TOMORROW (Conversation)
══════════════════                           ════════════════════════

┌─────────────────────┐                     ┌─────────────────────┐
│  LANDING PAGE       │                     │  CHAT WINDOW        │
│    ↓                 │                     │                     │
│  SEARCH             │                     │  💬 "What juices    │
│    ↓                 │                     │     do you sell?"   │
│  RESULTS            │                     │                     │
│    ↓                 │                     │  🤖 "We have Apple  │
│  PRODUCT PAGE       │                     │     ($1.99), Orange │
│    ↓                 │                     │     ($2.49)..."    │
│  ADD TO CART        │                     │                     │
│    ↓                 │                     │  💬 "I'll take 2   │
│  CART               │                     │     apple juices!"  │
│    ↓                 │                     │                     │
│  CHECKOUT           │                     │  🤖 "Added! Anything│
│    ↓                 │                     │     else?"         │
│  PAYMENT            │                     │                     │
│    ↓                 │                     │  💬 "No, thanks!"   │
│  DONE!              │                     │                     │
│                     │                     │  🎉 ORDER PLACED!   │
│  10+ CLICKS         │                     │                     │
│  5+ PAGES           │                     │  3 MESSAGES         │
│  ~2 MINUTES         │                     │  0 PAGE LOADS       │
│                     │                     │  ~15 SECONDS        │
└─────────────────────┘                     └─────────────────────┘

       Browsing                                      Chatting
       ⏬                                               💬
    Old way                                        New way!
```

---

## 📝 **Lesson 4 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ CHECKLIST                      │
│                                            │
│  [ ] Juice Shop cloned to Codespace       │
│  [ ] npm install completed                 │
│  [ ] npm run build completed               │
│  [ ] npm start — server running            │
│  [ ] Opened http://localhost:3000          │
│  [ ] Explored products                     │
│  [ ] Tried to order something              │
│  [ ] Counted clicks needed                 │
│                                            │
│  🎯 KEY REALIZATION:                       │
│  Navigation-based shopping is HARD.        │
│  We can do better with AI + conversation!  │
│                                            │
└────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 5: Pain Points Deep Dive -->
<!-- ============================================================ -->

# 😤 **LESSON 5: Experience Pain Points — Why Navigation Sucks**

### *"Let's REALLY understand the problem before we fix it!"*

---

## 🗺️ **The E-Commerce Navigation Map**

```
This is what a typical e-commerce site map looks like:

                    ┌──────────────┐
                    │   HOME PAGE  │
                    └──────┬───────┘
                           │
           ┌───────────────┼───────────────┐
           │               │               │
           ▼               ▼               ▼
     ┌──────────┐   ┌──────────┐   ┌──────────┐
     │ SEARCH   │   │CATEGORIES│   │ PROMOS   │
     └────┬─────┘   └────┬─────┘   └────┬─────┘
          │              │              │
          ▼              ▼              ▼
    ┌──────────┐   ┌──────────┐   ┌──────────┐
    │ RESULTS  │   │ PRODUCTS │   │ DEALS    │
    └────┬─────┘   └────┬─────┘   └──────────┘
         │              │
         ▼              ▼
    ┌──────────┐   ┌──────────┐
    │ PRODUCT  │   │ PRODUCT  │
    │ DETAILS  │   │ DETAILS  │
    └────┬─────┘   └────┬─────┘
         │              │
         ▼              ▼
    ┌──────────┐   ┌──────────┐
    │ADD TO    │   │ADD TO    │
    │CART      │   │CART      │
    └────┬─────┘   └────┬─────┘
         │              │
         └──────┬───────┘
                ▼
           ┌──────────┐
           │   CART   │
           └────┬─────┘
                │
                ▼
           ┌──────────┐      ┌──────────┐
           │ CHECKOUT │─────▶│  LOGIN   │
           └────┬─────┘      └──────────┘
                │
                ▼
           ┌──────────┐
           │ SHIPPING │
           └────┬─────┘
                │
                ▼
           ┌──────────┐
           │ PAYMENT  │
           └────┬─────┘
                │
                ▼
           ┌──────────┐
           │ CONFIRM  │
           └──────────┘

😵 Overwhelming, right?
```

---

## 🎯 **The 5 Big Problems with Navigation**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│   PROBLEM #1: TOO MANY CHOICES                                  │
│   ───────────────────────────                                    │
│                                                                  │
│   "Should I search, browse, or look at promotions?"             │
│   "Which category? Which subcategory?"                           │
│   "Page 1 of 5 — should I click all of them?"                   │
│                                                                  │
│   🧠 PARALYSIS BY ANALYSIS — too many options = user leaves!    │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│   PROBLEM #2: TOO MANY CLICKS                                   │
│   ────────────────────────────                                   │
│                                                                  │
│   Simple task: "Find the cheapest juice"                        │
│   → Check page 1 ($1.99, $2.49, $2.99)                         │
│   → Click page 2 ($1.99, $3.49, $4.99)                         │
│   → Click page 3 ($5.99, $2.99)                                 │
│   → Compare manually — which is cheapest?                       │
│   → 10+ clicks for a SIMPLE question!                           │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│   PROBLEM #3: HIDDEN INFORMATION                                │
│   ───────────────────────────────                                │
│                                                                  │
│   Want to know about DELIVERY? → Find the FAQ page              │
│   Want to know about RETURNS? → Find the policy page            │
│   Want to know about NUTRITION? → Scroll to product details     │
│                                                                  │
│   Information is scattered across pages!                        │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│   PROBLEM #4: MOBILE IS WORSE                                   │
│   ───────────────────────────────                                │
│                                                                  │
│   • Tiny screens → Less visible                                 │
│   • Fat fingers → Wrong clicks                                  │
│   • Slow loading → Wait for pages                               │
│   • Data usage → Every page costs money                         │
│                                                                  │
│   📱 70% of online shopping is on mobile!                       │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│   PROBLEM #5: NO PERSONALIZATION                                │
│   ────────────────────────────────                               │
│                                                                  │
│   Every user sees the SAME homepage:                            │
│   • New customer? Same page.                                    │
│   • Returning customer? Same page.                              │
│   • Premium member? Same page.                                  │
│   • Vegetarian? Still see meat products.                        │
│                                                                  │
│   The site doesn't KNOW you or your preferences!                │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📊 **The Data: How Bad Is It?**

```
┌─────────────────────────────────────────────────────────────────┐
│              E-COMMERCE STATISTICS (REAL DATA!)                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  📉 CART ABANDONMENT RATE:                                      │
│                                                                  │
│  70% ─██████████████████████████████████████████████░░░░░░░░░░  │
│        ↑                                                        │
│        7 out of 10 people ADD items to cart                     │
│        but never complete the purchase! 😱                       │
│                                                                  │
│  📉 WHY THEY LEAVE:                                             │
│                                                                  │
│  24% ─██████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   │
│        "Site required me to create an account"                  │
│                                                                  │
│  22% ─█████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   │
│        "Too long / complicated checkout"                        │
│                                                                  │
│  18% ─█████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   │
│        "Couldn't see total cost upfront"                        │
│                                                                  │
│  17% ─████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   │
│        "Website errors or crashed"                              │
│                                                                  │
│  📈 THE OPPORTUNITY:                                            │
│                                                                  │
│  🏆 Companies with AI chatbots see:                             │
│     • +35% conversion rate 💰                                   │
│     • +40% customer satisfaction 😊                             │
│     • -30% support costs 💸                                     │
│     • 24/7 availability ⏰                                      │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🤖 **The Solution: AI-Powered Conversational Commerce**

```
The AI assistant ELIMINATES navigation entirely:
═════════════════════════════════════════════════

🚫 NO more:                                 ✅ INSTEAD:
─────────────────────                     ─────────────────────

📄 Browsing pages                           💬 Just ask!
🔍 Searching manually                       🤖 AI answers instantly
🧮 Comparing prices yourself                📊 AI does the comparison
📑 Finding policies yourself                📋 AI knows all policies
🔄 Back-and-forth navigation               💭 Natural conversation
💪 Remembering products                     🧠 AI remembers context
```

---

## 🗣️ **Pair & Share Activity**

### *Turn to a partner and explain this in 30 seconds:*

```
"Explain why conversational AI is better than navigation-based shopping."

Your Explanation:
─────────────────
"Instead of __________________, you can _________________________
because ________________________________________________________
_______________________________________________________________"

🎯 Key points to include:
• Clicks vs messages
• Time comparison
• Mobile friendliness
• Personalization

Listen to your partner's explanation too!
What did they say that you didn't think of?
_______________________________________________________________
```

---

## 💬 **Class Discussion: Would You Use This?**

```
Raise your hand if:

✋ You've abandoned a shopping cart before
✋ You've gotten frustrated finding a product
✋ You'd prefer chatting instead of clicking
✋ You think AI shopping assistants are the future

💡 The future of ALL commerce is conversational!
   Every industry will adopt this.
   YOU are learning it NOW — that's a huge advantage!
```

---

## 📝 **Lesson 5 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ CHECKLIST                      │
│                                            │
│  [ ] Understood the 5 problems             │
│  [ ] Experienced the pain yourself         │
│  [ ] Saw the statistics                    │
│  [ ] Understand WHY AI helps               │
│  [ ] Explained to a partner (Pair & Share) │
│                                            │
│  🎯 KEY INSIGHT:                           │
│  The problem isn't the products —          │
│  it's HOW we find and buy them!           │
│  AI conversation = zero navigation!       │
│                                            │
└────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 6: Build the AI Chatbot -->
<!-- ============================================================ -->

# 🤖 **LESSON 6: Meet the AI — Building the Chatbot Brain**

### *"Now let's BUILD the solution!"*

---

## 🧠 **What is an AI Chatbot?**

```
A chatbot = A program that TALKS like a human
─────────────────────────────────────────────

┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│  User: "What juices do you sell?"                               │
│                                                                  │
│       ┌─────────────────────────────────────────────────┐       │
│       │          AI CHATBOT BRAIN                        │       │
│       │                                                 │       │
│       │  1. 🔍 Understand the question                 │       │
│       │     "juices" + "sell" = wants product list     │       │
│       │                                                 │       │
│       │  2. 🔎 Search for information                  │       │
│       │     Look in product database                   │       │
│       │                                                 │       │
│       │  3. ✍️ Generate a response                     │       │
│       │     "We have Apple Juice ($1.99),..."          │       │
│       │                                                 │       │
│       └─────────────────────────────────────────────────┘       │
│                                                                  │
│  Bot: "We have Apple Juice ($1.99), Orange Juice ($2.49),      │
│        and Eggfruit Juice ($1.99)! Which sounds good?"          │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🏗️ **Our Bot Architecture**

```
┌─────────────────────────────────────────────────────────────────┐
│                  HOW OUR AI BOT WORKS                            │
│                                                                  │
│   STEP 1: User types a question                                  │
│   ─────────────────────────────────────                          │
│   👤 "What's the cheapest juice?"                               │
│                                                                  │
│          │                                                       │
│          ▼                                                       │
│                                                                  │
│   STEP 2: Our Python server receives it                         │
│   ─────────────────────────────────────                         │
│   🚀 FastAPI (main.py): "Got it! Let me process this..."        │
│                                                                  │
│          │                                                       │
│          ▼                                                       │
│                                                                  │
│   STEP 3: Find relevant products (RAG — next lesson!)           │
│   ─────────────────────────────────────────────────────         │
│   🔍 ChromaDB: "Products related to 'cheap juice' found!"       │
│                                                                  │
│          │                                                       │
│          ▼                                                       │
│                                                                  │
│   STEP 4: Send to AI model with product data                    │
│   ──────────────────────────────────────────────                │
│   🧠 OpenRouter AI: "Here's the answer based on real data!"     │
│                                                                  │
│          │                                                       │
│          ▼                                                       │
│                                                                  │
│   STEP 5: Send answer back to user                              │
│   ───────────────────────────────────────                      │
│   🤖 "The Eggfruit Juice is $1.99 — our best deal!"             │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🔑 **Step 1: Get Your OpenRouter API Key**

```
OpenRouter = A GATEWAY to AI models
──────────────────────────────────────

┌─────────────────────────────────────────────────────────────┐
│                                                             │
│  🧠 OpenRouter gives you access to:                        │
│  • Multiple AI models (not just one!)                      │
│  • Free tier available (great for learning!)               │
│  • Pay-as-you-go (pennies per 1000 questions)              │
│  • Works like OpenAI (same code!)                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘

STEPS:
─────
1️⃣ Go to https://openrouter.ai/keys
2️⃣ Click "Sign Up" (use Google/GitHub for speed)
3️⃣ Click "Create API Key"
4️⃣ Copy your key (starts with sk-or-v1-...)
5️⃣ Save it — you'll need it soon!

⚠️ This is YOUR private key. Never share it!
   It's like the password to your AI account.
```

---

## 🏗️ **Step 2: Create the AI Assistant Project**

```bash
# Create our project folder
cd ~
mkdir -p juice-shop-assistant/static

# Go into the project
cd juice-shop-assistant

# Create virtual environment with uv
uv venv

# Save our API key (replace with YOUR key!)
echo "OPENROUTER_API_KEY=sk-or-v1-YOUR_KEY_HERE" > .env.openai

# Create requirements file
cat > requirements.txt << 'EOF'
fastapi>=0.110.0
uvicorn>=0.29.0
openai>=1.0.0
python-dotenv>=1.0.0
pydantic>=2.0.0
httpx>=0.27.0
chromadb>=1.5.0
sentence-transformers>=2.2.0
EOF

# Install everything
uv pip sync requirements.txt
```

---

## 💻 **Step 3: Write the AI Assistant Code**

Create `assistant.py` — the brain of our AI:

```python
"""
THE AI BRAIN 🧠
==============
This code talks to the AI model through OpenRouter.
"""

from openai import OpenAI
import os


class JuiceShopAssistant:
    """The AI that answers customer questions."""

    SYSTEM_PROMPT = """You are a helpful assistant for a juice shop.
Answer questions about products and prices.
Be friendly and use emojis!
Only answer based on the product data you're given."""

    def __init__(self):
        # Get API key from file
        api_key = os.environ.get("OPENROUTER_API_KEY", "")
        if not api_key:
            # Try to read from .env.openai
            with open(".env.openai") as f:
                for line in f:
                    if "OPENROUTER_API_KEY" in line:
                        api_key = line.split("=")[1].strip()
        
        # Connect to OpenRouter
        self.client = OpenAI(
            base_url="https://openrouter.ai/api/v1",
            api_key=api_key,
        )

    def ask(self, question, context=None):
        """Send a question to the AI and get an answer."""
        
        # Build the message
        messages = [
            {"role": "system", "content": self.SYSTEM_PROMPT},
        ]
        
        # Add context if we have it
        user_message = question
        if context:
            user_message = f"Product data:\n{context}\n\nQuestion: {question}"
        
        messages.append({"role": "user", "content": user_message})
        
        # Send to AI
        response = self.client.chat.completions.create(
            model="openrouter/free",  # Free AI model!
            messages=messages,
            max_tokens=500,  # Max length of response
            temperature=0.5,  # 0=strict, 1=creative
        )
        
        return response.choices[0].message.content
```

---

## 🐍 **Python Code Explained — Line by Line**

```python
from openai import OpenAI
# "from" = import a library
# This gives us tools to talk to AI models

class JuiceShopAssistant:
# "class" = a blueprint for creating something
# Like a recipe for making cookies

    def ask(self, question, context=None):
    # "def" = define a function (a reusable action)
    # "self" = refers to THIS assistant
    # "question" = what the user asked
    # "context" = product data (optional)
    
        messages = [
            {"role": "system", "content": self.SYSTEM_PROMPT},
        ]
        # Messages = the conversation history
        # System prompt = instructions for the AI
        
        response = self.client.chat.completions.create(
            model="openrouter/free",
            messages=messages,
        )
        # This sends the request to OpenRouter
        # Like sending a letter to the AI
        
        return response.choices[0].message.content
        # Extract the AI's response text
```

---

## 🎮 **Activity: Test Your AI Assistant**

Open a terminal and run:

```bash
# Go to project folder
cd ~/juice-shop-assistant

# Run Python interactively
uv run python
```

```python
# Now type these commands in Python:

from assistant import JuiceShopAssistant

# Create our AI
ai = JuiceShopAssistant()

# Ask it a question!
answer = ai.ask("What juices do you sell?", 
    context="Apple Juice $1.99, Orange Juice $2.49, Eggfruit Juice $1.99")

print("🤖:", answer)

# Try another
answer2 = ai.ask("What's the cheapest?",
    context="Apple Juice $1.99, Orange Juice $2.49, Eggfruit Juice $1.99")

print("🤖:", answer2)

# Exit Python
exit()
```

> 💡 **Expected result:** The AI should tell you about Apple and Eggfruit juices being $1.99!

---

## 🧪 **Understanding AI Parameters**

```
AI MODEL SETTINGS
══════════════════

🌡️ TEMPERATURE (0 to 1 or 2)
──────────────────────────────

Temperature = 0.0:
  "The cheapest juice is Eggfruit Juice at $1.99."
  → Always the same answer. Very predictable.

Temperature = 0.5:  ← WHAT WE USE
  "Our best deal is Eggfruit Juice at just $1.99! 🎉"
  → Natural but accurate. Best for business.

Temperature = 1.0:
  "OMG you HAVE to try the Eggfruit Juice!!! 
   It's like a party in your mouth for ONLY $1.99!!! 🥳🎉🎊"
  → Creative but might exaggerate.

📏 MAX TOKENS (1 to 4096)
───────────────────────────

Controls how long the AI's response can be.
Like: "Write a short answer" vs "Write an essay"
```

---

## 📝 **Lesson 6 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ CHECKLIST                      │
│                                            │
│  [ ] OpenRouter account created           │
│  [ ] API key generated and saved           │
│  [ ] Project folder created                │
│  [ ] Python packages installed             │
│  [ ] assistant.py written                  │
│  [ ] Tested AI with a question             │
│  [ ] Saw the AI respond!                   │
│                                            │
│  🎯 MILESTONE ACHIEVED:                    │
│  You just talked to an AI through code!   │
│  This is how ALL AI apps communicate!     │
│                                            │
└────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 7: RAG Knowledge -->
<!-- ============================================================ -->

# 🔍 **LESSON 7: RAG — Giving the AI Product Knowledge**

### *"Without data, the AI is guessing. Let's fix that!"*

---

## 🧩 **The Problem: AI Doesn't Know Your Products**

```
Without RAG:
────────────────────────────────────────────────────────────

👤 User: "What juices do you sell?"

                  🧠 AI (no context)
                  │
                  ├── "I think some shops sell juices..."
                  ├── "But I don't know YOUR shop's products!"
                  └── "I might make up fake products! 😱"

❗ This is called HALLUCINATION — AI making stuff up!

────────────────────────────────────────────────────────────

With RAG:
────────────────────────────────────────────────────────────

👤 User: "What juices do you sell?"
                     │
                     ▼
         ┌─────────────────────┐
         │  🔍 RAG System      │
         │  Searches REAL data │
         └──────────┬──────────┘
                    │
                    ▼
         "Here are the ACTUAL products
          from the Juice Shop database:"
         • Apple Juice  → $1.99
         • Orange Juice → $2.49
         • Eggfruit     → $1.99
                    │
                    ▼
         🧠 AI (with context)
         │
         └── "We have Apple Juice ($1.99),
                Orange Juice ($2.49)..."
         
✅ AI answers based on REAL data!
```

---

## 🔬 **How RAG Works — The Full Picture**

```
RAG = Retrieval-Augmented Generation
──────────────────────────────────────

              ┌─────────────────────────────┐
              │  👤 USER ASKS:              │
              │  "cheap fruity drink"        │
              └─────────────┬───────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│  STEP 1: RETRIEVE (Find relevant info)                      │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  "cheap fruity drink"                                       │
│         │                                                    │
│         │ Convert to vector (AI fingerprint)                │
│         ▼                                                    │
│  Vector: [0.32, 0.87, 0.11, 0.45, ...]                     │
│         │                                                    │
│         │ Search ChromaDB for closest vectors               │
│         ▼                                                    │
│  ┌──────────────────────────────────────────────────────┐   │
│  │  RESULTS:                                              │   │
│  │  🥇 Apple Juice   → similarity: 0.94 (94% match!)     │   │
│  │  🥈 Eggfruit Juice → similarity: 0.89 (89% match!)    │   │
│  │  🥉 Orange Juice  → similarity: 0.82 (82% match!)     │   │
│  └──────────────────────────────────────────────────────┘   │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│  STEP 2: AUGMENT (Add context to the question)              │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  "Here is the product data:                                 │
│   • Apple Juice - $1.99                                     │
│   • Eggfruit Juice - $1.99                                 │
│   • Orange Juice - $2.49                                   │
│                                                             │
│   Customer Question: 'cheap fruity drink'                   │
│   Please answer based on this data."                        │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│  STEP 3: GENERATE (AI creates the answer)                   │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  🧠 AI reads context + question → generates answer:        │
│                                                             │
│  "Our cheapest fruity drinks are Apple Juice                 │
│   and Eggfruit Juice, both at just $1.99! 🎉                │
│   Apple is crisp and refreshing, while                      │
│   Eggfruit is tropical and sweet! 🥤"                       │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 🖐️ **Analogy: RAG = Open Book Exam**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│         WITHOUT RAG = CLOSED BOOK EXAM 😰                       │
│                                                                  │
│  You walk into an exam.                                         │
│  The teacher asks: "What's the atomic weight of Nitrogen?"      │
│  You have to guess from memory!                                 │
│  You might be wrong!                                            │
│                                                                  │
│  → This is what happens when AI answers without context!        │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│         WITH RAG = OPEN BOOK EXAM ✅                             │
│                                                                  │
│  Same exam. But this time...                                    │
│  The teacher gives you the textbook.                            │
│  "Here are the relevant pages," says the teacher.               │
│  You read the exact page and give the correct answer.           │
│                                                                  │
│  → This is RAG! The AI gets the "textbook" before answering!    │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  The textbook = Our ChromaDB vector database                    │
│  The relevant pages = RAG retrieval results                     │
│  The student = The AI model                                      │
│                                                                  │
│  RESULT: 100% accurate answers based on real data! 🎯           │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🏗️ **Building the RAG System — rag.py**

Here's the complete RAG code, explained simply:

```python
"""
RAG SYSTEM 🔍
============
This gives the AI REAL product data to answer questions!
"""

import chromadb
from sentence_transformers import SentenceTransformer

# ─── CONFIGURATION ────────────────────────────────────────────

CHROMA_HOST = "localhost"    # ChromaDB runs on our computer
CHROMA_PORT = 8001           # Port 8001
MODEL_NAME = "all-MiniLM-L6-v2"  # The "fingerprint maker"


# ─── STEP 1: START CHROMADB IN DOCKER ─────────────────────────

# Run this in terminal FIRST:
# docker run -d --name chromadb -p 8001:8000 chromadb/chroma:latest


# ─── STEP 2: CONNECT TO CHROMADB ──────────────────────────────

def connect_chromadb():
    """Connect to our vector database."""
    client = chromadb.HttpClient(host=CHROMA_HOST, port=CHROMA_PORT)
    return client


# ─── STEP 3: CREATE COLLECTION ────────────────────────────────

def get_collection(client):
    """Get or create our product collection."""
    return client.get_or_create_collection("juice_shop_products")
    # A collection = like a folder for similar data


# ─── STEP 4: LOAD THE FINGERPRINT MAKER ──────────────────────

model = SentenceTransformer(MODEL_NAME)
# This turns words into vectors (AI fingerprints)


# ─── STEP 5: STORE PRODUCTS AS VECTORS ────────────────────────

def seed_products(products):
    """Convert products to vectors and store in ChromaDB."""
    
    for product in products:
        # Create text description
        text = f"{product['name']} ${product['price']} {product['description']}"
        
        # Convert to vector (AI fingerprint)
        vector = model.encode(text)
        
        # Store in ChromaDB
        collection.upsert(
            ids=[str(product['id'])],
            embeddings=[vector],
            metadatas=[{"name": product['name'], 
                       "price": product['price']}]
        )
    
    print(f"✅ Stored {len(products)} products as vectors!")


# ─── STEP 6: SEARCH BY MEANING ────────────────────────────────

def search_products(query, top_k=5):
    """Find products most relevant to the question."""
    
    # Convert question to vector
    query_vector = model.encode(query)
    
    # Find closest matches
    results = collection.query(
        query_embeddings=[query_vector],
        n_results=top_k,
    )
    
    return results['metadatas'][0]
```

---

## 🔄 **RAG in Action — See It Work!**

```
Let's trace through a REAL example:
═══════════════════════════════════════

Q: "What merchandise can I buy?"
─────────────────────────────────

Step 1: Convert to vector
  "merchandise" → [0.12, 0.89, 0.34, ...]
  "buy"         → [0.45, 0.67, 0.23, ...]
  Combined      → [0.28, 0.78, 0.29, ...]

Step 2: ChromaDB searches ALL 56 product vectors
  Compares question vector to each product vector
  Finds the closest matches:

  ┌──────────────────────────────────────────────────────┐
  │  RANK │ PRODUCT        │ PRICE  │ SIMILARITY         │
  ├──────────────────────────────────────────────────────┤
  │   🥇  │ Logo T-Shirt   │ $14.99 │ 98.2% ← Almost    │
  │   🥈  │ Logo Hoodie    │ $29.99 │ 95.7%    perfect  │
  │   🥉  │ Cap            │ $9.99  │ 91.3%    match!   │
  │   4th │ Sticker Sheet  │ $0.99  │ 87.1%             │
  │   5th │ Apple Juice    │ $1.99  │ 12.5% ← Not merch!│
  └──────────────────────────────────────────────────────┘

Step 3: Send to AI with these products as context

Step 4: AI generates answer
  "We have great merchandise! 👕
   • Logo T-Shirt — $14.99
   • Logo Hoodie — $29.99
   • Cap — $9.99
   • Sticker Sheet — $0.99
   Which one interests you?"
```

---

## 📊 **RAG vs Old Search — Side by Side**

```
┌─────────────────────────────────────────────────────────────────┐
│          RAG SEARCH          │       TRADITIONAL SEARCH         │
├──────────────────────────────┼──────────────────────────────────┤
│                              │                                  │
│  Q: "cheap fruity drink"    │  Q: "cheap fruity drink"         │
│                              │                                  │
│  🔍 ChromaDB searches by    │  🔍 SQL searches for EXACT       │
│     MEANING, not keywords   │     word match                   │
│                              │                                  │
│  ✓ "cheap" ≈ "affordable"   │  ✗ "cheap" → no exact match     │
│  ✓ "fruity" ≈ "juice"       │  ✗ "fruity" → no exact match    │
│  ✓ "drink" ≈ "juice"        │  ✗ "drink" → no exact match     │
│                              │                                  │
│  RESULTS:                    │  RESULTS:                        │
│  1. Apple Juice $1.99  (94%)│  (empty — no keywords found!)   │
│  2. Eggfruit Juice $1.99(89%)│                                  │
│  3. Orange Juice $2.49 (82%)│  ❌ 0 results!                   │
│                              │                                  │
│  ✅ Found what user meant!   │  ❌ Only finds exact keywords!  │
│                              │                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🐳 **Start ChromaDB (the RAG Database)**

```bash
# Make sure Docker is running
docker ps

# Pull and start ChromaDB (one time setup)
docker run -d \
  --name chromadb \
  -p 8001:8000 \
  chromadb/chroma:latest

# Verify it's running
curl http://localhost:8001/api/v1/health

# Expected: {"nanosecond heartbeat": ...} 
# (This means it's alive! 🎉)
```

---

## 🎮 **Activity: Test RAG Search**

```bash
# Start Python
uv run python
```

```python
# Paste and run:

import rag
from database import get_all_products

# 1. Connect to ChromaDB
collection = rag.get_collection(rag.connect_chromadb())

# 2. Get products from Juice Shop
products = get_all_products()
print(f"📦 Found {len(products)} products!")

# 3. Store them as vectors (first time only)
rag.seed_products(products)

# 4. Search by meaning!
results = rag.search_products("cheap fruity drink", top_k=3)

print("\n🔍 RAG Search Results:")
print("─" * 40)
for r in results:
    print(f"  🏆 {r['name']} — ${r['price']}")
    print(f"     (similarity: {r.get('relevance_score', 'N/A')})")
    print()

exit()
```

---

## 📝 **Lesson 7 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ CHECKLIST                      │
│                                            │
│  [ ] Understand RAG concept (open book)   │
│  [ ] ChromaDB running in Docker            │
│  [ ] Products stored as vectors            │
│  [ ] Tested RAG search                     │
│  [ ] Saw semantic search in action         │
│                                            │
│  🎯 KEY INSIGHT:                           │
│  RAG = Giving AI the right information     │
│  before it answers.                        │
│  Vectors = AI fingerprints for words       │
│  ChromaDB = Database of fingerprints       │
│                                            │
│  Without RAG: AI guesses 🤷                 │
│  With RAG: AI KNOWS 🎯                     │
└────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 8: Connect Everything -->
<!-- ============================================================ -->

# 🚀 **LESSON 8: Connect Everything — AI + E-Commerce**

### *"Putting it all together!"*

---

## 🗺️ **The Complete System**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│            THE FULL PICTURE — ALL PIECES WORKING                 │
│                                                                  │
│   👤 YOU (Browser at http://localhost:8000)                     │
│   │                                                              │
│   │  💬 "What's the cheapest juice?"                            │
│   ▼                                                              │
│   ┌──────────────────────────────────────────────────────┐      │
│   │  🧃 CHAT INTERFACE (chat.html)                       │      │
│   │  Beautiful chat window — you type here!              │      │
│   └─────────────────┬────────────────────────────────────┘      │
│                     │ POST /chat                                 │
│                     ▼                                            │
│   ┌──────────────────────────────────────────────────────┐      │
│   │  🚀 FASTAPI SERVER (main.py)                         │      │
│   │  • Receives your message                             │      │
│   │  • Calls RAG to find relevant products               │      │
│   │  • Formats data for AI                               │      │
│   │  • Sends to OpenRouter                               │      │
│   │  • Returns answer                                    │      │
│   └──────┬─────────────────────────────┬─────────────────┘      │
│          │                             │                          │
│          ▼                             ▼                          │
│   ┌──────────────┐           ┌──────────────────┐                │
│   │  🔍 RAG      │           │  🧠 OPENROUTER   │                │
│   │  (rag.py)    │           │  (assistant.py)  │                │
│   │  + ChromaDB  │           │  Cloud AI Model   │                │
│   │  (Docker)    │           │  Generates answer │                │
│   └──────────────┘           └──────────────────┘                │
│                                                                  │
│   🗄️ SQLite Database (Juice Shop products)                     │
│     /home/codespace/juice-shop/data/juiceshop.sqlite             │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🏗️ **Step 1: Create the Database Layer — database.py**

```python
"""
DATABASE LAYER 🗄️
==================
Connects to Juice Shop's SQLite database and gets product info.
"""

import sqlite3
from pathlib import Path

# Path to the Juice Shop database
DB_PATH = Path.home() / "juice-shop" / "data" / "juiceshop.sqlite"

def get_products():
    """Get ALL products from the shop."""
    
    # 1. Connect to database
    conn = sqlite3.connect(str(DB_PATH))
    conn.row_factory = sqlite3.Row  # Makes results easier to use
    
    # 2. Run SQL query
    cursor = conn.cursor()
    cursor.execute("SELECT id, name, price, description FROM Products")
    rows = cursor.fetchall()
    
    # 3. Convert to list of dictionaries
    products = [dict(row) for row in rows]
    
    # 4. Close connection
    conn.close()
    
    return products


def search_products(keyword):
    """Search products by name or description."""
    conn = sqlite3.connect(str(DB_PATH))
    conn.row_factory = sqlite3.Row
    cursor = conn.cursor()
    
    # LIKE means "contains this text"
    cursor.execute(
        "SELECT * FROM Products WHERE name LIKE ? OR description LIKE ?",
        (f"%{keyword}%", f"%{keyword}%")
    )
    rows = cursor.fetchall()
    conn.close()
    return [dict(row) for row in rows]


def format_products(products):
    """Format products for the AI to read."""
    if not products:
        return "No products found."
    
    lines = ["📋 Products:", "─" * 40]
    for p in products:
        lines.append(f"• {p['name']} — ${p['price']:.2f}")
        if p.get('description'):
            lines.append(f"  {p['description'][:100]}")
    
    return "\n".join(lines)
```

---

## 🏗️ **Step 2: Create the API Server — main.py**

```python
"""
THE API SERVER 🚀
=================
The "waiter" between your chat and the AI.
"""

import uvicorn
from fastapi import FastAPI
from fastapi.responses import FileResponse
from pydantic import BaseModel
from pathlib import Path

# ─── SETUP ────────────────────────────────────────────────────

app = FastAPI(title="Juice Shop AI Assistant")

import assistant
import rag
from database import get_products, search_products, format_products


# ─── REQUEST/RESPONSE MODELS ─────────────────────────────────

class ChatRequest(BaseModel):
    message: str     # The user's question
    history: list = []  # Previous messages (for context)

class ChatResponse(BaseModel):
    answer: str      # The AI's response
    tokens_used: int = 0


# ─── SERVE THE CHAT UI ──────────────────────────────────────

@app.get("/")
async def home():
    return FileResponse("static/chat.html")


# ─── HEALTH CHECK ─────────────────────────────────────────────

@app.get("/health")
async def health():
    return {"status": "healthy 🟢", "service": "Juice Shop AI"}


# ─── LIST PRODUCTS ────────────────────────────────────────────

@app.get("/products")
async def list_products():
    products = get_products()
    return {"count": len(products), "products": products}


# ─── CHAT ENDPOINT ────────────────────────────────────────────

@app.post("/chat")
async def chat(request: ChatRequest):
    """Main chat endpoint — this is what the UI calls!"""
    
    # 1. Get ALL products (for now — RAG will be added)
    products = get_products()
    context = format_products(products)
    
    # 2. Create AI assistant
    ai = assistant.JuiceShopAssistant()
    
    # 3. Ask the AI with product context
    answer = ai.ask(request.message, context)
    
    # 4. Return answer
    return ChatResponse(answer=answer)


# ─── START THE SERVER ─────────────────────────────────────────

if __name__ == "__main__":
    print("🚀 Starting Juice Shop AI Assistant...")
    print("📋 Chat UI: http://localhost:8000")
    print("📚 Docs:    http://localhost:8000/docs")
    uvicorn.run(app, host="0.0.0.0", port=8000)
```

---

## 💻 **Step 3: Create the Chat Interface — chat.html**

```html
<!DOCTYPE html>
<html>
<head>
    <title>🧃 Juice Shop AI</title>
    <style>
        /* Dark theme — like a premium chat app! */
        body {
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            font-family: 'Segoe UI', system-ui, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            color: white;
        }
        
        .chat-container {
            width: 90%;
            max-width: 700px;
            height: 90vh;
            max-height: 800px;
            background: rgba(255,255,255,0.05);
            backdrop-filter: blur(20px);
            border-radius: 24px;
            border: 1px solid rgba(255,255,255,0.1);
            display: flex;
            flex-direction: column;
            overflow: hidden;
        }
        
        .header {
            padding: 20px 24px;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            text-align: center;
        }
        
        .header h1 { margin: 0; font-size: 1.4em; }
        .header p { margin: 4px 0 0; opacity: 0.6; font-size: 0.9em; }
        
        .messages {
            flex: 1;
            overflow-y: auto;
            padding: 20px;
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        
        .message {
            max-width: 80%;
            padding: 12px 18px;
            border-radius: 18px;
            line-height: 1.5;
            animation: fadeIn 0.3s;
        }
        
        .message.user {
            background: linear-gradient(135deg, #667eea, #764ba2);
            align-self: flex-end;
            border-radius: 18px 18px 4px 18px;
        }
        
        .message.bot {
            background: rgba(255,255,255,0.08);
            align-self: flex-start;
            border-radius: 18px 18px 18px 4px;
        }
        
        .input-area {
            padding: 16px 20px;
            border-top: 1px solid rgba(255,255,255,0.1);
            display: flex;
            gap: 12px;
        }
        
        .input-area textarea {
            flex: 1;
            background: rgba(255,255,255,0.08);
            border: 1px solid rgba(255,255,255,0.15);
            border-radius: 12px;
            padding: 12px 16px;
            color: white;
            font-size: 1em;
            resize: none;
            outline: none;
        }
        
        .input-area button {
            background: linear-gradient(135deg, #667eea, #764ba2);
            border: none;
            border-radius: 12px;
            padding: 12px 24px;
            color: white;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.2s;
        }
        
        .input-area button:hover {
            transform: scale(1.05);
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

<div class="chat-container">
    <div class="header">
        <h1>🧃 Juice Shop AI</h1>
        <p>Ask me anything about our products!</p>
    </div>
    
    <div class="messages" id="messages">
        <!-- Welcome message -->
        <div class="message bot">
            👋 Hi! I'm the Juice Shop Assistant.<br>
            Ask me about our products — no browsing needed!
        </div>
    </div>
    
    <div class="input-area">
        <textarea id="input" rows="1" 
            placeholder="Ask something..."></textarea>
        <button onclick="sendMessage()">Send</button>
    </div>
</div>

<script>
    async function sendMessage() {
        const input = document.getElementById('input');
        const msg = input.value.trim();
        if (!msg) return;
        
        // Show user message
        addMessage(msg, 'user');
        input.value = '';
        
        // Send to API
        const res = await fetch('/chat', {
            method: 'POST',
            headers: {'Content-Type': 'application/json'},
            body: JSON.stringify({message: msg})
        });
        const data = await res.json();
        
        // Show AI response
        addMessage(data.answer, 'bot');
    }
    
    function addMessage(text, role) {
        const div = document.createElement('div');
        div.className = 'message ' + role;
        div.textContent = text;
        document.getElementById('messages').appendChild(div);
        div.scrollIntoView({behavior: 'smooth'});
    }
    
    // Send on Enter (Shift+Enter for new line)
    document.getElementById('input').addEventListener('keydown', (e) => {
        if (e.key === 'Enter' && !e.shiftKey) {
            e.preventDefault();
            sendMessage();
        }
    });
</script>

</body>
</html>
```

---

## 🚀 **Step 4: Launch Everything!**

```bash
# 1. Make sure ChromaDB is running
docker ps | grep chromadb

# 2. Make sure Juice Shop is running
curl -s -o /dev/null -w "%{http_code}" http://localhost:3000
# Should say: 200

# 3. Start our AI Assistant!
cd ~/juice-shop-assistant
uv run python main.py
```

**What you'll see:**
```
🚀 Starting Juice Shop AI Assistant...
📋 Chat UI: http://localhost:8000
📚 Docs:    http://localhost:8000/docs
```

---

## 🎮 **Activity: Test Your AI Assistant!**

**Open http://localhost:8000 in your browser** and try these questions:

```
🗣️ "What juices do you sell?"
    → AI should list all products with prices

🗣️ "What's the cheapest item?"
    → AI should find the best deal

🗣️ "Do you have any merchandise?"
    → AI should find apparel/stickers

🗣️ "What can I get for under $3?"
    → AI should filter by price

🗣️ "I want something fruity and cheap"
    → AI should understand meaning, not just keywords
```

---

## 🆓 **Using Freebuff Throughout Your Project**

Now that everything is running, use Freebuff to help improve it!

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│  🆓 FREEBUFF CODING AGENT — Use It Everywhere!                  │
│                                                                  │
│  📖 EXPLAIN: Select any code and press Ctrl+I                   │
│     "Explain this function line by line"                        │
│                                                                  │
│  ✍️ IMPROVE: Select code and press Ctrl+I                      │
│     "Add error handling for when the server is down"            │
│                                                                  │
│  🐛 DEBUG: Copy error message and press Ctrl+I                  │
│     "What does this error mean and how do I fix it?"            │
│                                                                  │
│  🏗️ ADD FEATURES: Press Ctrl+I with no code selected           │
│     "Add a new endpoint that shows products by category"        │
│                                                                  │
│  💡 Freebuff also uses AI — the SAME technology you just        │
│     built! You're now using AI to HELP you code AI!             │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📝 **Lesson 8 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ CHECKLIST                      │
│                                            │
│  [ ] database.py created                   │
│  [ ] main.py created                       │
│  [ ] chat.html created                     │
│  [ ] Server running on port 8000           │
│  [ ] Chat UI works in browser              │
│  [ ] AI answers product questions          │
│  [ ] Used Freebuff to improve code         │
│                                            │
│  🎯 YOU DID IT!                            │
│  The full system is running!               │
│  AI + E-Commerce + RAG = 🚀                │
│                                            │
└────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- LESSON 9: Final Demo & Future -->
<!-- ============================================================ -->

# 🎉 **LESSON 9: Final Demo & The Future**

### *"See the complete solution + Where we go from here!"*

---

## 🎬 **The Grand Demo**

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║              🧃 AI-POWERED SHOPPING DEMO 🧃                 ║
║                                                              ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  You vs Old Way:                                             ║
║  ─────────────────                                           ║
║                                              ║
║  👤 "What juices do you sell?"              ║
║     Old: 5 pages, 10+ clicks                ║
║     NEW: 1 question, 1 answer 🎯            ║
║                                              ║
║  👤 "What's cheapest?"                      ║
║     Old: Compare prices manually            ║
║     NEW: AI tells you instantly ⚡           ║
║                                              ║
║  👤 "Do you have t-shirts?"                 ║
║     Old: Browse categories                   ║
║     NEW: 1 chat message 💬                   ║
║                                              ║
║  👤 "I'll take 2 apple juices"              ║
║     Old: Add to cart → checkout → ...       ║
║     NEW: AI understands intent 🧠            ║
║                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 📊 **Old Way vs New Way — Final Comparison**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│         OLD WAY (Navigation)         │   NEW WAY (Conversation)  │
├──────────────────────────────────────┼──────────────────────────┤
│                                      │                          │
│  Visit homepage                      │  Open chat window        │
│       ↓                              │       ↓                  │
│  Find search bar                     │  Type: "I need..."       │
│       ↓                              │       ↓                  │
│  Type keywords                       │  AI understands          │
│       ↓                              │       ↓                  │
│  Browse results                      │  AI searches database    │
│       ↓                              │       ↓                  │
│  Click product                       │  AI generates response   │
│       ↓                              │       ↓                  │
│  Read description                    │  You get answer in       │
│       ↓                              │  seconds!                │
│  Check price                         │       ↓                  │
│       ↓                              │  Ask follow-up:          │
│  Add to cart                         │  "I'll take it!"         │
│       ↓                              │                          │
│  Continue or checkout                │  Total: 3-4 messages     │
│       ↓                              │  Total: 0 page loads     │
│  Login/register                      │  Total: ~30 seconds      │
│       ↓                              │                          │
│  Enter shipping                      │  😊 HAPPY CUSTOMER       │
│       ↓                              │                          │
│  Enter payment                       │                          │
│       ↓                              │                          │
│  Confirm order                       │                          │
│                                      │                          │
│  Total: 12+ steps                    │                          │
│  Total: 6+ pages                     │                          │
│  Total: 5+ minutes                   │                          │
│                                      │                          │
│  😫 FRUSTRATED CUSTOMER              │                          │
│                                      │                          │
└─────────────────────────────────────────────────────────────────┘


📉 70% cart abandonment              📈 35% increase in sales
📉 High bounce rates                 📈 40% happier customers
📉 Expensive support                 📈 24/7 instant support
```

---

## 🌍 **This is BIGGER Than Juice Shop!**

```
The SAME pattern works for ANY industry!
═══════════════════════════════════════════

┌─────────────────────────────────────────────────────────────────┐
│      WHAT WE BUILT           │   WHERE IT CAN BE USED           │
├──────────────────────────────┼──────────────────────────────────┤
│                              │                                  │
│  🧃 Juice Shop Assistant     │  🏪 ANY e-commerce store!        │
│                              │     (Amazon, Walmart, etc.)      │
│  Query: "What juices?"       │                                  │
│  Query: "Cheapest item?"     │  🏥 Healthcare:                  │
│  Query: "Product info"       │     "What are my symptoms?"      │
│                              │                                  │
│  RAG database: Products      │  🏦 Banking:                     │
│                              │     "What's my balance?"         │
│  AI model: OpenRouter        │                                  │
│                              │  🎓 Education:                   │
│  Chat interface: HTML+JS     │     "Explain quantum physics"    │
│                              │                                  │
│                              │  🚚 Logistics:                   │
│  💡 GOLDEN PATTERN:          │     "Where's my package?"        │
│  Chat → Search → AI → Reply │                                  │
│                              │  🎮 Gaming:                      │
│                              │     "How do I level up?"         │
│                              │                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📈 **The Market Trend — Conversational AI is EXPLODING**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│   MARKET SIZE: CONVERSATIONAL AI                                 │
│                                                                  │
│   2020  ████████████░░░░░░░░░░░░░░░░░░░░░░  $4.8 Billion        │
│   2021  ██████████████████░░░░░░░░░░░░░░░░  $6.8 Billion        │
│   2022  ████████████████████████░░░░░░░░░░  $10.7 Billion       │
│   2023  ██████████████████████████████░░░░  $14.2 Billion       │
│   2024  ██████████████████████████████████  $18.4 Billion       │
│   2025  ██████████████████████████████████  ██  Projected:      │
│   2026  ██████████████████████████████████  ████  $30+ Billion! │
│         ─────────────────────────────────────                    │
│         2019               2024              2030                │
│                                                                  │
│   📊 GROWTH: ~22% per year                                      │
│   🏆 EVERY major company is building AI chatbots:               │
│      • Amazon → Alexa Shopping                                   │
│      • McDonald's → AI Drive-Thru                                │
│      • Bank of America → Erica chatbot                          │
│      • Starbucks → Barista AI                                   │
│      • Domino's → Dom the pizza bot                             │
│      • H&M → Shopping assistant bot                             │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🎓 **What You've Learned Today**

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║              🏆 SKILLS YOU'VE ACQUIRED 🏆                    ║
║                                                              ║
║  ✅ CREATED your GitHub account & first repository           ║
║  ✅ WROTE a Product Requirements Document (PRD)              ║
║  ✅ LAUNCHED a Codespace (4vCPU, 16GB cloud computer)        ║
║  ✅ CLONED and RAN a real e-commerce website                 ║
║  ✅ IDENTIFIED navigation pain points in online shopping     ║
║  ✅ UNDERSTOOD API, LLM, and RAG concepts                   ║
║  ✅ OBTAINED OpenRouter API key for AI access               ║
║  ✅ WROTE Python code that talks to an AI model             ║
║  ✅ BUILT a RAG system with ChromaDB vector search          ║
║  ✅ CREATED a chat interface in HTML/CSS/JS                 ║
║  ✅ CONNECTED everything into a working AI assistant         ║
║  ✅ USED Freebuff AI coding agents to help write code       ║
║  ✅ UNDERSTOOD the market shift to conversational commerce  ║
║                                                              ║
║     FROM ZERO TO AI-POWERED E-COMMERCE IN ONE DAY! 🚀      ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 🎯 **Your New Superpowers**

```
BEFORE THIS COURSE:                    AFTER THIS COURSE:
───────────────────                   ───────────────────

❌ "AI is magic I don't understand"   ✅ "I know how AI works!"
❌ "I can't code"                      ✅ "I wrote Python code!"
❌ "Chatbots are complicated"         ✅ "I built one myself!"
❌ "GitHub is for pros"               ✅ "I have a GitHub repo!"
❌ "Cloud computers are scary"        ✅ "I launched a Codespace!"
❌ "RAG is a mystery"                 ✅ "I understand RAG!"

┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│     🗣️ YOU CAN NOW EXPLAIN TO ANYONE:                          │
│                                                                  │
│     "RAG is like giving the AI an open-book exam —             │
│      you give it the right information before it answers!"      │
│                                                                  │
│     "APIs are like waiters — they take requests                 │
│      from your app to other services and bring                  │
│      back the response!"                                        │
│                                                                  │
│     "Vectors are AI fingerprints — similar words               │
│      have similar fingerprints!"                                │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🚀 **What's Next? Your Project Ideas**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│  🏪 PROJECT 1: YOUR OWN STORE                                   │
│     Replace Juice Shop with your products!                      │
│     → A bakery, a bookstore, a gadget shop                     │
│     → Just change the database!                                │
│     ⭐ Difficulty: ⭐                                           │
│                                                                  │
│  📚 PROJECT 2: DOCUMENTATION BOT                                │
│     Upload your class notes, school policies, textbooks         │
│     → Ask questions about ANY document                          │
│     → Like ChatGPT for your personal knowledge!                 │
│     ⭐ Difficulty: ⭐⭐                                         │
│                                                                  │
│  🍳 PROJECT 3: RECIPE BOT                                       │
│     Store 100 recipes in ChromaDB                               │
│     → "What can I make with eggs and flour?"                    │
│     → "Find vegetarian dinner recipes"                          │
│     ⭐ Difficulty: ⭐⭐                                         │
│                                                                  │
│  🎵 PROJECT 4: MOVIE/MUSIC RECOMMENDER                          │
│     Store your media collection                                 │
│     → "Recommend something like Inception"                      │
│     → "Find happy songs from the 80s"                           │
│     ⭐ Difficulty: ⭐⭐⭐                                        │
│                                                                  │
│  🌍 PROJECT 5: MULTI-LANGUAGE ASSISTANT                         │
│     Translate the chat interface                                │
│     → "Hablas español?" — AI responds in Spanish!               │
│     ⭐ Difficulty: ⭐⭐⭐                                        │
│                                                                  │
│  🗣️ PROJECT 6: VOICE ASSISTANT                                  │
│     Add speech-to-text and text-to-speech                       │
│     → Talk to your AI assistant out loud!                       │
│     ⭐ Difficulty: ⭐⭐⭐⭐                                       │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📚 **Resources to Continue Learning**

```
FREE RESOURCES TO LEARN MORE:
══════════════════════════════

📖 PYTHON (Code your own apps)
   • https://python.org — Official Python tutorial
   • https://codecademy.com — Interactive Python course
   • https://freecodecamp.org — Full Python certification

🤖 AI & LLMs (Understand the brain)
   • https://openrouter.ai/docs — Our AI provider's docs
   • https://platform.openai.com/docs — How ChatGPT works
   • https://lmsys.org — Compare AI models

🔍 RAG & VECTORS (Smart search)
   • https://docs.trychroma.com — ChromaDB documentation
   • https://sbert.net — Sentence transformers explained
   • https://pinecone.io/learn — Vector database guide

🌐 WEB DEVELOPMENT (Build interfaces)
   • https://fastapi.tiangolo.com — Our API framework
   • https://developer.mozilla.org — HTML/CSS/JS reference
   • https://w3schools.com — Beginner web tutorials

💼 CAREER (Turn skills into jobs)
   • Build projects → Put on GitHub → Add to resume
   • AI skills are the MOST in-demand in tech!
   • Entry-level AI roles: $70-120k/year
```

---

## 🗣️ **Final Reflection — Pair & Share**

### *Turn to a partner. You have 60 seconds each:*

```
"Explain why you think conversational AI 
will change how we shop."

🗣️ Your turn (60 seconds):
────────────────────────────
Key points to cover:
• How many clicks we counted earlier
• The cart abandonment statistics
• How our AI assistant works (API → RAG → AI)
• What you'll build next

🤝 Listen to your partner:
────────────────────────────
New idea they mentioned that you liked:
_________________________________________________________

💡 Class Discussion:
Do you AGREE that conversational AI is the future?
  [ ] YES — why? ____________________________________
  [ ] MAYBE — what concerns you? _____________________
  [ ] I need to learn more
```

---

## 🏁 **Final Message**

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║                                                              ║
║     🎉🎉🎉  CONGRATULATIONS!  🎉🎉🎉                        ║
║                                                              ║
║                                                              ║
║     You started the day not knowing how to code.            ║
║     You're ending the day having built an AI.               ║
║                                                              ║
║     THAT'S AMAZING! 🚀                                      ║
║                                                              ║
║     Remember:                                                ║
║                                                              ║
║     💬 The future of shopping is CONVERSATION               ║
║     🤖 The future of work is AI-ASSISTED                    ║
║     🎯 YOU ARE PART OF THIS FUTURE                          ║
║                                                              ║
║     Keep building. Keep learning. Keep growing.             ║
║                                                              ║
║     The 🧃 Juice Shop AI Assistant was just the             ║
║     beginning of YOUR journey!                               ║
║                                                              ║
║                                                              ║
║                   🚀 GO BUILD! 🚀                            ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 📝 **Lesson 9 Summary**

```
┌────────────────────────────────────────────┐
│           ✅ COMPLETION CHECKLIST           │
│                                            │
│  [ ] Watched the final demo               │
│  [ ] Compared old vs new approach         │
│  [ ] Remembered the 3 key concepts:       │
│      • API = Waiter                       │
│      • Vectors = AI fingerprints          │
│      • RAG = Open book exam               │
│  [ ] Participated in Pair & Share         │
│  [ ] AGREE: Conversational AI is future   │
│  [ ] Picked a project to try next         │
│  [ ] Saved resources for learning more   │
│                                            │
│  🎉 COURSE COMPLETE!                       │
│                                            │
│  Screenshot your working AI assistant!    │
│  Share it with friends:                    │
│  "I built an AI today!" 🚀                │
└────────────────────────────────────────────┘
```

---

> **🧃 Thank you for learning with us! You're now part of the conversational commerce revolution. Happy building! 🚀🌟**

---

## 🎙️ **APPENDIX: Instructor Guide & Teaching Tips**

### ⏱️ Suggested Schedule

| Lesson | Topic | Duration | Type |
|--------|-------|----------|------|
| 1 | GitHub Account Setup | 20 min | 🖱️ Hands-on |
| 2 | Project Requirements (PRD) | 20 min | 📝 Write docs |
| 3 | Codespaces & Tools | 30 min | ☁️ Setup |
| 4 | Launch Juice Shop | 30 min | 🧃 Explore |
| 5 | Pain Points Analysis | 20 min | 💬 Discussion |
| 6 | AI Chatbot Brain | 40 min | 🤖 Code |
| 7 | RAG Knowledge System | 40 min | 🔍 Code |
| 8 | Connect Everything | 40 min | 🚀 Build |
| 9 | Final Demo & Future | 30 min | 🎉 Wrap-up |
| **Total** | | **~4.5 hours** | |

### 🗣️ Key Analogies to Use

| Concept | Analogy |
|---------|---------|
| API | Waiter in a restaurant 🍽️ |
| Repo | Project folder on the cloud ☁️ |
| Codespace | Gaming PC in browser 🎮 |
| Vector | AI fingerprint 🖐️ |
| ChromaDB | Fingerprint database 👮 |
| RAG | Open book exam 📖 |
| npm install | Shopping for tools 🛍️ |
| Docker | Shipping containers 📦 |
| System Prompt | AI's job description 📋 |
| Token | AI's counting beads 🔢 |

### 🐛 Common Student Issues

| Problem | Cause | Fix |
|---------|-------|-----|
| `git clone` fails | No internet | Check WiFi |
| `npm install` fails | Missing Node.js | `node --version` |
| Port 3000 in use | Already running | `pkill node` |
| ChromaDB connection | Docker not running | `docker ps` |
| API key error | Wrong key | Check `.env.openai` |
| `uv` not found | PATH missing | `export PATH="$HOME/.local/bin:$PATH"` |

### 🎯 Discussion Questions

1. "What other websites would benefit from a chatbot?"
2. "How would you improve the Juice Shop navigation?"
3. "What products would YOUR dream store sell?"
4. "Can you think of a time AI helped you shop?"
5. "What other uses can you imagine for RAG?"

### 📸 Photo Ops

Have students take screenshots of:
1. Their GitHub repo page
2. Juice Shop running at localhost:3000
3. The AI answering a question in the chat UI
4. Their final working system

> These make great portfolio pieces for resumes!

---

> **🧃 Instructor: Remember — the goal is CONFIDENCE. Even if code doesn't work perfectly, students should leave knowing THEY CAN BUILD. That's the real win! 🎉**
