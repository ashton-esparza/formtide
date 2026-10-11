# FormTide — Strategic Roadmap

> **Progress comes in waves.**
>
> **Status:** Living draft (v0.1) · **Created:** October 11, 2026  
> **Related brands:** **fashtonfit** (audience and marketing) · FormTide (coaching experience and software)

## 1. Vision

Build a sustainable fitness-coaching business and, over time, a scalable software platform that makes personalized training, body-composition guidance, and better health more accessible to everyday people.

This is a **three-part venture**, not three unrelated projects:

| Pillar                            | Primary purpose                                                                                    | Feeds into                                                      |
| --------------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| **fashtonfit**                    | Earn attention and trust through relatable, useful fitness content                                 | Audience → qualified leads → clients and product insight        |
| **Coaching education & practice** | Build competence, credibility, judgment, and real-world client experience                          | Better coaching → better outcomes → better product requirements |
| **FormTide**                      | Deliver a streamlined, asynchronous coaching experience; gradually productize repeatable workflows | Better client experience → lower overhead → scalable revenue    |

**Flywheel:** Educate publicly → attract the right people → coach them well → learn from real use → improve FormTide → share useful lessons and outcomes (with consent) → repeat.

### Principles

- **Clients first, software second.** Build features that solve demonstrated coaching or client problems.
- **Sustainable progress beats dramatic short-term results.** Fitness moves through build, lean, and maintain phases—not a single straight line.
- **Human-in-the-loop by default.** Use AI and automation for administrative work, drafts, pattern detection, and explanations; retain coach oversight of material training/nutrition decisions.
- **Self-service where it empowers, not where it abandons.** Make routine actions easy without eliminating judgment or accountability.
- **Evidence-informed and within scope.** Distinguish fitness education from diagnosis, rehabilitation, or regulated nutrition practice.
- **Build alongside an existing engineering career.** Protect time, avoid premature overhead, and scale only when demand and economics justify it.

## 2. North star and measures

**North star:** Clients consistently make meaningful progress through coaching that is effective, accessible, and operationally sustainable.

Track a small set of measures from the beginning; establish baselines before setting targets.

| Area                   | Useful signals                                                                                       | Caution                                        |
| ---------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| Audience / acquisition | Relevant followers, profile visits, qualified inquiries, waitlist signups, inquiry → paid conversion | Follower count alone is not a business outcome |
| Coaching value         | Goal progress, adherence, client-reported confidence, satisfaction, referrals                        | Avoid reducing success to scale weight         |
| Client experience      | Onboarding completion, weekly check-in completion, time to useful feedback, retention                | Low effort must not mean low care              |
| Operations             | Coaching hours per active client, review backlog, recurring manual tasks                             | Count hidden admin time                        |
| Business               | Active paying clients, monthly recurring revenue, churn, contribution margin                         | Separate revenue from take-home income         |
| Product                | Weekly active clients, workout logs, check-in completion, bugs/support requests                      | Ship against observed problems, not guesses    |

**Aspirational audience milestone:** ~10,000 organic fashtonfit followers during the coaching-growth stage. Treat as a directional ambition, **not** a requirement to launch, raise rates, or scale.

## 3. Roadmap at a glance

This roadmap uses **evidence-based stage gates instead of fixed dates**. Activities overlap; moving forward does not require abandoning earlier pillars.

| Stage                          | Business objective                                  | Education                                                                                | FormTide                                                      | fashtonfit                                                    |
| ------------------------------ | --------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- |
| **0 — Foundations (parallel)** | Prepare a trustworthy first offering                | Study for NASM-CPT; CPR/AED                                                              | Define MVP and build first usable workflow                    | Keep posting; test audience problems and interests            |
| **1 — Paid coaching beta**     | First clients and first recurring revenue           | Complete NASM-CPT; apply foundational coaching skills                                    | Deliver onboarding, programming, tracking, check-ins, reviews | Convert trust into qualified conversations; document learning |
| **2 — Coaching depth & fit**   | Improve results, retention, pricing, and efficiency | Consider NASM-PES and/or NSCA-CSCS; evaluate nutrition/behavior education based on needs | Automate validated repetitive work; refine coach/client UX    | Strengthen authority, testimonials, referrals, and audience   |
| **3 — Platform scale**         | Expand beyond one coach's available hours           | Develop trainer enablement and quality standards                                         | Multi-coach SaaS and selectively self-serve tiers             | Acquire both clients and prospective coaches                  |

## 4. Stage 0 — Foundations (three tracks in parallel)

**Goal:** Become ready to deliver a safe, useful, paid beta without overbuilding or waiting for a large audience.

### Track A — Education / NASM-CPT

- [ ] Select the **NCCA-accredited NASM-CPT exam** pathway and establish a realistic study cadence.
- [ ] Schedule accepted **CPR/AED certification** and verify current exam prerequisites.
- [ ] Study movement science, assessments, exercise technique, programming, behavior change, and professional responsibilities.
- [ ] Use practice questions and weak-area review to track exam readiness.
- [ ] Pass NASM-CPT and define a continuing-education plan.
- [ ] Document the boundaries of professional practice and referral processes.

### Track B — FormTide / MVP discovery and development

- [ ] Write a one-page target-client profile: general-population adults seeking fat loss, muscle gain, better routines, and confidence.
- [ ] Interview potential users about onboarding, adherence, scheduling, check-ins, nutrition support, and communication frustrations.
- [ ] Map a single complete client journey: **discover → inquire → enroll → onboard → program → log → check in → receive feedback → adjust**.
- [ ] Define privacy, data retention, consent, secure authentication, and client-data boundaries before collecting sensitive information.
- [ ] Choose the smallest sustainable architecture; document tradeoffs rather than building for hypothetical scale.
- [ ] Build a working end-to-end MVP flow and test it with mock/test accounts.
- [ ] Create coach-facing operational checklists and a manual fallback for failures.

**MVP — must support a complete coaching loop:**

1. Client account, consent, intake, goals, and relevant readiness screening.
2. Coach-created or coach-approved training program delivery.
3. Simple workout completion and progress/measurement logging.
4. Structured, asynchronous check-ins and coach responses.
5. Coach dashboard showing what needs review and what changed.
6. Basic enrollment/payment workflow (manual steps are acceptable in a beta).
7. Basic notifications, security, access controls, and data handling.

**Deliberately later:** full meal databases, wearable integrations, autonomous AI coaching, community/social feeds, marketplace features, trainer multi-tenancy, advanced analytics, elaborate program builders, and sophisticated billing plans.

### Track C — fashtonfit / audience and trust

- [ ] Maintain a sustainable publishing cadence, favoring quality and consistency over volume.
- [ ] Continue useful content in three value categories: **educational, relatable/entertaining, motivational**.
- [ ] Use the existing content structure when appropriate: **observation → challenge the premise → teach the rule → example → takeaway**.
- [ ] Test content on real audience pain points: adherence, dieting, body recomposition, beginner lifting, plateaus, and habits.
- [ ] Occasionally document authentic NASM preparation and FormTide's build process; keep the account primarily valuable to its fitness audience.
- [ ] Set up a lightweight interest/waitlist mechanism, with clear permission to contact people.
- [ ] Clearly represent certification status; do not imply qualifications not yet earned.

### Stage 0 exit gate

- [ ] NASM-CPT earned, with current CPR/AED and an appropriate professional setup.
- [ ] End-to-end FormTide MVP works for at least one test client journey.
- [ ] Intake, informed consent, policies, payment handling, liability coverage, and operating procedures have been reviewed before paid onboarding.
- [ ] An initial pool of interested potential clients exists; a large follower count is **not** required.

## 5. Stage 1 — Paid coaching beta

**Goal:** Validate that clients will pay for the experience, benefit from it, and complete the recurring check-in loop.

- [ ] Recruit a **small, manageable initial cohort** (working hypothesis: 3–5 clients, adjusted to actual available time).
- [ ] Offer a clearly scoped coaching package: who it serves, what's included, check-in cadence, communication expectations, and boundaries.
- [ ] Establish initial pricing from value, time costs, positioning, and market feedback; do not assume credentials alone justify higher prices.
- [ ] Onboard clients through FormTide and manually support any missing workflows.
- [ ] Complete several full plan → execution → check-in → review → adjustment cycles.
- [ ] Capture structured feedback and categorize friction: client confusion, repetitive coach labor, bugs, missing features, and low-value features.
- [ ] Measure time spent per client and client adherence; refine the service before adding significant capacity.
- [ ] Request testimonials, transformation stories, or case studies **only with explicit informed consent**.

**Stage 1 exit gate (hypotheses to refine):** Several active paying clients have completed multiple check-in cycles, the core experience is usable, coaching delivery is within a sustainable time budget, and a prioritized product backlog is backed by real observations.

**Business expectation:** This is the start of revenue and proof of demand, **not** an immediate replacement for software-engineering income.

## 6. Stage 2 — Coaching depth, product fit, and operational leverage

**Goal:** Improve client outcomes, coaching expertise, retention, and unit economics before adding substantial volume.

### Coaching and credentials

- [ ] Review the most common actual client challenges and select education accordingly.
- [ ] Evaluate **NASM-PES** for applied performance programming and/or **NSCA-CSCS** for deeper strength-and-conditioning expertise.
- [ ] Consider nutrition/behavior-coaching education if it better matches the needs of general-population clients than athletic-performance credentials.
- [ ] Apply learning to assessment, progression, communication, and program quality; evaluate outcomes rather than credential count.
- [ ] Explore tiered offers and pricing changes based on demonstrated client value, retention, service complexity, and sustainable delivery cost.

**Certification decision note:** PES is a specialization focused on athletic performance, not an NCCA-accredited standalone CPT credential. CSCS currently accepts a bachelor's degree in any field for U.S. candidates through **December 31, 2029**; starting **January 1, 2030**, NSCA plans to require a bachelor's degree from a CASCE-accredited program for U.S. applicants. Verify the rules when deciding and scheduling.

### Product improvements driven by evidence

- [ ] Maintain a prioritized list of recurring client and coach problems.
- [ ] Standardize reusable onboarding, goal-setting, program, and check-in templates.
- [ ] Reduce repetitive administration with reminders, data summaries, and workflow automation.
- [ ] Experiment with **coach-reviewed** AI summaries/suggestions; test for correctness, safety, privacy, and actual time saved.
- [ ] Improve mobile usability, accessibility, client education, and progress visualization.
- [ ] Implement analytics that help guide action rather than merely display charts.
- [ ] Reassess security, client-data separation, backups, and operational reliability as usage grows.

### Audience and offer development

- [ ] Publish more practical coaching lessons and evidence-informed myth-busting content.
- [ ] Share transparent product-building updates when relevant to client pain points.
- [ ] Use feedback from inquiries, non-buyers, active clients, and churned clients to sharpen positioning.
- [ ] Explore referrals, collaborations, and an email/waitlist channel so acquisition does not depend only on Instagram.
- [ ] Pursue the **~10k organic follower** ambition without mistaking it for proof of product-market fit.

**Stage 2 exit gate:** Repeatable coaching outcomes, healthy retention, a sufficiently reliable product, improving time-per-client economics, consistent qualified demand, and evidence that other coaches would benefit from the platform.

## 7. Stage 3 — FormTide as a scalable platform

**Goal:** Move from a single-coach delivery tool toward a sustainable, multi-coach SaaS business and optional low-cost self-service experience.

### Expansion paths (validate separately)

**A. Trainer SaaS — B2B/B2B2C**

- [ ] Validate demand with trainers outside the founding coaching practice.
- [ ] Define coach accounts, organizations, client ownership, permissions, and secure tenant isolation.
- [ ] Productize trainer onboarding, programming templates, check-ins, billing, and support.
- [ ] Pilot with a few external trainers before broad self-service signup.
- [ ] Establish SaaS pricing around clear value, usage, and support costs.

**B. Client self-service — B2C**

- [ ] Identify safe, high-value features that genuinely work without continuous 1:1 coaching.
- [ ] Test a low-cost or limited free tier: guided onboarding, general training plans, educational resources, tracking, and automated reminders.
- [ ] Use clear escalation pathways to human coaches when individualized judgment is needed.
- [ ] Validate conversion, retention, safety, and support burden before broad expansion.

**Do not assume both business models should launch together.** Choose the first path using demand, economics, operating complexity, and differentiation.

### Stage 3 success indicators

- Revenue and client outcomes are increasingly independent of the founder personally reviewing every routine interaction.
- Trainers can onboard and deliver reliable coaching without founder-led setup.
- Clear separation between general-purpose automation and individualized professional recommendations.
- Sustainable margins after infrastructure, payment processing, support, marketing, and compliance costs.

## 8. Operating cadence and decision discipline

### Weekly review (lightweight)

- **Education:** Did study progress? What is the next weak area to address?
- **Content:** Which posts generated genuine conversation, questions, or qualified inquiries?
- **Product:** What client/coach problem was learned, fixed, or validated this week?
- **Capacity:** Is time investment sustainable alongside employment and personal responsibilities?

### Monthly review

1. Update the metrics and stage exit checklist.
2. Pick **one highest-leverage constraint** across the three pillars.
3. Limit the next development cycle to a small number of measurable outcomes.
4. Decide what to **start, continue, pause, or explicitly defer**.
5. Record significant choices in short architecture/product decision notes.

### Decision rules

- **Don't add a feature** solely because it is technically interesting; attach it to a user problem and expected impact.
- **Don't automate** a coaching decision until the manual workflow is understood and its quality can be evaluated.
- **Don't scale acquisition** faster than service quality and capacity can support.
- **Don't leave engineering employment** based on follower count or gross revenue alone; require sustained, risk-adjusted income, runway, and a workable schedule.
- **Don't treat certificates as substitutes** for client experience, ethical practice, and demonstrated outcomes.

## 9. Risks and guardrails

| Risk                                                         | Mitigation                                                                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| Three simultaneous initiatives overwhelm available time      | Time-box efforts; pick one primary constraint each month                                          |
| MVP expands into an unfocused fitness super-app              | Define the smallest complete coaching loop; maintain a “later” list                               |
| Social reach does not convert to revenue                     | Track qualified inquiries, conversion, retention, and referrals                                   |
| Credentials don't translate into better service              | Apply new skills to actual coaching and evaluate client feedback                                  |
| AI provides low-quality or inappropriate advice              | Require evaluation, limits, disclosure, and human review; no diagnosis or treatment               |
| Handling sensitive client data creates risk                  | Collect minimally, secure access, document consent/retention, and review applicable privacy rules |
| Nutrition guidance crosses professional/licensing boundaries | Confirm jurisdiction-specific rules and refer clinical cases to licensed practitioners            |
| Client capacity becomes a bottleneck                         | Measure coach hours/client and simplify recurring tasks before expanding                          |

## 10. Immediate next actions

- [ ] Block recurring NASM-CPT study time and schedule CPR/AED.
- [ ] Create `docs/vision.md` (one-page client/problem statement) and `docs/mvp.md` (one end-to-end coaching journey).
- [ ] Sketch the first coach and client screens, focusing on onboarding and weekly check-ins.
- [ ] Start a simple audience-question and prospect-interview log sourced from fashtonfit.
- [ ] Publish content consistently while capturing lessons from studying and building.
- [ ] Establish a private product backlog and label work **Now / Next / Later**.
- [ ] Decide on an initial weekly time budget and define what gets deprioritized if it is exceeded.

## 11. Open questions / assumptions to validate

- Who is the **first narrow target customer** (e.g., busy beginners, former athletes returning to lifting, people navigating first cuts)?
- Which part of coaching is hardest for clients: getting started, executing, staying consistent, or knowing when to adjust?
- What communication cadence and level of personalization will clients actually pay for?
- What should be standardized versus tailored by the coach?
- What data is truly necessary to deliver the service?
- How much weekly coaching time is acceptable alongside engineering employment?
- Which advanced educational path addresses the client population's most important needs?
- Is multi-trainer SaaS or low-cost B2C self-service the more promising first expansion?

## 12. References / living resources

- [NASM — CPT program and prerequisites](https://www.nasm.org/products/become-a-personal-trainer)
- [NASM — Performance Enhancement Specialization](https://www.nasm.org/products/performance-enhancement-specialist)
- [NSCA — CSCS prerequisites and 2030 change](https://www.nsca.com/certification/cscs/cscs-exam-prerequisites/)
- [Florida Department of Health — Dietitian and Nutritionist](https://www.floridahealth.gov/licensing-regulations/regulated-professions/dietitian-nutritionist/)
- [Florida Statutes — Chapter 468, Part X](https://leg.state.fl.us/statutes/index.cfm?App_mode=Display_Statute&URL=0400-0499%2F0468%2F0468.html)

---

_This is a directional strategy, not a fixed promise, dated release schedule, or substitute for professional legal/compliance advice. Revise it as coaching experience, customer feedback, and business constraints become clearer._
