# RoadWork Platform — TODO

## [RC] Core Platform

- [ ] [RC] Integrate Ollama/local LLM for tutor response generation (replace placeholder methods)
- [ ] [RC] Implement full FSRS-4.5 parameter optimization with student history
- [ ] [RC] Build WebSocket real-time tutoring sessions (replace request/response)
- [ ] [RC] Add file upload support for homework photos (OCR pipeline)
- [ ] [RC] Implement student authentication (Stripe + session tokens)
- [ ] [RC] Add rate limiting and abuse prevention on tutor endpoints
- [ ] [RC] Build parent dashboard with progress summaries and alerts
- [ ] [RC] Implement teacher dashboard with class-wide analytics

## [RC] Accessibility

- [ ] [RC] Integrate OpenDyslexic font and bionic reading mode
- [ ] [RC] Implement speech-to-text input for all text fields
- [ ] [RC] Build text-to-speech output with adjustable speed and voice
- [ ] [RC] Add switch access and dwell-click support
- [ ] [RC] Run automated WCAG 2.2 AA audit with axe-core
- [ ] [RC] Test with NVDA, JAWS, VoiceOver, TalkBack screen readers
- [ ] [RC] Implement cognitive load reduction mode (simplified UI)
- [ ] [RC] Add keyboard shortcut overlay and help panel

## [RC] Visualization Engine

- [ ] [RC] Build SVG generation engine for math concepts
- [ ] [RC] Implement interactive Canvas-based physics simulations
- [ ] [RC] Add ASCII fallback generator for all visualization types
- [ ] [RC] Build audio description pipeline for visualizations
- [ ] [RC] Create chemistry lab simulation sandbox
- [ ] [RC] Implement code sandbox with syntax highlighting and execution

## [RC] LMS Integration

- [ ] [RC] Implement full LTI 1.3 launch flow (OIDC + JWT)
- [ ] [RC] Build Canvas LTI Advantage deep linking
- [ ] [RC] Implement Assignment and Grade Services (AGS) for grade passback
- [ ] [RC] Build Names and Role Provisioning Services (NRPS) for roster sync
- [ ] [RC] Add Schoology-specific SSO integration
- [ ] [RC] Implement MyMathLab problem-level content matching
- [ ] [RC] Build LMS admin panel for district-wide configuration

## [RC] Content & Curriculum

- [ ] [RC] Build adaptive content generation engine (3 Lexile levels)
- [ ] [RC] Implement Common Core standards alignment mapping
- [ ] [RC] Add NGSS standards alignment for science courses
- [ ] [RC] Build FSRS review card auto-generation from lesson content
- [ ] [RC] Implement formative assessment question generator
- [ ] [RC] Create differentiated content export (PDF, SCORM, LTI)

## [RC] Infrastructure

- [ ] [RC] Deploy FastAPI app to Octavia (self-hosted)
- [ ] [RC] Set up PostgreSQL database (migrate from SQLite)
- [ ] [RC] Configure Caddy reverse proxy for roadwork.blackroad.io
- [ ] [RC] Add Stripe checkout integration for subscription plans
- [ ] [RC] Implement FERPA-compliant data encryption at rest
- [ ] [RC] Set up automated backups to MinIO
- [ ] [RC] Build CI/CD pipeline with Gitea Actions
- [ ] [RC] Add monitoring with InfluxDB + Grafana dashboard

## [RC] Data & Privacy

- [ ] [RC] Implement FERPA compliance audit logging
- [ ] [RC] Build COPPA-compliant parental consent flow
- [ ] [RC] Add data export/deletion for student privacy requests
- [ ] [RC] Implement end-to-end encryption for student data
- [ ] [RC] Create privacy impact assessment documentation
- [ ] [RC] Build data retention policy automation (auto-delete after term)

## [RC] Testing

- [ ] [RC] Write unit tests for FSRS algorithm implementation
- [ ] [RC] Add integration tests for all API endpoints
- [ ] [RC] Build accessibility automated test suite
- [ ] [RC] Create load tests for concurrent tutor sessions
- [ ] [RC] Implement LTI 1.3 certification test suite
- [ ] [RC] Add end-to-end tests for student learning flow
