# Level 1: First Year Students

**Focus:** Building functional, complete apps with clean UI and basic data flow.

## Technical Milestones

- [x] CRUD operations (Create, Read, Update, Delete)
- [x] Basic API integration
- [x] Simple database usage
- [x] Responsive user interface
- [x] Form validation and error handling

---

## Problem Statement 1.1: Mental Health Check-In & Wellness Tracker

**Category:** Health & Wellness

### Problem Description
College life can be overwhelming, and students often struggle to track their mental wellness. Build a supportive application that helps students monitor their daily mood, stress levels, and sleep patterns to develop better self-awareness.

### Core Features

| Feature | Description |
|---------|-------------|
| 📊 Daily mood check-in | Emoji/scale selection (1-10) |
| 💭 Journal entry | Optional notes for each day |
| 😴 Sleep tracking | Hours slept |
| 📈 Stress level logging | Daily stress ratings |
| 🔥 Mood streak tracking | Consecutive days logged |
| 📉 Trend visualizations | Line/bar charts for weekly/monthly patterns |
| 🎯 Wellness suggestions | Activity suggestions based on mood patterns |
| 🆘 Emergency resources | Counselor contacts, helplines |

### Technical Requirements

- Data persistence (store mood history)
- Date/time handling
- Data visualization library (Chart.js, Matplotlib, Plotly, etc.)
- Clean, intuitive UI

### Expected Deliverables

- Functional web/mobile app
- Minimum 7-day mood tracking demonstration
- At least 3 visualization types

### Bonus Features

- Weekly wellness summary/report
- Reminder notifications for daily check-ins
- Export mood data as PDF/CSV
- Dark mode

---

## Problem Statement 1.2: Campus Event Discovery & Registration Platform

**Category:** College Utility

### Problem Description
Students often miss out on campus events due to poor communication and scattered information. Create a centralized platform where students can discover events, register for them, and organizers can manage attendees.

### Core Features

| Feature | Description |
|---------|-------------|
| 📅 Event listing | Title, description, date, time, venue, organizer |
| 🔍 Browse and filter | By category, date, department |
| ✅ Event registration | RSVP system |
| 👥 Attendee management | List management for organizers |
| 🔔 Event reminders | Email/notification |
| 📊 Organizer dashboard | Registration count display |
| 🔎 Search functionality | Find events quickly |
| 🏷️ Event categories | Cultural, technical, sports, academic, etc. |

### Technical Requirements

- User authentication (students and organizers)
- Role-based access (organizer vs attendee)
- Email/notification system
- Calendar integration or visualization
- CRUD operations for events

### Expected Deliverables

- Functional platform with at least 2 user roles
- Minimum 10 sample events populated
- Working registration flow

### Bonus Features

- QR code generation for event check-in
- Google Calendar export
- Event capacity limits
- Waitlist for full events
- Event analytics for organizers

---

## Problem Statement 1.3: Study Buddy Finder & Session Planner

**Category:** Education

### Problem Description
Students often struggle to find compatible study partners. Build a platform that matches students based on subjects, schedules, and study preferences, then helps them plan study sessions together.

### Core Features

| Feature | Description |
|---------|-------------|
| 👤 Student profile | Name, year, subjects, study preferences, available time slots |
| 🔍 Search and filter | By subject and availability |
| 🤝 Connection system | Buddy request system |
| 📅 Session scheduling | Time/location planning |
| 💬 Simple messaging | Coordination between buddies |
| ⏰ Time overlap calculator | Shows common free hours |
| ⭐ Rating system | Rate study partners |
| 📚 Recommendations | Subject-wise buddy suggestions |

### Technical Requirements

- Profile management system
- Matching/filtering logic
- Time slot comparison algorithm
- Basic messaging or notification system
- Database relationships (users, sessions, subjects)

### Expected Deliverables

- Functional matching system
- At least 15 sample student profiles
- Working session planner

### Bonus Features

- Group study room creation (3+ people)
- Study session history
- Study goal tracking
- Integration with class timetables
- Study habit badges/achievements

---

## Problem Statement 1.4: Digital Lost & Found Portal

**Category:** College Utility

### Problem Description
Lost items on campus are hard to track and recover. Create a centralized portal where students can report lost items and claim found items with proper verification.

### Core Features

| Feature | Description |
|---------|-------------|
| 📝 Report lost items | Description, category, location, date, photo |
| 📝 Report found items | Similar fields |
| 🔍 Search and filter | Category, location, date range |
| 🎯 Smart matching | Keyword similarity between lost/found descriptions |
| 📧 Contact system | Email/phone reveal for matches |
| ✅ Item status tracking | Unclaimed/claimed/resolved |
| 🖼️ Image upload | For items |
| 🏷️ Category tags | Electronics, books, accessories, etc. |

### Technical Requirements

- Image upload and storage
- Text similarity/matching algorithm
- Search and filter logic
- Notification system for potential matches
- Database design with proper relationships

### Expected Deliverables

- Functional portal with lost and found listings
- Minimum 20 sample items
- Working matching algorithm

### Bonus Features

- Admin verification before claiming
- Auto-archive items after 60 days
- Location-based clustering on campus map
- Multiple image upload per item
- False claim prevention mechanism

---

## Problem Statement 1.5: Personal Expense Tracker & Budget Planner

**Category:** Finance & Utility

### Problem Description
Students living away from home often struggle with budget management. Build a simple expense tracking app that helps students log expenses and stick to monthly budgets.

### Core Features

| Feature | Description |
|---------|-------------|
| 💰 Expense logging | Amount, category, date, description |
| 📊 Category breakdown | Food, transport, shopping, etc. |
| 🎯 Monthly budgets | Budget setting per category |
| 📈 Spending visualization | Pie charts, bar graphs |
| ⚠️ Budget warnings | Alert when nearing limits |
| 📅 Monthly reports | Expense summaries |
| 💳 Income tracking | Track money coming in |
| 🔍 Search and filter | Find specific expenses |

### Technical Requirements

- CRUD operations for expenses
- Data visualization
- Date range calculations
- Budget vs actual comparison logic
- Data persistence

### Expected Deliverables

- Functional expense tracker
- Minimum 30 sample transactions
- At least 3 visualization types

### Bonus Features

- Recurring expense support
- Export to CSV/PDF
- Expense trends and insights
- Savings goal tracker
- Multi-currency support
- Receipt image upload

---

## Problem Statement 1.6: Open Innovation (Level 1)

**Category:** Free Choice

### Description
Propose and build your own solution that addresses a real student life problem. Your project should demonstrate understanding of basic app development, data flow, and user interface design.

### Requirements

- [x] Must solve a clearly defined problem
- [x] Should have proper input and output flow
- [x] Must use a database for persistence
- [x] Should have a clean, functional UI
- [x] Must be achievable within 24 hours

### Evaluation Focus

| Criteria | What We Look For |
|----------|-----------------|
| Problem clarity | Is the problem well-defined and relevant? |
| Completeness | Are all core features implemented? |
| Code quality | Is the code clean and readable? |
| User experience | Is the app intuitive and easy to use? |

!!! tip "Choosing Your Problem"
    Think about daily challenges you face as a student. What app would make your life easier? Start small and build something useful!
