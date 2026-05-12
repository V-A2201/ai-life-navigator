# Data Model

## Tables

### users
- id
- email
- created_at

### goals
- id
- user_id
- title
- description
- status

### habits
- id
- user_id
- name
- frequency

### habit_logs
- id
- habit_id
- date
- completed

### daily_plans
- id
- user_id
- date
- tasks (JSON)

### mood_checkins
- id
- user_id
- mood
- stress
- notes
- timestamp

### global_patterns
- id
- user_id
- pattern_type
- description
- detected_at
