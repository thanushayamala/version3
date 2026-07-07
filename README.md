# 🚀 Personal Task Manager

A modern, AI-assisted, full-stack personal productivity application built to help individuals quickly capture, organize, and complete tasks without the complexity of traditional project management tools.

> **Philosophy:** Fast capture. Clear priorities. Zero unnecessary friction.

---

# 📖 Overview

People often manage their work using sticky notes, scattered apps, or memory. This project solves that problem by providing a lightweight task management system focused on a single user.

Instead of recreating a large project management platform, this application focuses on making task capture effortless while still providing enough organization to remain productive.

The application was designed with scalability, clean architecture, and extensibility in mind.

---

# ✨ Features

## ✅ Core (MVP)

* Create tasks instantly
* View all tasks
* Edit tasks inline
* Delete tasks
* Mark tasks as Complete / Incomplete
* Persistent storage
* Fast keyboard-first task creation

---

## 📅 Task Management

* Due dates
* Overdue task highlighting
* Automatic due-date sorting
* Task priorities
* Tags for organization
* Real-time filtering

Filters include:

* All
* Active
* Completed

---

## 🎯 Goals

The application separates long-term planning from daily execution.

### Weekly Goals

* Create weekly objectives
* Associate tasks with goals
* Automatic progress tracking

Example:

2 / 5 tasks completed

---

### Monthly Goals

Separate section for larger objectives.

Each goal automatically updates its completion percentage based on linked tasks.

---

## 🤖 Natural Language Task Capture

Supports intelligent task creation such as:

> "Call dentist Friday 3pm"

which can automatically become

* Task title
* Due date
* Time

The architecture also supports future LLM-based parsing.

---

# 🏗 Architecture

Frontend

* HTML5
* CSS3
* JavaScript (ES6)

Backend

* Supabase

Database

* PostgreSQL (via Supabase)

Deployment

* Static deployment
* Cloud hosted

---

# ⚙ Tech Stack

| Layer          | Technology                          |
| -------------- | ----------------------------------- |
| Frontend       | HTML, CSS, JavaScript               |
| Backend        | Supabase                            |
| Database       | PostgreSQL                          |
| Authentication | Ready for Supabase Auth integration |
| Storage        | Supabase Database                   |
| Deployment     | Static Hosting                      |

---

# 🤖 AI-Assisted Development

This project was developed using an AI-assisted workflow while all architectural decisions, feature prioritization, integration, debugging, testing, and final implementation remained under my direction.

Development included collaboration with:

* Claude
* ChatGPT
* Antigravity
* Supabase

AI was used as an engineering productivity tool for:

* brainstorming
* rapid prototyping
* implementation assistance
* debugging
* architecture discussions
* code refinement
* documentation

All final decisions, feature integrations, testing, and system validation were performed manually.

---

# 🧠 Engineering Decisions

Some deliberate product and engineering choices include:

### Fast Task Capture

The application minimizes clicks and interactions to allow users to record tasks quickly.

---

### Optional Goal Linking

Goals are optional instead of mandatory.

Most tasks don't belong to larger objectives, so forcing a relationship would slow down the primary workflow.

---

### Separate Weekly & Monthly Goals

Weekly and monthly goals are displayed independently because they represent different planning horizons.

This improves focus while keeping the interface uncluttered.

---

### Live Progress Calculation

Goal progress is computed dynamically from linked completed tasks rather than storing redundant values.

Benefits:

* no synchronization issues
* always accurate
* simpler data model

---

### Extensible Data Model

Tasks can easily support future additions such as:

* reminders
* recurring schedules
* attachments
* subtasks
* AI-generated suggestions

without requiring major architectural changes.

---

# 📂 Data Model

## Task

```text
id
title
completed
createdAt
dueDate
priority
tags
goalId
```

## Goal

```text
id
title
period (week | month)
createdAt
```

---

# 🚀 Future Improvements

Given additional development time, planned enhancements include:

* User authentication
* Multi-device synchronization
* Push notifications
* Recurring tasks
* Calendar integration
* Drag-and-drop organization
* AI-powered task prioritization
* AI-generated productivity insights
* Voice task capture
* Mobile application
* Offline-first synchronization
* Collaborative task sharing

---

# 📈 Project Highlights

* Full CRUD operations
* Persistent backend storage
* Goal management
* Dynamic filtering
* Intelligent sorting
* Natural language task architecture
* Responsive UI
* Modular JavaScript architecture
* Production-ready backend integration

---

# 💡 What I Learned

This project strengthened my understanding of:

* Product thinking
* UI/UX trade-offs
* Backend integration
* Database design
* State management
* CRUD architecture
* AI-assisted software engineering
* Feature prioritization
* End-to-end application development

---

# 🛠 Getting Started

Clone the repository

```bash
git clone <repository-url>
```

Install dependencies (if applicable)

```bash
npm install
```

Configure Supabase credentials.

Run the application.

---

# 📄 License

This project is available under the MIT License.

---

# 👨‍💻 Developer

Designed, architected, integrated, tested, and delivered by **Thanusha Yamala**.

I believe modern software engineering is not about writing every line manually—it is about making sound architectural decisions, selecting the right tools, integrating systems effectively, debugging rigorously, and delivering reliable software. This project reflects that engineering approach by combining thoughtful product design with AI-assisted development to build a complete, end-to-end application.
