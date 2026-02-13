# Judges Guide

Thank you for taking the time to evaluate student submissions for the Ctrl C + Ctrl V Hackathon. We truly appreciate your expertise and guidance in assessing our students' work.

This document provides an overview of the evaluation criteria and suggested workflow to help streamline the remote judging process. Please feel free to adapt the process as you see fit.

---

## Judge Assignments

| Level | Judges | Submissions |
|-------|--------|-------------|
| Level 1 | 3 judges | First year student projects |
| Level 2 & 3 | 3 judges (shared) | Second and third year student projects |

---

## What You'll Receive

Each submission includes:

- **GitHub Repository Link** — Public repo with source code and README
- **5-Minute Video Presentation** — Uploaded to Google Drive

---

## Suggested Evaluation Workflow

### Step 1: Watch the Video (~5 minutes)

Some aspects you may wish to consider:

- Is the problem clearly explained?
- Is there a working demo (not just slides)?
- Are technical decisions justified?
- Is the presentation within the time limit?

!!! tip "Note"
    Students were advised to show working features rather than slides. A functional demo, even if rough, may indicate stronger technical work.

### Step 2: Review the GitHub Repository (~5-10 minutes)

Some areas that may be helpful to review:

| Area | Considerations |
|------|----------------|
| **README** | Project explanation, setup instructions, screenshots |
| **Code Structure** | Organization, meaningful file names |
| **Code Quality** | Readability, comments, handling of sensitive data |
| **Commit History** | Development progression over time |
| **Dependencies** | Proper dependency management (`requirements.txt`, `package.json`, etc.) |

### Step 3: Clone & Test (Optional)

If you would like to verify functionality beyond what the video demonstrates:

1. Clone the repository
2. Follow setup instructions in README
3. Test core features
4. Note any setup issues or bugs

!!! info "Environment Considerations"
    Differences in OS or software versions may occasionally cause setup issues. In such cases, the video demonstration may serve as the primary reference for functionality.

### Step 4: Score Each Criterion

The scoring rubrics below outline the evaluation criteria for each level. These are provided as guidelines to help ensure consistency across evaluations.

---

## Scoring Rubrics

### Level 1: First Year Students

| Criteria | Weight | 1-3 (Poor) | 4-6 (Average) | 7-8 (Good) | 9-10 (Excellent) |
|----------|--------|------------|---------------|------------|------------------|
| **Functionality & Correctness** | 40% | Major features broken | Some features work | Most features work | All features work smoothly |
| **Logic & Code Quality** | 30% | Messy, hard to follow | Basic structure | Clean and readable | Well-organized, good practices |
| **User Interface & Experience** | 15% | Unusable or ugly | Functional but rough | Clean and intuitive | Polished, responsive, delightful |
| **Video Presentation** | 15% | No demo, confusing | Basic explanation | Clear demo and explanation | Engaging, technical depth shown |

### Level 2: Second Year Students

| Criteria | Weight | 1-3 (Poor) | 4-6 (Average) | 7-8 (Good) | 9-10 (Excellent) |
|----------|--------|------------|---------------|------------|------------------|
| **Functionality & Correctness** | 35% | Core broken | Partially working | Stable, most features work | Fully functional, polished |
| **Technical Implementation** | 30% | No DB/API, copy-paste | Basic DB, simple API | Good schema, meaningful AI use | Advanced implementation, clean architecture |
| **Innovation & Features** | 20% | Bare minimum | Met requirements | Extra features added | Creative solutions, exceeded scope |
| **Video Presentation** | 15% | No architecture shown | Basic walkthrough | Good technical explanation | Deep technical dive, clear architecture |

**Level 2 Penalties:**

| Issue | Penalty |
|-------|---------|
| Over-reliance on AI-generated code without understanding | -10% |
| Poor database design (no normalization, bad relationships) | -10% |
| Hardcoded values instead of configuration | -5% |

### Level 3: Third Year Students

| Criteria | Weight | 1-3 (Poor) | 4-6 (Average) | 7-8 (Good) | 9-10 (Excellent) |
|----------|--------|------------|---------------|------------|------------------|
| **Functionality & Correctness** | 30% | Core broken | Basic features work | All features work | Production-ready |
| **Technical Depth** | 30% | Shallow implementation | Standard tech stack | Advanced concepts used | Sophisticated implementation |
| **Scalability & Architecture** | 20% | Monolithic mess | Basic separation | Good architecture | Scalable, well-designed system |
| **Innovation & Impact** | 20% | Cookie-cutter solution | Meets requirements | Novel approaches | Industry-applicable, innovative |

**Level 3 Bonuses:**

| Achievement | Bonus |
|-------------|-------|
| Deployed/hosted application | +5% |
| Comprehensive test coverage | +5% |
| API documentation (Swagger/Postman) | +3% |
| CI/CD pipeline | +3% |
| Exceptional UI/UX | +5% |

**Level 3 Penalties:**

| Issue | Penalty |
|-------|---------|
| No error handling | -10% |
| Hardcoded credentials | -10% |

---

## Calibration (Optional)

If time permits, it may be helpful for judges to:

1. **Review 1-2 sample submissions together** to calibrate expectations
2. **Briefly discuss scoring standards** to ensure consistency
3. **Align on penalty application** if applicable

### Score Interpretation

| Score Range | Meaning |
|-------------|---------|
| 9-10 | Exceptional — Goes well beyond expectations |
| 7-8 | Good — Solid work, meets all requirements well |
| 5-6 | Average — Works but has notable gaps |
| 3-4 | Below Average — Major issues or incomplete |
| 1-2 | Poor — Barely functional or missing core features |

---

## Suggested Judging Process

### For Level 1 (3 judges)

One possible approach:

1. Each judge evaluates approximately one-third of submissions independently
2. Flag top 5-10 submissions for cross-review
3. All judges review the flagged submissions
4. Brief discussion to finalize rankings for top positions

### For Level 2 & 3 (3 judges)

One possible approach:

1. Each judge evaluates all submissions independently
2. Identify any submissions where scores differ significantly
3. Discuss and reach consensus on those cases
4. Final score may be averaged across judges

---

## Scoresheet Template

For each submission, record:

| Field | Entry |
|-------|-------|
| Team Name | |
| Level | |
| GitHub Link | |
| Video Link | |
| Criterion 1 Score | /10 |
| Criterion 2 Score | /10 |
| Criterion 3 Score | /10 |
| Criterion 4 Score | /10 |
| Bonuses Applied | |
| Penalties Applied | |
| **Weighted Total** | /100 |
| Comments | |
| Feedback/Advice for Team | |

---

## Points to Note

!!! danger "Disqualification Criteria"
    The following result in automatic disqualification per hackathon rules:
    
    - Plagiarized code (copied from other teams)
    - Submission after deadline
    - No video or inaccessible video
    - Repository is private/inaccessible

!!! warning "Areas of Concern"
    These may warrant closer examination:
    
    - Single bulk commit (may indicate last-minute work)
    - Video shows features not present in code
    - Over-reliance on AI-generated code without demonstrated understanding
    - Hardcoded API keys or credentials in repository

---

## Final Deliberation

For determining the top teams in each level, we would be grateful if judges could:

1. Participate in a brief video call to discuss finalists
2. Share observations on each top submission
3. Collaboratively finalize rankings
4. Provide brief reasoning for winners (to be used in announcements)

---

## Contact

If you have any questions or need assistance during the judging process, please don't hesitate to reach out to us at `fossclub@saiuniversity.edu.in`.

Thank you once again for your time and support in making this hackathon a success.
