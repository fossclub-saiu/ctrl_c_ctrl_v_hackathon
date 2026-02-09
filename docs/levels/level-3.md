# Level 3: Third Year Students

**Focus:** Real-time features, external API integration, security, complex system design, and advanced NLP/ML.

## Technical Milestones

- [x] Real-time communication (WebSockets)
- [x] Security implementation
- [x] Advanced NLP/ML integration
- [x] Scalable architecture
- [x] External API integration
- [x] Background processing
- [x] Complex multi-module systems

---

## Problem Statement 3.1: Secure Real-Time Campus Chat & Collaboration Platform

**Category:** Communication + Security

### Problem Description
Build a Slack-like real-time collaboration platform for campus use with intelligent content moderation and sensitive data protection.

### Core Features

| Feature | Description |
|---------|-------------|
| 💬 Real-time messaging | WebSocket/Socket.io implementation |
| 👥 User authentication | Session management |
| 🗂️ Channel organization | Departments, clubs, courses, projects |
| 👤 Chat types | One-on-one and group chat |
| 📁 File sharing | With security scanning |
| 🔒 PII detection | Phone numbers, emails, Aadhaar, credit cards, addresses |
| 🤖 Auto-sanitization | Warning before sending sensitive data |
| 🚫 Content moderation | Profanity and hate speech detection |
| 🔐 Encryption | Message encryption in transit |
| 📜 Message history | With search |
| 🟢 Status | Online/offline indicators |
| ✅ Read receipts | Message delivery confirmation |
| 📌 Pin messages | Important message highlighting |
| 🔔 Notifications | Customizable alerts |

### Technical Requirements

- WebSocket server implementation
- Encryption implementation (at least in-transit)
- NLP for content detection (regex + ML)
- Real-time communication protocol
- Database for message persistence
- Security best practices
- Rate limiting and spam prevention

### Advanced Features

- End-to-end encryption
- Voice/video call integration
- Screen sharing
- Self-destructing messages
- Admin moderation dashboard
- Message reactions and threads
- Code syntax highlighting
- Markdown support

### Expected Deliverables

- Functional real-time chat system
- Working PII detection and masking
- Minimum 5 channels with 20+ users
- Message search functionality
- File sharing capability

### Bonus Features

- AI-powered message summarization
- Smart reply suggestions
- Language translation
- Mobile app version
- Offline message queue
- Message editing and deletion
- Bot integration framework

---

## Problem Statement 3.2: URL Safety Analyzer & Phishing Awareness Tool

**Category:** Security + ML

### Problem Description
Phishing attacks are increasingly sophisticated. Build a comprehensive URL safety analyzer that evaluates links using multiple detection techniques and educates users about online safety.

### Core Features

| Feature | Description |
|---------|-------------|
| 🔗 URL submission | Analysis interface |
| 🔍 Pattern-based analysis | URL structure, keywords, domain age, HTTPS, complexity, homograph detection |
| 🤖 ML classification | Feature extraction, phishing prediction, confidence scoring |
| 🌐 Network validation | DNS lookup, WHOIS info, SSL verification, IP geolocation |
| 📋 Blacklist checking | Known phishing databases, Google Safe Browsing API |
| 📊 Risk scoring | 0-100 with detailed explanation |
| 📸 Visual detection | Screenshot comparison for spoofed websites |
| 📧 Email analyzer | Suspicious language, urgency detection, sender verification |
| 🎓 Educational tips | Based on detected risks |
| 📋 Reporting system | User reporting for new threats |

### Technical Requirements

- ML model training (use PhishTank, OpenPhish datasets)
- Feature extraction algorithms
- External API integration (VirusTotal, Google Safe Browsing, WHOIS)
- NLP for email content analysis
- Image comparison algorithms
- Database for threat intelligence

### Advanced Features

- Real-time protection browser extension
- Chrome/Firefox extension
- Automated threat database updates
- Historical threat analysis
- API for third-party integration
- Phishing simulation tool for training

### Expected Deliverables

- Functional URL analyzer with risk scoring
- Working ML-based detection (minimum 80% accuracy on test set)
- Integration with at least 2 external APIs
- Educational component with safety tips
- Detailed risk report generation

### Bonus Features

- Browser extension with real-time protection
- Email attachment scanner
- QR code safety checker
- Bulk URL analysis
- Threat intelligence dashboard
- Monthly security newsletter generator

---

## Problem Statement 3.3: AI-Powered Placement Preparation & Interview Tracker

**Category:** Career + AI

### Problem Description
Placement preparation is scattered across multiple platforms and resources. Build a comprehensive platform that combines application tracking, interview preparation, shared experiences, and AI-powered mock interviews.

### Core Features

#### 📋 Application Tracker

| Feature | Description |
|---------|-------------|
| Status tracking | Applied, OA, interview, offer, rejected |
| Timeline visualization | Visual progress |
| Document management | Resume versions, cover letters |
| Deadline tracking | Important dates |
| Notes & reminders | Follow-up tracking |

#### 💼 Interview Experience Database

| Feature | Description |
|---------|-------------|
| Shared experiences | Student submissions |
| Question bank | Company-wise |
| Difficulty ratings | Easy to hard |
| Round breakdown | Interview stages |
| Voting system | Upvote/downvote |
| Search & filter | By company, role, difficulty |

#### 🤖 AI Mock Interview System

| Type | Features |
|------|----------|
| Technical Interviews | Coding problems, real-time evaluation, hints, solution discussion |
| HR/Behavioral | AI-driven questions, answer evaluation, STAR method guidance |
| Video Analysis (Optional) | Speech clarity, filler words, pace analysis |

#### 📚 Preparation Resources

- Company-specific preparation guides
- Topic-wise study materials
- DSA roadmap
- System design resources

#### 📊 Analytics Dashboard

- Progress tracking
- Strengths and weaknesses
- Time spent per topic
- Mock interview performance trends

### Technical Requirements

- Complex database schema
- AI API integration for interview simulation
- Code execution sandbox (Docker/online judge API)
- Real-time code evaluation
- NLP for answer assessment
- Data visualization
- Optional: Speech-to-text for video analysis

### Advanced Features

- Peer mock interview matching
- Salary predictor based on skills and company
- Company culture fit analyzer
- Resume-JD match percentage
- Automated job application from tracker

### Expected Deliverables

- Functional application tracker with 10+ sample applications
- Interview experience database with 20+ entries
- Working AI mock interview system (both technical and HR)
- Code execution for at least Python and Java
- Analytics dashboard

### Bonus Features

- Integration with LinkedIn/job portals
- Automated job aggregation
- Chrome extension for quick experience posting
- Mobile app for on-the-go tracking
- Offer comparison tool
- Negotiation tips based on offer data

---

## Problem Statement 3.4: Automated Document & Certificate Generator

**Category:** Automation + Utility

### Problem Description
Generating hundreds of personalized certificates, ID cards, or letters manually is time-consuming and error-prone. Build a bulk document generator with template support, QR verification, and background processing.

### Core Features

#### 📄 Template Management

| Feature | Description |
|---------|-------------|
| Custom templates | Upload PDF, DOCX, images |
| Visual editor | Drag-and-drop |
| Placeholder system | `{{name}}`, `{{date}}`, etc. |
| Multiple types | Certificates, ID cards, letters |

#### 📊 Bulk Data Input

| Feature | Description |
|---------|-------------|
| CSV/Excel upload | With data validation |
| Manual entry | Alternative interface |
| Data preview | Before generation |

#### 🎨 Document Generation

| Feature | Description |
|---------|-------------|
| Merge data | With templates |
| Generate PDFs | Personalized documents |
| Background processing | For 100+ documents |
| Progress tracking | Real-time status |

#### 📱 QR Code Integration

| Feature | Description |
|---------|-------------|
| Unique QR codes | Per document |
| Verification system | QR-based authenticity check |
| Public portal | Scan to verify |

#### 📧 Distribution

| Feature | Description |
|---------|-------------|
| Email distribution | Automated sending |
| Batch download | ZIP file |
| Individual links | Download links |

#### 🔐 Security

| Feature | Description |
|---------|-------------|
| Tampering prevention | Document integrity |
| Digital signature | Support |
| Verification database | Records |

### Technical Requirements

- PDF generation and manipulation
- QR code generation and scanning
- Background job processing (Celery, Bull, etc.)
- Template parsing engine
- Bulk email system
- Database for verification records

### Advanced Features

- Google Drive integration for storage
- WhatsApp distribution
- Multi-language support
- Version control for templates
- Analytics (generated count, verification count)

### Expected Deliverables

- Functional bulk generator with 2+ template types
- QR verification system
- Background processing for 100+ documents
- Email distribution working
- Public verification portal

### Bonus Features

- Blockchain-based verification
- Mobile app for QR scanning
- Template marketplace
- AI-powered content suggestions
- Watermark support
- Batch editing interface

---

## Problem Statement 3.5: Multi-Source Campus Announcement Aggregator

**Category:** Utility + AI + Web Scraping

### Problem Description
Campus announcements are scattered across websites, social media, and multiple platforms. Build an intelligent aggregator that scrapes data from various sources and creates a unified feed with AI-generated summaries.

### Core Features

#### 🌐 Multi-Source Scraping

| Source | Description |
|--------|-------------|
| College website | Official announcements |
| Social media | Instagram, Twitter/X, Facebook |
| Email | College circulars |
| RSS feeds | Feed integration |
| Departments | Specific scraping |

#### 🤖 AI Processing

| Feature | Description |
|---------|-------------|
| Duplicate detection | Across sources |
| Categorization | Academic, event, placement, sports, etc. |
| Daily digest | AI-summarized |
| Sentiment analysis | Tone detection |
| Priority detection | Urgent vs informational |

#### 📱 Unified Feed

| Feature | Description |
|---------|-------------|
| Multiple views | Chronological and category-wise |
| Search & filter | Find specific announcements |
| Bookmarks | Save for later |
| Sharing | Share announcements |

#### 🔔 Smart Notifications

| Feature | Description |
|---------|-------------|
| Personalized | Based on year/department |
| Keyword alerts | Custom triggers |
| Daily summary | Email digest |

#### 📊 Analytics

| Feature | Description |
|---------|-------------|
| Source contribution | Which sources post most |
| Category trends | Popular topics |
| Engagement metrics | User interaction |

### Technical Requirements

- Web scraping (BeautifulSoup, Scrapy, Playwright)
- API integration for social media
- NLP for content processing
- AI API for summarization
- Background scheduling (cron jobs)
- Duplicate detection algorithms
- Database for storing announcements

### Advanced Features

- Image and video processing
- OCR for image-based announcements
- Multi-language support
- Mobile app with push notifications
- Chrome extension
- Webhook support for instant updates

### Expected Deliverables

- Working scraper for at least 3 sources
- Unified feed interface
- AI-generated daily digest
- Duplicate detection system
- Categorization working
- Minimum 50 sample announcements

### Bonus Features

- Real-time scraping with WebSocket updates
- Announcement prediction (based on patterns)
- Integration with calendar apps
- Voice announcement feature
- Accessibility features (text-to-speech)
- Admin moderation panel

---

## Problem Statement 3.6: Open Innovation (Level 3)

**Category:** Free Choice

### Description
Propose and build an advanced system demonstrating complex system design, real-time features, or sophisticated integrations. This should be a production-grade solution addressing a significant problem.

### Requirements

- [x] Must involve advanced technical concepts (real-time, ML/NLP, security, etc.)
- [x] Should include background processing or complex integrations
- [x] Must demonstrate scalable architecture
- [x] Should have comprehensive documentation
- [x] Must address a real, significant problem

### Evaluation Focus

| Criteria | What We Look For |
|----------|-----------------|
| Technical sophistication | Advanced concepts properly implemented |
| System architecture | Scalable, well-designed |
| Scalability & performance | Can handle real-world load |
| Innovation & uniqueness | Novel approach |
| Production-readiness | Could be deployed today |
| Real-world impact | Solves a significant problem |

!!! success "Bonus Points"
    - Deployed/hosted application: **+5%**
    - Comprehensive test coverage: **+5%**
    - API documentation (Swagger/Postman): **+3%**
    - CI/CD pipeline: **+3%**
    - Exceptional UI/UX: **+5%**

!!! danger "Penalties"
    - Security vulnerabilities (SQL injection, XSS, etc.): **-15%**
    - No error handling: **-10%**
    - Hardcoded credentials: **-10%**
    - Copied code without attribution: **-20%**
