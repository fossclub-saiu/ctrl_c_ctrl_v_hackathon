# Level 2: Second Year Students

**Focus:** Multi-module applications, proper database design, role-based access, and basic AI/ML integration.

## Technical Milestones

- [x] Complex database schemas with relationships
- [x] API development and consumption
- [x] User authentication and authorization
- [x] AI API integration
- [x] Data analytics and visualization
- [x] Workflow management

---

## Problem Statement 2.1: Academic Planner & Deadline Tracker

**Category:** Education + AI

### Problem Description
Students juggle multiple courses, assignments, and exams without a unified system. Build an intelligent academic planner that centralizes all academic commitments and provides smart scheduling assistance.

### Core Features

| Feature | Description |
|---------|-------------|
| 📚 Course management | Add courses with credits, timings, venue, professor |
| 📝 Deadline tracker | Assignment and exam deadlines with priority levels |
| 📅 Calendar view | Weekly/monthly with color coding |
| ⏰ Smart reminders | Based on deadline urgency |
| 📊 Workload heatmap | Visual representation of busy vs free days |
| 🆓 Free slot identifier | Find available time in daily schedule |
| 🤖 AI study plan generator | Suggests study sessions in free slots |
| ⚡ Conflict detection | Alert for overlapping events |
| 📈 Progress tracker | Semester progress monitoring |

### Technical Requirements

- Complex database design (courses, assignments, exams, schedules)
- Time slot management algorithms
- AI API integration for study plan suggestions
- Calendar data structure and visualization
- Conflict detection logic
- Notification system

### Advanced Features

- AI syllabus parsing (upload PDF, auto-extract topics and deadlines)
- What-if scenario analysis for grade prediction
- Google Calendar synchronization
- Collaborative scheduling (find common free slots with friends)

### Expected Deliverables

- Functional planner with at least 5 courses
- Working AI study plan generation
- Minimum 15 sample assignments/deadlines
- Conflict detection demonstration

### Bonus Features

- Pomodoro timer integration
- Productivity analytics dashboard
- Smart deadline prioritization algorithm
- Integration with LMS
- Mobile app version

---

## Problem Statement 2.2: AI-Enhanced Resume & Portfolio Builder

**Category:** Career + AI

### Problem Description
Students struggle to create professional resumes that pass ATS (Applicant Tracking Systems) and showcase their skills effectively. Build a comprehensive tool that generates ATS-friendly resumes and shareable portfolio links with AI-powered content optimization.

### Core Features

| Feature | Description |
|---------|-------------|
| 📄 Resume builder | Multiple professional templates |
| ✏️ Section-wise input | Personal info, education, experience, projects, skills, certifications |
| 🤖 AI content enhancement | Improve bullet points, suggest action verbs, optimize phrasing |
| ✅ ATS checker | Keyword analysis, format validation |
| 📊 Resume scoring | Rate resume quality |
| 💼 Cover letter generator | Based on job description + resume |
| 🔗 Portfolio website | Shareable portfolio link |
| 📱 Version management | Multiple resume versions |
| 📥 PDF export | Clean formatting |

### Technical Requirements

- AI API integration with well-crafted prompts
- PDF generation library
- Template system with responsive design
- ATS keyword extraction algorithm
- Version control for resumes
- Web hosting for portfolio links

### Advanced Features

- Job description analyzer (identifies required skills, suggests tweaks)
- Skill gap identification
- LinkedIn profile import
- Real-time ATS score as you type
- LaTeX template support

### Expected Deliverables

- Functional resume builder with 3+ templates
- Working AI content improvement
- ATS checker with score
- Shareable portfolio link

### Bonus Features

- Batch resume generation (different versions for different roles)
- Resume comparison tool
- Interview question predictor based on resume
- Salary estimator based on skills
- Export to JSON/YAML for developers

---

## Problem Statement 2.3: Campus Resource Booking & Utilization Dashboard

**Category:** College Utility

### Problem Description
Campus facilities like seminar halls, sports courts, and labs are often double-booked or underutilized. Create a centralized booking system with conflict prevention and usage analytics for administrators.

### Core Features

| Feature | Description |
|---------|-------------|
| 🏢 Resource catalog | Rooms, courts, labs, equipment with details, capacity, photos |
| 📅 Availability calendar | Real-time hourly/half-hourly time slots |
| ✅ Conflict-free booking | Prevents double-booking |
| 👤 User authentication | Role-based access (student, faculty, admin) |
| 📋 Approval workflow | Auto-approve or admin approval based on resource |
| ✏️ Booking management | Modification and cancellation with rules |
| 📧 Confirmations | Email/SMS confirmations and reminders |
| 📊 Admin dashboard | Peak hours, idle time, most/least booked, department usage |
| 🚫 No-show tracking | Track and penalize no-shows |

### Technical Requirements

- Time slot management algorithm
- Booking conflict prevention logic
- Role-based access control (RBAC)
- Email/notification system
- Analytics calculation and visualization
- Complex database schema

### Advanced Features

- Recurring booking support (e.g., weekly lab sessions)
- Waitlist management for fully booked slots
- QR code-based check-in system
- Mobile app for quick bookings
- Resource dependency (e.g., book projector with room)

### Expected Deliverables

- Functional booking system with 10+ resources
- Working conflict detection
- Admin dashboard with analytics
- Minimum 3 user roles implemented

### Bonus Features

- Predictive analytics (suggest best booking times)
- Integration with college calendar
- Automatic cancellation for no-shows
- Usage reports (PDF export)
- Resource maintenance scheduling

---

## Problem Statement 2.4: Smart Campus Store Inventory & Expiry Tracker

**Category:** Utility + ML

### Problem Description
Campus stores (stationery, mess, bookshops) face stock management challenges and wastage due to expiry. Build an intelligent inventory system with expiry tracking, low-stock alerts, and demand prediction.

### Core Features

| Feature | Description |
|---------|-------------|
| 📦 Item catalog | Name, category, quantity, price, expiry date |
| 🚨 Expiry monitoring | Color-coded alerts (🔴 7 days, 🟡 15 days, 🟢 Fresh) |
| 📉 Low-stock notifications | Automatic alerts |
| 🔔 Reorder suggestions | Based on consumption patterns |
| 📊 Consumption analytics | Category-wise breakdown |
| 📈 Trend visualization | Daily/weekly/monthly sales |
| 💰 Revenue tracking | Track income |
| 🛒 Sales input interface | Record consumption data |
| 📋 Admin dashboard | Inventory insights |

### Technical Requirements

- Database design for inventory management
- Date calculations for expiry tracking
- Analytics and reporting
- Data visualization
- Alert/notification system
- Optional: Basic ML for demand prediction

### Advanced Features

- Stock prediction using time-series analysis
- Barcode scanning for quick updates
- Supplier management
- Purchase order generation
- Seasonal pattern detection
- Mobile app for stock updates

### Expected Deliverables

- Functional inventory system with 50+ items
- Working expiry tracking with alerts
- Consumption analytics dashboard
- Low-stock notification system

### Bonus Features

- ML-based reorder point optimization
- Wastage reports (expired items)
- Multi-store support
- Integration with POS system
- Batch tracking (multiple batches per item)

---

## Problem Statement 2.5: Digital Circular & Notice Management Platform

**Category:** College Utility

### Problem Description
Important college announcements and circulars often get lost in email clutter or WhatsApp groups. Build a targeted announcement platform where admins can track engagement and ensure important information reaches the right audience.

### Core Features

| Feature | Description |
|---------|-------------|
| 📢 Circular creation | Rich text editor |
| 🎯 Targeted distribution | By department, year, role, groups/clubs |
| ✅ Read tracking | Who has read, who hasn't |
| 📱 Push notifications | Instant alerts |
| 🏷️ Priority tagging | Urgent, informational, action-required |
| 📁 Searchable archive | Past notices |
| 📊 Analytics dashboard | Reach %, read rate, time to read, engagement |
| 📎 Attachments | PDFs, images support |
| 💬 Comment section | Feedback area |

### Technical Requirements

- Role-based access control (admin, user)
- Notification system (email, push, in-app)
- Full-text search implementation
- Read tracking mechanism
- Analytics calculation
- File upload and storage

### Advanced Features

- Auto-reminder for unread urgent notices
- Scheduled circular publishing
- Translation support for multiple languages
- Integration with college website
- SMS fallback for critical notices

### Expected Deliverables

- Functional platform with admin and user roles
- Minimum 20 sample circulars with different categories
- Working read tracking
- Analytics dashboard

### Bonus Features

- Digital signature for official circulars
- Version control for circular edits
- Circular templates for common types
- Export to PDF with distribution list
- Mobile app with offline reading

---

## Problem Statement 2.6: Open Innovation (Level 2)

**Category:** Free Choice

### Description
Propose and build an advanced solution requiring meaningful data management, analytics, or AI integration. Your project should demonstrate multi-module thinking and system design capabilities.

### Requirements

- [x] Must involve complex data relationships
- [x] Should include analytics or AI features
- [x] Must have role-based access control
- [x] Should demonstrate proper system architecture
- [x] Must be scalable and well-documented

### Evaluation Focus

| Criteria | What We Look For |
|----------|-----------------|
| System design quality | Is the architecture well thought out? |
| Database schema | Are relationships properly designed? |
| Feature completeness | Are all promised features working? |
| Code architecture | Is the code well organized? |
| Real-world applicability | Can this be used in practice? |

!!! warning "Penalties"
    - Over-reliance on AI-generated code without understanding: **-10%**
    - Poor database design (no normalization, bad relationships): **-10%**
    - Hardcoded values instead of configuration: **-5%**
