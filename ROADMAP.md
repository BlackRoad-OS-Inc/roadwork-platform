# RoadWork Platform — Product Roadmap

> **RoadWork**: Adaptive AI tutoring that remembers every student, builds conceptual understanding, and meets every learner where they are.
>
> Part of [BlackRoad OS](https://blackroad.io) — Pave Tomorrow.

---

## Phase 1: MVP — Foundation ($75K-$150K, 6 months)

**Goal**: Launch core AI tutoring platform with FSRS scheduling, basic accessibility, and individual subscriptions.

### Milestone 1.1: Core Tutor Engine (Months 1-2)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| FastAPI backend | Education-specific API with SQLite (dev) / PostgreSQL (prod) | In Progress |
| FSRS implementation | Full FSRS-4.5 spaced repetition with per-concept difficulty/stability | In Progress |
| Cross-session memory | Student memory persistence across all sessions | In Progress |
| Socratic method engine | AI tutor that guides through questions instead of giving answers | Planned |
| Local LLM integration | Ollama on Pi fleet for sovereign inference | Planned |
| Landing page | Full product marketing page with BlackRoad design system | Done |

### Milestone 1.2: Accessibility Foundation (Months 2-3)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| WCAG 2.2 AA compliance | Full audit and remediation of all UI components | Planned |
| Screen reader support | ARIA landmarks, live regions, tested with NVDA/JAWS/VoiceOver | Planned |
| Keyboard navigation | Full keyboard access with visible focus indicators | Planned |
| High contrast mode | WCAG AAA contrast ratios, system preference detection | Planned |
| Dyslexia-friendly fonts | OpenDyslexic option with adjustable spacing | Planned |
| Speech I/O | Speech-to-text input and text-to-speech output | Planned |

### Milestone 1.3: Individual Launch (Months 4-6)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| Stripe integration | $9.99/mo Individual, $19.99/mo Family subscription plans | Planned |
| Student dashboard | Progress, FSRS review schedule, concept mastery visualization | Planned |
| Parent dashboard | Child progress reports, alerts, settings management | Planned |
| 10 seed courses | Algebra, Biology, Chemistry, Physics, English, History, CS, Spanish, Geometry, Creative Writing | In Progress |
| Homework upload | Photo/PDF upload with OCR for problem extraction | Planned |
| Basic visualization | SVG diagrams for math and science concepts | Planned |

**Phase 1 Revenue Target**: 500 individual subscribers = ~$5K MRR

---

## Phase 2: Growth — Institutional ($200K-$500K, 12 months)

**Goal**: Launch school/district plans with LMS integration, teacher tools, and expanded content.

### Milestone 2.1: LMS Integration (Months 7-9)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| LTI 1.3 core | OIDC login, JWT validation, launch flow | Planned |
| Canvas integration | Deep linking, AGS grade passback, NRPS roster sync, SpeedGrader | Planned |
| Schoology integration | Gradebook sync, parent portal, district-wide SSO | Planned |
| MyMathLab integration | Problem-level content matching, supplemental tutoring mode | Planned |
| Teacher dashboard | Class-wide analytics, concept gap identification, intervention alerts | Planned |
| District admin panel | Multi-school management, usage reporting, compliance dashboard | Planned |

### Milestone 2.2: Content Engine (Months 9-11)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| Adaptive content generation | Auto-generate lessons at 3 Lexile levels per topic | Planned |
| Standards alignment engine | Auto-map content to Common Core, NGSS, state standards | Planned |
| Assessment generator | Formative and summative assessments from lesson content | Planned |
| FSRS card generator | Auto-create spaced repetition cards from any content | Planned |
| Content export | PDF, SCORM 2004, LTI Deep Linking for LMS import | Planned |
| 50+ courses | Expand to full K-12 catalog across 8 subject areas | Planned |

### Milestone 2.3: Visualization & Sandbox (Months 10-12)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| Interactive SVG engine | Draggable, zoomable, keyboard-navigable diagrams | Planned |
| Chemistry sandbox | Virtual lab with reactions, pH, titration simulations | Planned |
| Physics sandbox | Mechanics, optics, wave simulations with real constants | Planned |
| Code sandbox | Python/JS execution with syntax highlighting and test cases | Planned |
| Math graphing | Interactive function plotter with accessibility | Planned |
| Audio descriptions | Full audio narration pipeline for all visual content | Planned |

### Milestone 2.4: Institutional Sales (Month 12)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| School pricing | $3-8/student/year volume pricing | Planned |
| Pilot program | 5 schools, 50 classrooms, 1,000 students | Planned |
| FERPA certification | Third-party FERPA compliance audit | Planned |
| COPPA compliance | Parental consent flow, data minimization, auto-deletion | Planned |
| Case studies | Publish 3 pilot school case studies with outcome data | Planned |
| Sales materials | District pitch deck, ROI calculator, implementation guide | Planned |

**Phase 2 Revenue Target**: 50 schools x $5/student x 500 avg = ~$125K ARR + individual subs

---

## Phase 3: Scale — Enterprise & Research ($300K-$800K, 24 months)

**Goal**: Enterprise deployment, custom AI models, research partnerships, and international expansion.

### Milestone 3.1: Enterprise Platform (Months 13-18)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| On-premise deployment | Docker/K8s deployment for districts with data residency requirements | Planned |
| Custom AI model training | Fine-tune models on district curriculum and pedagogical preferences | Planned |
| White-label option | Brandable version for large organizations | Planned |
| API access | RESTful and GraphQL APIs for third-party integration | Planned |
| SSO/SAML | SAML 2.0, OAuth 2.0, Active Directory integration | Planned |
| 99.9% SLA | High availability with multi-region failover | Planned |
| Dedicated support | Named account manager, 24/7 technical support | Planned |

### Milestone 3.2: Advanced AI (Months 15-20)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| Multi-modal tutoring | Voice, image, video, handwriting input | Planned |
| Predictive analytics | Identify at-risk students before they fall behind | Planned |
| Peer matching | AI-powered study group formation by complementary skills | Planned |
| Learning path optimization | ML-driven curriculum sequencing per student | Planned |
| Emotion detection | Frustration/engagement detection for adaptive pacing | Planned |
| Research data platform | Anonymized, IRB-compliant data for education research | Planned |

### Milestone 3.3: International Expansion (Months 18-24)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| 30+ languages | Full localization of tutor, UI, and content | Planned |
| International standards | Alignment with UK, EU, AU, CA curriculum frameworks | Planned |
| RTL support | Full right-to-left language support (Arabic, Hebrew) | Planned |
| Regional content | Country-specific history, culture, and context | Planned |
| GDPR compliance | EU data protection compliance for European schools | Planned |
| International pilots | 10 schools across 5 countries | Planned |

### Milestone 3.4: Research & Impact (Months 20-24)

| Deliverable | Description | Status |
|-------------|-------------|--------|
| Efficacy study | RCT study measuring learning outcomes vs. control | Planned |
| Accessibility impact | Study on outcomes for students with disabilities | Planned |
| FSRS optimization | Research paper on adaptive scheduling in education | Planned |
| University partnerships | 3 research university partnerships for longitudinal studies | Planned |
| Open data initiative | Anonymized educational data for public research | Planned |
| Conference presentations | ISTE, ASU+GSV, EDUCAUSE presentations | Planned |

**Phase 3 Revenue Target**: $50K-200K/yr enterprise contracts x 10 = $500K-$2M ARR

---

## Revenue Model

| Tier | Price | Target | Annual Revenue |
|------|-------|--------|----------------|
| Individual | $9.99/mo | 2,000 students | ~$240K |
| Family | $19.99/mo | 500 families | ~$120K |
| School | $3-8/student/yr | 50 schools (25K students) | ~$125K |
| Enterprise | $50K-200K/yr | 10 contracts | ~$1M |
| **Total Y2** | | | **~$1.5M ARR** |

---

## Key Differentiators

1. **Cross-session memory** — No other AI tutor remembers students across sessions
2. **FSRS scheduling** — Research-backed spaced repetition, not random quizzing
3. **Accessibility-first** — ADA Title II 2025 compliant from day one, not bolted on
4. **Conceptual understanding** — Socratic method and scaffolding, not drill-and-practice
5. **Sovereign AI** — Local-first inference on BlackRoad Pi fleet, no data leaves the network
6. **LMS native** — LTI 1.3 integration with Canvas, Schoology, MyMathLab out of the box
7. **Affordable** — $9.99/mo individual vs. $20-40/mo for Chegg/CourseHero competitors

---

*Copyright 2024-2026 BlackRoad OS, Inc. All rights reserved.*
*BlackRoad OS — Pave Tomorrow.*
