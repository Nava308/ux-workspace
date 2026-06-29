# PRAJNA — UX Screens to Build
**Project:** PRAJNA — Professional AI Companion for GITAM Faculty
**UX Owners:** Mohan & Hima
**Phase:** 1 (Faculty across Bengaluru, Vizag, Hyderabad)
**Dev Period:** May–July 2026

> All screens must follow GITAM Brand Guidelines.
> Reference: `designs/BRAND_GUIDELINES.md`

---

## Screen Index by Role

| Role | Screens They See |
|---|---|
| Faculty | Auth, Faculty Dashboard, Profile, Teaching, Research, Achievements, FDP, Admin, AI Companion, To-Do, Leaderboard, PRAJNA Score, Notifications, APAR (self) |
| HoD | HoD Dashboard, Approval Queue, Faculty overview, Leaderboard (dept), Reports |
| Director | Director Command Centre, School-level view, Leaderboard (school), Reports |
| Pro Vice-Chancellor | Campus Command Centre, Cross-campus benchmarking |
| IQAC | Inspection Readiness view, NAAC criterion-wise view |
| Admin | All-campus dashboard, User management |

---

## 1. Auth Flow

| # | Screen | Key Elements |
|---|---|---|
| A1 | Login | OTP / SSO login, GITAM branding, campus selector |
| A2 | Role-based redirect | After login — auto-routes to correct dashboard based on JWT role |

---

## 2. Faculty Dashboard (Module 24)

| # | Screen | Key Elements |
|---|---|---|
| F1 | Home / Today | Today's priorities, AI morning briefing card, Dynamic To-Do list, quick actions |
| F2 | PRAJNA Score Card | Composite score, breakdown (Teaching 25%, Research 30%, FDP 20%, Achievements 10%, Admin 10%, Profile 5%), tier badge (Bronze → PRAJNA Fellow) |
| F3 | Personal Timeline | Activity history, milestone highlights |
| F4 | Profile Completeness Banner | % complete, prompts for missing fields |

---

## 3. Faculty Profile (Module 7)

| # | Screen | Key Elements |
|---|---|---|
| P1 | Profile View | Name, designation, campus, school, photo, qualifications |
| P2 | Profile Edit | Edit personal info, upload photo, add ORCID/Scopus IDs |
| P3 | Qualifications | Degree history, institution, year |

---

## 4. Course Deliverables & Teaching (Module 8)

| # | Screen | Key Elements |
|---|---|---|
| T1 | Timetable | Weekly class schedule |
| T2 | Teaching Load | Courses assigned, hours per week |
| T3 | Attendance | Mark attendance per class, view history |
| T4 | Lesson Plans | Upload/view lesson plans per course |
| T5 | CO-PO Mapping | Course Outcome → Programme Outcome mapping table |
| T6 | Faculty Advisor Log | Student advisee list, meeting notes |

---

## 5. Research & Innovation (Module 9)

| # | Screen | Key Elements |
|---|---|---|
| R1 | Publications List | All publications, status badges (Pending / Approved / Rejected) |
| R2 | Add Publication | DOI input, auto-fetch from CrossRef/Scopus, manual override, PDF proof upload |
| R3 | Duplicate Detection | Side-by-side comparison of detected duplicate vs new entry, resolve/confirm action |
| R4 | Grants | Active/past grants, funding body, amount, status |
| R5 | Patents | Patent list, application status, co-inventors |
| R6 | PhD Scholars | Scholars list, registration year, current stage |

---

## 6. Achievements & Recognition (Module 10)

| # | Screen | Key Elements |
|---|---|---|
| AC1 | Achievements List | Awards, talks, memberships, editorial roles |
| AC2 | Add Achievement | Form for award/talk/membership entry, proof upload |

---

## 7. Faculty Development & Growth (Module 11)

| # | Screen | Key Elements |
|---|---|---|
| FD1 | FDP List | FDPs attended, status, certificates |
| FD2 | Add FDP / MOOC / Workshop | Entry form, certificate upload |
| FD3 | International Visits | Visit details, institution, purpose |

---

## 8. Administrative & Lifecycle (Module 12)

| # | Screen | Key Elements |
|---|---|---|
| AD1 | Leave Records | Leave history, balance, apply leave |
| AD2 | Committee Roles | Roles held, tenure |
| AD3 | Exam Duties | Invigilation schedule, question paper prep deadlines |

---

## 9. Approval Workflow (Module 13)

| # | Screen | Key Elements | Role |
|---|---|---|---|
| AW1 | My Submissions | All submitted items, status (Pending / Approved / Rejected / Escalated) | Faculty |
| AW2 | Approval Queue | Items waiting for action, deadline countdown | HoD / Director |
| AW3 | Approval Detail | Full submission details, approve/reject action, comment field | HoD / Director |
| AW4 | Escalation Timeline | Visual escalation status: Day 0 → 3 → 7 → 10 | HoD / Admin |

---

## 10. PRAJNA Score Engine (Module 14)

| # | Screen | Key Elements |
|---|---|---|
| SC1 | Score Breakdown | Donut/bar chart: Teaching, Research, FDP, Achievements, Admin, Profile % |
| SC2 | Tier Progress | Current tier badge, points to next tier, visual progress bar |
| SC3 | Score History | Score over time chart |

---

## 11. Leaderboard (Module 15)

| # | Screen | Key Elements |
|---|---|---|
| LB1 | Department Leaderboard | Ranked list of faculty in same dept |
| LB2 | School Leaderboard | Ranked list across dept in same school |
| LB3 | Cross-Campus Leaderboard | All campuses, top performers |
| LB4 | Leaderboard Toggle | Monthly vs All-time switch |

---

## 12. AI Companion (Module 20)

| # | Screen | Key Elements |
|---|---|---|
| AI1 | Chat Interface | Conversational UI, context-aware responses, conversation history (private to faculty) |
| AI2 | Fallback State | Rule-based fallback UI when Bedrock is unavailable, clear status indicator |

---

## 13. Morning Briefing & End-of-Day (Module 21)

| # | Screen | Key Elements |
|---|---|---|
| MB1 | Morning Briefing Card | Daily agenda, AI-personalized, pushed at 8 AM |
| MB2 | End-of-Day Summary | Day recap, tasks completed, pending carry-overs |
| MB3 | Reflection Capture | Simple input to log end-of-day reflection |

---

## 14. Career Coach (Module 22)

| # | Screen | Key Elements |
|---|---|---|
| CC1 | Gap Analysis | Promotion criteria checklist, what's missing vs what's done |
| CC2 | Opportunity Spotter | Recommended conferences, grants, FDPs relevant to faculty's research area |
| CC3 | Workload Balance | Visual workload monitor, flag if overloaded |

---

## 15. Dynamic To-Do Engine (Module 23)

| # | Screen | Key Elements |
|---|---|---|
| TD1 | To-Do List | Prioritized daily task list — classes, assessments, approvals, deadlines |
| TD2 | Task Completion | Check off task, AI confirmation message, next task surfaced |
| TD3 | To-Do History | Completed tasks by date |

---

## 16. HoD Dashboard (Module 25)

| # | Screen | Key Elements |
|---|---|---|
| HD1 | Department Overview | Faculty count, active/inactive, PRAJNA score avg |
| HD2 | Approval Queue | Pending items, overdue flags |
| HD3 | Faculty Attention List | Faculty with low scores, overdue tasks, or compliance gaps |
| HD4 | Workload Balance View | Teaching load distribution across dept |

---

## 17. Director / Pro VC / IQAC Command Centre (Module 26)

| # | Screen | Key Elements | Role |
|---|---|---|---|
| DC1 | School-Level View | Faculty performance, dept breakdowns | Director |
| DC2 | Campus-Level View | School comparisons, campus health | Pro VC |
| DC3 | Inspection Readiness | 0–100% score per dept/school/campus, NAAC criterion-wise view | IQAC |
| DC4 | Faculty Activity Pulse | Real-time feed of faculty activity | Director / Pro VC / IQAC |
| DC5 | Top Performers | Leaderboard snapshot | Director / Pro VC |
| DC6 | Executive Summary | Weekly auto-generated summary card | Director / Pro VC |
| DC7 | Cross-Campus Benchmarking | Side-by-side campus comparison | Pro VC / Admin |

---

## 18. Notifications (Module 16)

| # | Screen | Key Elements |
|---|---|---|
| N1 | Notification Centre | In-app notification feed, read/unread state |
| N2 | Notification Settings | Toggle email / SMS / WhatsApp / in-app per event type |

---

## 19. APAR & Appraisal (Module 18)

| # | Screen | Key Elements | Role |
|---|---|---|---|
| AP1 | Self-Assessment Form | AI-suggested inputs, editable fields | Faculty |
| AP2 | Appraisal Status | Current stage: Self → HoD → Director, progress indicator | Faculty |
| AP3 | HoD Review Screen | View self-assessment, add comments, approve/send to Director | HoD |
| AP4 | Director Review Screen | Final sign-off, API score summary | Director |

---

## 20. Report Generator (Module 17)

| # | Screen | Key Elements |
|---|---|---|
| RG1 | Reports Home | Report types: NAAC / NBA / NIRF / Custom |
| RG2 | NAAC Report View | Criteria I–VII, auto-populated from live data |
| RG3 | NBA OBE Report | CO-PO mapping, programme outcome attainment |
| RG4 | NIRF Data View | Teaching, research, graduation outcomes |
| RG5 | Custom Analytics | Filters, date range, export options |
| RG6 | Export Screen | PDF / Excel download, preview before export |

---

## 21. Multi-Channel Integration (Module 27)

| # | Screen | Key Elements |
|---|---|---|
| MC1 | Channel Settings | Connect/disconnect WhatsApp, Email, Teams |
| MC2 | Sync Status | Which channels are active, last sync time |

---

## 22. Data Migration (Module 30)

| # | Screen | Key Elements |
|---|---|---|
| DM1 | Import Dashboard | Upload Excel, validation status, error list |
| DM2 | Data Verification | HoD sign-off view, flagged records, approve/reject |
| DM3 | Archive View | Pre-2020 historical records, read-only badge |

---

## 23. Security & Audit (Module 28)

| # | Screen | Key Elements |
|---|---|---|
| SA1 | Audit Trail | Immutable log of all data changes, actor, timestamp, before/after |

---

## 24. Admin (All Campuses)

| # | Screen | Key Elements |
|---|---|---|
| ADM1 | All-Campus Dashboard | High-level system health, cross-campus stats |
| ADM2 | User Management | Faculty/HoD/Director accounts, role assignment |
| ADM3 | Escalation Flags | Items escalated to Pro VC level, unresolved approvals |

---

## Screen Count Summary

| Group | Screens |
|---|---|
| Auth | 2 |
| Faculty Dashboard | 4 |
| Profile | 3 |
| Teaching | 6 |
| Research | 6 |
| Achievements | 2 |
| FDP & Growth | 3 |
| Admin & Lifecycle | 3 |
| Approval Workflow | 4 |
| Score Engine | 3 |
| Leaderboard | 4 |
| AI Companion | 2 |
| Morning Briefing | 3 |
| Career Coach | 3 |
| To-Do Engine | 3 |
| HoD Dashboard | 4 |
| Command Centre | 7 |
| Notifications | 2 |
| APAR & Appraisal | 4 |
| Report Generator | 6 |
| Multi-Channel | 2 |
| Data Migration | 3 |
| Security & Audit | 1 |
| Admin | 3 |
| **Total** | **83** |

---

## Priority Order for UX (suggested)

**P0 — Must have for Phase 1 launch**
Auth → Faculty Dashboard → Profile → Teaching → PRAJNA Score → To-Do → AI Companion Chat → Approval Workflow → HoD Dashboard → Notifications

**P1 — Core but can follow**
Research → FDP → Achievements → Leaderboard → Morning Briefing → APAR → Career Coach

**P2 — Power users / management**
Director/Pro VC/IQAC Command Centre → Report Generator → Admin Dashboard

**P3 — Infrastructure / ops**
Data Migration → Audit Trail → Multi-Channel → Monitoring
