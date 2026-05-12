# Architecture Overview

AI Life Navigator is built entirely inside the MeDo platform, using its:
- Workflow engine
- Database layer
- Auto‑generated UI components
- AI Coach integration

## High-Level Architecture

User → UI Pages → Workflows → Database → AI Coach → Insights

### 1. UI Layer
- Daily Plan page
- Habits page
- Mood Check‑ins page
- Goals page
- Global Insights page
- AI Coach chat interface

### 2. Workflow Layer
Workflows handle:
- CRUD operations
- Daily plan generation
- Weekly summary generation
- Pattern detection
- AI Coach context building

### 3. Database Layer
Tables:
- Users
- Goals
- Habits
- Habit Logs
- Daily Plans
- Mood Check‑ins
- Global Patterns

### 4. AI Layer
The AI Coach uses:
- User history
- Habit logs
- Mood logs
- Goals
- Weekly summaries
- Global patterns

to generate personalized insights.
