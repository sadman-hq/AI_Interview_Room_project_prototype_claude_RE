# AI Interview Room — Full Prototype

An AI-powered interview platform prototype designed for the complete hiring workflow, from candidate interviews to coding rounds and admin evaluation.

## Features

- Candidate login and role selection
- AI-powered interview conversation
- Timed interview and recording interface
- Live coding round with test execution
- Candidate performance report
- Admin dashboard and candidate management
- Scoring weights and evaluation workflow
- Responsive, modern AI-first interface

## Run

Open the HTML file directly in a browser, or host it with GitHub Pages.

> This is a front-end prototype with simulated interactions and evaluation data.

# Page-by-Page High-Fidelity Prototype

This section defines the complete page structure, candidate journey, admin experience, scoring framework, responsive requirements, and prototype flow.

The final prototype should look like a **premium AI-powered hiring platform launching in 2026**.

The experience should communicate:

> Create a bold, original, world-class product experience.

Every page/screen must be separated as an individual high-fidelity Figma frame/artboard while maintaining one consistent design system.

---

## Page 01 — Website AI Interview Room Onboarding Screen

### Overall Layout

- Full-body white background.
- Premium split-screen composition.
- Large amount of whitespace.
- Modern glassmorphism and soft-gradient visual language.
- Primary brand color: `#0F98FF`.

### Left Side

Display:

- **AI ROOM INTERVIEW** title
- Supporting body text
- Company Name
- Company Logo

The left side can contain an editable background design related to AI, interviews, intelligent recruitment, or communication.

Possible visual direction:

- Abstract AI geometry
- Fluid shapes
- Neural-network-inspired patterns
- Soft particles
- Linear gradients
- Glass effects
- Abstract interview-related visual elements

The primary color `#0F98FF` should be incorporated into the background treatment.

The background must remain easy to edit in Figma.

### Right Side

Center the authentication panel.

Display:

**Welcome to AI Interview Room**

Buttons:

- **Candidate Login** — outlined/stroked button
- **Admin Login** — primary `#0F98FF` filled button

The interface should immediately distinguish candidate and administrator entry points.

---

## Page 02 — Selection Role

### Background

Use a full-screen abstract design, soft gradient, or linear gradient.

The background should visually connect to the AI interview platform while remaining subtle enough to preserve readability.

### Center Glass Container

Use a large premium glassmorphism container centered on the page.

Display:

**Select Your Role**

### Role Selector

Create a selector component with:

- Neutral filled background
- Primary `#0F98FF` stroke
- Clear hover state
- Clear selected state
- Rounded corners

Options:

1. Student Candidate
2. Industry Candidate

### Unique Code Section

Display:

**Enter Your Unique Code**

Supporting text:

> When you applied for this role, on your mobile we sent the code.

Include an input field for the unique candidate code.

### Next Button

Use:

- `#0F98FF`
- Filled button
- Rounded corners
- Hover elevation
- Disabled state when required information is missing

---

## Page 03 — Selection Position

### Background

Add a beautiful abstract background suitable for the AI-powered recruitment platform.

Possible treatments:

- Soft gradient
- Abstract AI geometry
- Fluid shapes
- Glass layers
- Subtle particles
- Linear gradient

### Candidate Information

Display:

**Name:** Your Name

Also show:

**Got your CV**

### Position Selection

Display:

**Select Your Position**

Dropdown options:

- UI/UX Designer — Non-Coder
- Project Manager — Non-Coder
- Back End Developer — Coder
- ML Engineer — Coder

The interface should clearly communicate whether the selected position follows a non-coder or coder interview workflow.

### Join Interview

Primary CTA:

**Join Interview**

Use the primary brand color `#0F98FF`.

---

## Page 3.1 — Selection Position for Student

The Student Candidate position-selection page should follow the same design system as Page 03.

The interface should:

- Display candidate identity
- Display selected student context
- Allow position selection
- Clearly indicate whether the selected position is coder or non-coder
- Prepare the candidate for the appropriate interview flow

The student experience should communicate that a progress report will be available after the interview.

---

## Page 3.2 — Selection Position for Industry

The Industry Candidate position-selection page should follow the same visual language as Page 03.

The selected position determines the interview path:

- Non-Coder → AI Interview
- Coder → AI Interview + Coding Round

The transition between selection and interview should feel seamless.

---

# Page 04 — Interview / Result Flow

Page 04 represents the complete interview experience family.

Each major interface should be created as a separate prototype frame/artboard.

---

## Page 04A — Industry Non-Coder AI Interview

Flow:

Candidate Login  
→ Selection Role  
→ Industry  
→ Selection Position  
→ Non-Coder AI Interview  
→ End Interview  
→ Onboarding Screen

The candidate does not receive a coding round.

### AI Interview Interface

The interface should include:

- AI interviewer
- Candidate camera/video
- Current question
- Interview progress
- Microphone status
- Camera status
- AI listening/speaking state
- Timer where appropriate
- End Interview action
- Connection status
- Clear interaction feedback

The interface should feel:

- Calm
- Professional
- Intelligent
- Focused
- Real-time
- Premium

---

## Page 04B — Industry Coder AI Interview — Round 1

Flow:

Candidate Login  
→ Selection Role  
→ Industry  
→ Selection Position  
→ AI Interview — Round 1  
→ Coding Round — Round 2  
→ End Interview  
→ Onboarding Screen

Round 1 should contain the standard AI interview interface.

After completion, the candidate proceeds to the second technical round.

---

## Page 04C — Industry Coder AI Interview — Round 2

The second round is a coding/technical assessment.

The interface should include:

- Problem statement
- Code editor
- Programming-language selector
- Run Code
- Submit Code
- Test cases
- Output/console
- Timer
- Round indicator
- Submission status

The interface should feel like a modern developer environment rather than a traditional coding-test website.

Prioritize:

- Focus
- Readability
- Technical credibility
- Fast interaction
- Minimal distractions
- Clear hierarchy

After completion:

**End Interview → Onboarding Screen**

---

## Page 04D — Student Non-Coder AI Interview

Flow:

Student Candidate  
→ Selection Position  
→ Non-Coder AI Interview  
→ End Interview  
→ Student Progress Report  
→ Download Progress Report / QR Code  
→ Onboarding Screen

The same premium AI interview interface should be used while adapting the experience for student candidates.

---

## Page 04E — Student Coder AI Interview — Round 1

Flow:

Student Candidate  
→ Selection Position  
→ AI Interview — Round 1  
→ Coding Round — Round 2  
→ Student Progress Report  
→ Download Progress Report / QR Code  
→ Onboarding Screen

Round 1 uses the AI interview interface.

---

## Page 04F — Student Coder AI Interview — Round 2

The second round is the coding assessment.

Use the same premium coding environment defined for Page 04C.

After completion:

**End Interview → Student Progress Report**

---

# Page 05 — Student Progress Report

The student progress report appears after completing the interview.

The report should be visually polished, educational, and easy to understand.

Possible sections:

- Overall progress
- Interview performance
- Communication indicators
- Answer relevance
- Technical performance
- Coding performance where applicable
- Strength areas
- Improvement areas
- Summary
- Next steps

Primary action:

**Download Progress Report**

Also display a QR code for convenient access.

The QR code should be integrated into a premium report card rather than appearing as an isolated generic QR element.

Candidate-facing information should only expose metrics approved for the student report.

---

# Page 06 — Download Progress Report

Create a dedicated download state/screen where appropriate.

Display:

**Your Progress Report is Ready**

Include:

- Report preview
- Download button
- QR code
- Candidate name
- Position
- Completion status

The QR code should provide a convenient way to access the progress report.

---

# Page 07 — Interview Completion / Onboarding Screen

The completion experience should provide a clear end state.

Display:

- Interview completed status
- Thank-you message
- Completion confirmation
- Relevant next-step information
- Return/onboarding action

The transition should feel intentional rather than like an abrupt end to the application.

---

# 31. Complete Candidate User Flows

## Industry — Non-Coder

Candidate Login  
→ Selection Role  
→ Industry Candidate  
→ Selection Position  
→ Non-Coder AI Interview  
→ End Interview  
→ Onboarding Screen

## Industry — Coder

Candidate Login  
→ Selection Role  
→ Industry Candidate  
→ Selection Position  
→ AI Interview — Round 1  
→ Coding Round — Round 2  
→ End Interview  
→ Onboarding Screen

## Student — Non-Coder

Candidate Login  
→ Selection Role  
→ Student Candidate  
→ Selection Position  
→ Non-Coder AI Interview  
→ Student Progress Report  
→ Download Progress Report / QR Code  
→ Onboarding Screen

## Student — Coder

Candidate Login  
→ Selection Role  
→ Student Candidate  
→ Selection Position  
→ AI Interview — Round 1  
→ Coding Round — Round 2  
→ Student Progress Report  
→ Download Progress Report / QR Code  
→ Onboarding Screen

---

# 32. Admin Login & Admin Experience

The Admin Login is accessed from Page 01.

After successful authentication, the admin enters a dedicated enterprise-grade dashboard.

## Admin Navigation

The admin interface should include:

- Dashboard
- Candidates
- Scoring Weight Preset
- Search
- Admin Name / Profile
- Logout

Additional navigation items may be introduced where necessary to support the product.

---

# Admin Dashboard

The dashboard should prioritize information that requires administrator attention.

## Cohort Composite

Display a high-level view of the candidate cohort.

Possible information:

- Total candidates
- Interview completion
- Average composite score
- Interview performance
- Technical performance
- Cohort trends
- Candidate distribution

The purpose is to provide a quick overview of the current recruitment cohort.

## Needs You

This section should show candidates or tasks requiring administrator attention.

Examples:

- Pending candidate review
- Incomplete interviews
- Pending scoring
- Candidate requiring manual review
- Interview issues
- Time-sensitive actions

The purpose is to answer:

> What needs the admin's attention right now?

## Ranked by What Expires Soonest

Display time-sensitive items according to their nearest expiration/deadline.

Examples:

- Interview invitations expiring soon
- Pending evaluations
- Candidate review deadlines
- Coding rounds awaiting completion
- Time-sensitive recruitment actions

The purpose is to make operational urgency immediately visible.

This is an urgency-based ordering, not a candidate-quality ranking.

---

# Candidates

The Candidates section should provide complete candidate-management functionality.

Display information such as:

- Candidate name
- Candidate type
- Position
- Interview status
- CV Fit Score
- Live Interview Score
- Coding Score
- Final Composite Score
- Completion status
- Review status
- Expiration/deadline
- Last activity

Use modern:

- Data views
- Candidate cards
- Filters
- Search
- Expandable detail panels
- Structured tables where useful

Avoid unnecessarily dense legacy-style administrative interfaces.

---

# Candidate Detail View

Selecting a candidate should open a detailed candidate profile.

Display:

### Candidate Information

- Name
- Candidate type
- Position
- Cohort
- Interview status

### Evaluation

- CV Fit Score
- Live Interview Score
- Coding Score where applicable
- Final Composite Score

### Supporting Information

- CV fit rationale
- Interview evaluation
- Coding evaluation
- Relevant timestamps
- Interview completion status

The admin should be able to understand how the final score was produced rather than seeing only a single number.

---

# Scoring Weight Preset

The admin should be able to configure scoring weights by role.

Weights must not be hardcoded because different roles can place different importance on:

- Communication
- Experience
- Technical skill
- Coding ability

Example technical role:

CV Fit — 20%  
Live Interview — 40%  
Coding — 40%

Example non-technical role:

CV Fit — 30%  
Live Interview — 70%  
Coding — 0%

The interface should support:

- Role selection
- Weight configuration
- Editing
- Saving presets
- Viewing active configuration

The total weight must equal:

**100%**

---

# Admin Profile

Display:

- Admin name
- Profile/account area
- Relevant account information
- Logout

Keep the profile experience lightweight and consistent with the main dashboard.

---

# Logout

Logout should remain easily accessible.

Where appropriate, use a lightweight confirmation state before ending the admin session.

---

# 33. Scoring Matrix Framework

The platform uses a multi-stage scoring framework:

A. CV Fit Score  
B. Live Interview Score  
C. Coding Score  
D. Final Composite Score

Overall structure:

CV Fit Score  
+ Live Interview Score  
+ Coding Score  
→ Final Composite Score

---

# A. CV Fit Score

The CV Fit Score is computed when the CV is uploaded.

The score remains hidden from the candidate until the appropriate final stage.

The score evaluates:

## Skill / Keyword Match

Measure alignment between the candidate's CV and the selected role requirements.

## Relevant Experience

Consider:

- Years of relevant experience
- Project alignment
- Role alignment
- Experience related to the selected position

## Output

Generate:

**CV Fit Score: 0–100**

The admin view should include a short rationale explaining the major factors contributing to the score.

---

# B. Live Interview Score

The Live Interview Score is generated from the AI Interview interface.

## Confidence Score

Derived from available presentation signals such as:

- Voice tone
- Speaking pace
- Posture cues
- Gesture cues

This should be presented as a model-generated indicator rather than an absolute measurement of personality or ability.

## Eye Contact Score

Represent the percentage of relevant interview time during which the candidate is facing the camera.

## Filler Word Score

Measure the frequency of filler words such as:

- "um"
- "like"
- "uh"

The metric may be represented as frequency per minute and/or normalized to a 0–100 score.

## Emotion Stability

Measure consistency of observable expression patterns during:

- Pressure
- Interruption
- Challenging questions
- Changes in interview context

This should represent observable signals rather than claiming to directly measure internal emotional state.

## Answer Relevance Score

Use an LLM-based evaluation to determine whether the candidate's answer addresses the core concept of the interview question.

The system should provide an explanation/rationale rather than displaying only a numerical score.

---

# C. Coding Score

The Coding Score applies to technical/coder roles.

## Correctness

Evaluate whether the submitted code:

- Runs successfully
- Produces expected results
- Passes expected test cases

## Structure & Readability

Evaluate:

- Naming
- Modularity
- Code organization
- Clean logic
- Maintainability

## Approach Quality

Use LLM-assisted evaluation to assess the reasoning and approach behind the solution.

The system should distinguish between:

- Correct output
- Implementation quality
- Reasoning quality

The coding evaluation should not rely solely on whether the final output is correct.

---

# D. Final Composite Score

The final composite score is calculated using configurable weighted averaging.

Conceptually:

Final Composite Score  
=  
(A × CV Weight)  
+  
(B × Interview Weight)  
+  
(C × Coding Weight)

All component scores should be normalized to a consistent 0–100 scale.

## Example — Technical Role

CV Fit Score — 20%  
Live Interview Score — 40%  
Coding Score — 40%

## Example — Non-Technical Role

CV Fit Score — 30%  
Live Interview Score — 70%  
Coding Score — 0%

These are example configurations, not fixed universal weights.

Weights must be configurable per role because different positions can value communication, experience, and technical capability differently.

---

# 34. Responsive Design Requirements

Every page must be fully responsive.

Required layouts:

- Desktop
- Laptop
- Tablet
- Mobile

Responsive behavior must preserve:

- Visual hierarchy
- Readability
- Interaction quality
- Accessibility
- Spacing
- Component usability
- Navigation clarity

The design must not simply shrink the desktop layout.

Responsive layouts should be intentionally designed for each viewport.

This applies to:

- Onboarding
- Login
- Role selection
- Position selection
- AI Interview
- Coding Round
- Progress Report
- Download Report
- Admin Dashboard
- Candidates
- Candidate Detail
- Scoring Weight Preset
- Admin Profile
- Logout

---

# 35. Accessibility Requirements

The complete prototype should follow WCAG-oriented accessibility principles.

Requirements:

- Keyboard navigation
- High contrast
- Readable typography
- Large click/tap targets
- Visible focus states
- Clear labels
- Accessible form controls
- Accessible error states
- Screen-reader-friendly structure
- Sufficient color contrast
- No information conveyed through color alone
- Responsive text scaling
- Accessible modal/dialog behavior

Accessibility should be integrated into the design system rather than treated as an afterthought.

---

# 36. Final Prototype Requirements

The final output must be a complete high-fidelity prototype at **1440px desktop resolution**.

The prototype must include every major screen and flow described above.

Each page/screen must be separated into its own Figma frame/artboard.

The final experience should demonstrate:

- Premium AI-first design
- World-class visual hierarchy
- Strong product identity
- Modern recruitment workflow
- Candidate-friendly interaction
- Enterprise-grade admin experience
- Configurable scoring architecture
- Responsive design
- Accessibility
- Clear navigation
- Realistic AI interview interaction
- Coding assessment experience
- Student progress reporting
- QR-based report access

The overall product should feel like a serious **2026 AI-powered hiring platform**, not a generic dashboard template or conventional recruitment website.

The final design should communicate:

> **Bold. Original. Intelligent. Human-centered. Enterprise-ready. AI-native.**
