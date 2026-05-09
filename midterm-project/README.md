# 🏆 Midterm Project — CareerKiosk Final Report

**Team Neural Nexus | ITAI 4376 | Spring 2026**

Submitted by: **Win Ko Aung** (Team Lead) | **May 1, 2026**

---

## CareerKiosk — AI-Powered Career Guidance & Job Matching Platform

🔗 **Live Platform:** [careerkiosk.ai](https://careerkiosk.ai)

> Presented at the **HCC AI Innovation Symposium & Expo — Spring 2026**

---

## Team

| Member | Role | Responsibilities |
|--------|------|------------------|
| **Win Ko Aung** | Team Lead & Full Stack Dev | Architecture, Job Seeker Portal, AI, security, IP strategy |
| **Duc Nguyen** | Admin Panel Developer | Admin dashboard, moderation, audit logs, analytics, A/B testing |
| **Adeyemi Kolawole (Yemi)** | Backend Dev & QA | Database, Edge Functions, PL/pgSQL triggers, RLS, testing |
| **Stanley Huynh** | Company Portal Developer | Employer dashboard, job posting, hiring pipeline, analytics |
| **Mohd Ilyas Ahmed** | Data Science & AI | Gemini API, data analysis, agent development, ML features |

---

## What We Built

### Three Production-Ready Portals

**Job Seeker Portal**
- AI Resume Builder with smart optimization
- AI Interview Coach (mock sessions, 0–100 scoring)
- Smart Job Matching with AI algorithms
- Application tracker and career goal tracking
- Gamified engagement challenges

**Company Portal**
- Full employer dashboard with analytics
- Job posting and management system
- AI candidate ranking and search
- Hiring pipeline with offer management

**Admin Portal**
- Platform-wide user and content management
- Role-based access control and moderation
- A/B testing engine
- Comprehensive audit logging

### Security Architecture
- **Kernel-Level RLS:** Database blocks unauthorized changes even if frontend is bypassed
- **Automated Security Triggers:** PL/pgSQL fail-safe auto-resets tampered data
- **Access Audit System:** Logs every unauthorized route-guard attempt
- **Magic Byte Verification:** Validates uploaded file DNA
- **2FA + Google OAuth:** Dual authentication for all users

---

## Results & Metrics

| Metric | Result |
|--------|--------|
| Total Screens | 130+ across 3 portals |
| Database Tables | 50+ with RLS on every table |
| Edge Functions | 28 serverless functions |
| DB Migrations | 95+ throughout development |
| AI Features | 10+ across all portals |
| Portals Live | 3 (5 planned) |
| Mobile Support | PWA + Capacitor (iOS & Android) |

---

## Business Plan

- **Domain:** careerkiosk.ai — purchased ($183)
- **Presented at:** HCC AI Innovation Symposium & Expo — Spring 2026
- **Planned:** HCC Business Plan Competition (Jan 2027), Rice University
- **USPTO Patent:** Utility patent filing in progress

### Bill of Materials

| Item | Cost | Status |
|------|------|--------|
| Domain (careerkiosk.ai) | $183 | Purchased |
| Supabase Pro | $25/month | Active |
| AI Agent (Claude) | $21/month | Active |
| Lovable AI | $285 | Active |
| USPTO Patent | $15,000 | Seeking Funding |
| Legal Fees | $15,000 | Seeking Funding |
| Marketing | $20,000 | Seeking Funding |

---

## What We Learned

**Technical:** Prompt specificity is critical; mobile-first design must be planned from day one; security must be built at the database level; AI requires careful prompt engineering.

**Business:** IP protection is critical for student-built commercial products; splitting by portal creates clear ownership; regular class presentations drive accountability; AI tools accelerate development but require human oversight.

---

*Part of the Neural Nexus ITAI 4376 Portfolio | [Back to Main Portfolio](../README.md)*
