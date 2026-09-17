# Empathising with the Users of an Academic Website

### User Personas & Customer Journey Maps for the academic section of the Indian Institute of Information Technology Senapati, Manipur

**Design Thinking Lab · B.Tech V Semester · July–Dec 2026**

| | |
|---|---|
| **Institution studied** | IIIT Senapati, Manipur — www.iiitmanipur.ac.in |
| **Submitted for** | Design Thinking Lab Assignment — Persona & Customer Journey Mapping |
| **Submission date** | 17 September 2026 |
| **Site observed on** | 17 September 2026 |
| **Scope** | Academic portion of the website only. Fee-payment gateways, tenders and procurement excluded, except where they interrupt an academic journey. |
| **Group** | ____________ |
| **Members** | ______________________________________________ |

**Part 1 — Current Students** · registration, results, calendar, regulations, placement & campus-life touchpoints
**Part 2 — Prospective Students & Parents** · discovery, JoSAA/CSAB decision-making, admission reporting and travel
**Part 3 — Administration & Faculty** · publishing notices, maintaining profiles, running academic and recruitment processes


---

## Contents

**Front matter** — A. Executive summary · B. Scope, method and evidence base · C. The Design Thinking process we followed
**Chapter 1 — Understanding the artefact** — 1.1 Information architecture · 1.2 Annotated snapshots · 1.3 Heuristic evaluation
**Part 1 — Current students** — personas · empathy map · journey map · pain points
**Part 2 — Prospective students and their parents** — personas · empathy map · journey map · pain points
**Part 3 — Administration and faculty** — personas · empathy map · journey map · pain points
**Chapter 5 — Synthesis** — affinity clustering · prioritisation · How-Might-We set
**Chapter 6 — Ideation and proposed redesign** — proposed IA · concept wireframes · roadmap and metrics
**Appendices** — A1 evidence log · A2 templates · A3 contribution sheet · A4 references

---

## A. Executive summary

The academic website of IIIT Senapati, Manipur is content-rich and, by the standards of a young institute, unusually transparent: fee structures, ordinances, cut-off ranks, syllabi, MoUs, faculty interests and admission logistics are all published openly. The difficulty is not that information is missing. It is that information is *organised around the institute's internal departments rather than around what a visitor is trying to do*, and that the same page must simultaneously serve a nervous seventeen-year-old in Jaipur, a third-year student hunting for an exam schedule, and a faculty member who wants a notice published before 4 p.m.

Working through the Design Thinking cycle — empathise, define, ideate — we built six personas across three user groups, mapped their journeys through the live site, and recorded where the emotional curve dips. Three findings repeat across all three groups:

1. **Announcements mix audiences** — student scholarships, vendor quotations and recruitment notices share one undated list.
2. **Academic services are scattered** across PDFs, a bare IP-address results portal and Google Forms.
3. **No role-based entry point** — every user starts from the same homepage and must know the org chart.

These are not cosmetic complaints. Each maps to a measurable friction: a prospective student comparing IIITs against a deadline, a current student who cannot confirm whether a notice is still valid, and an administrator who must answer by telephone what the website could have answered. The report closes with a proposed role-based information architecture, three concept wireframes and a phased roadmap that can be implemented without replacing the existing PHP site.

---

## B. Scope, method and evidence base

**Institution studied.** Indian Institute of Information Technology Senapati, Manipur — an Institute of National Importance established under the IIIT (PPP) Act, operating from its City Campus at Mantripukhri, Imphal, with a new campus under construction at Mayangkhang, Kangpokpi district. The institute runs six B.Tech programmes and a PhD programme across three departments (CSE, ECE, and Humanities & Basic Sciences).

**Scope boundary.** As the assignment requires, we restricted ourselves to the academic part of the website: admissions, courses and syllabi, departments, academic calendar, results, regulations and ordinances, scholarships, training & placement, student affairs, and faculty/administrative directories. The ICICI EazyPay fee-payment gateway, tender notices and procurement advertisements were examined *only* where they intrude into an academic journey — for example, where vendor quotation notices push student announcements down the homepage list.

**What we actually did.**

| Stage | Activity | Output used in this report |
|---|---|---|
| **Empathise** | Walk-through of 20+ pages of the live site on desktop and mobile widths; task-based traversal ("find the exam schedule", "find what to bring to the hostel"); informal conversations with five peers who have used an institute website in the last month; review of the published contact matrix to infer which questions are asked most often. | Observation notes, annotated snapshots (§1.2), empathy maps |
| **Define** | Clustering of observations into pain points; persona construction using a standard Design Thinking persona template (name, demographics, context, goals, frustrations, behaviours, quote); journey mapping using the six-column template (stage → touchpoint → action → thought → emotion → pain → opportunity). | Six personas, three journey maps, pain-point tables |
| **Ideate** | How-Might-We reframing of each high-severity pain point; affinity clustering across the three user groups; prioritisation on an impact-versus-effort matrix; low-fidelity wireframing of the three highest-value concepts. | HMW set, prioritisation matrix, wireframes (§6.2) |

> **A note on our epistemic limits.** We are outsiders to the institute's administration. Statements about what a member of staff *feels* or *does internally* are inferences, clearly built as personas, not claims about real named individuals. Where a pain point is directly observable on the public site (a dead menu item, an undated notice, a bare IP-address link) we mark it **[Observed]**. Where it is a reasonable inference from what is visible, we mark it **[Inferred]** and say what would confirm it.

---

## C. The Design Thinking process we followed

```
        PROBLEM SPACE                        SOLUTION SPACE
   ◇ Empathise → Define ◇            ◇ Ideate → Prototype ◇  → Test
   site walk-through,                 HMW, affinity,            (§6.3 plan)
   peer conversations,                prioritisation,
   personas, journey maps             wireframes, IA proposal
        └──────────── iterate: testing feeds back into empathy ────────────┘
```

*Figure C.1 — Double-diamond framing. The deliverables demanded by the rubric (personas, journey maps) sit at the narrow waist of the first diamond; we carry the work one step into the second diamond so that the empathy work visibly produces design consequences.*

**Why three parts, and why these three.** The assignment explicitly suggests that different users — students, faculty, parents of prospective students — will experience the same website differently. We organised the report around the three groups whose journeys are genuinely *structurally* different rather than merely demographically different:

- **Current students** return to the site repeatedly, in short bursts, usually on a phone, to complete a specific transactional task. Their relationship with the site is habitual and their tolerance for a broken link is low because they have nowhere else to go.
- **Prospective students and their parents** visit intensely for perhaps ten days of their lives, under deadline pressure, while comparing the institute against alternatives. They are evaluating, not transacting, and the site is competing for their trust. We treat the aspirant and the parent as two personas within one journey because they travel it together but look for entirely different things.
- **Administration and faculty** are the site's *authors* as well as its readers. Their pain points are about publishing, maintenance and the downstream cost of an under-served public page — every question the website fails to answer arrives instead as a phone call to a personal mobile number.

Treating them separately, then synthesising in Chapter 5, is what the rubric calls *inter- and intra-component coverage*: each part is complete in itself, and the parts are then read against one another.

---

# Chapter 1 — Understanding the artefact

Before mapping anybody's journey we had to establish what actually exists. This chapter documents the site's structure, illustrates four pages that recur in all three journeys, and scores the academic section against Nielsen's ten usability heuristics. Everything here is observation; interpretation begins in Part 1.

## 1.1 Information architecture of the academic section

The global navigation exposes eight top-level groups. Six of them contain academic content.

```
iiitmanipur.ac.in (Home)
├── About IIITM ............ about, mission & vision, PPP, governance, facilities, statute
├── ACADEMIC ★ ............. Admission (BTech/PhD) · Courses offered ×6 · Departments ×3
│                            · Results → 3 external IP links · Semester Exchange
│                            · Academic Calendar (PDF) · Holiday List (PDF)
├── CENTER/CELL/DIVISION ★ . Scholarships & Loans · Training & Placement · R&D/Projects
│                            · IPR · Innovation & Incubation · TEXMiN CoE · Alumni · NIR
│                            · RTI · Grievance Redressal · Anti-Ragging · POSH · NEP 2020
├── PEOPLE ★ ............... Teaching Staff · Administrative Staff · Technical Staff
│                            (individual faculty profile pages exist for only ~60%)
├── Resources .............. Gallery · Newsletter · 26 MoU PDFs · Auditorium booking
├── STUDENTS' CORNER ★ ..... Gymkhana Council · Testimonials · Activities & Events
│                            · Tech fests → 3 different external domains by year
├── Scholarships and Loans . (duplicate of a Center/Cell item, promoted to top level)
└── Payment Link ........... external ICICI EazyPay gateway

PLUS a second, parallel navigation in the page footer:
  About IIIT | Administration | Academics | Rules & Regulations | Cells/Center | Others
  — different labels, different grouping, and containing footer-only links:
    BTech Regulation · Hostel Regulation · Leave Rules · Code of Conduct · Forms and Essentials
```

**Observations on the structure**

- ★ marks a branch carrying academic content — six of the eight top-level groups qualify, so "academic" is not one place.
- Some paths leave the domain entirely: results open on a raw IP address; tech fests open on three different external domains by year.
- Many leaves are terminal PDFs: the answer is a downloaded file, not a web page — invisible to site search and awkward on a phone.
- Depth is inconsistent. An admitted student needing hostel rules travels Home → (footer) Rules & Regulations → PDF, but a student needing the academic calendar travels Home → Academic → Academic Calendar → Academic Year 2026 → PDF.

> **Counting the architecture.** Eight top-level menu groups · six of them contain academic material · three separate results portals addressed by IP · twenty-six MoU links inside a single menu · six B.Tech programmes each with a separate syllabus PDF · one payment link promoted to top-level navigation alongside "Academic" · zero site-wide search box.

## 1.2 Annotated snapshots of key pages

Four pages appear in more than one journey and are therefore illustrated here rather than being repeated in each part.

### Snapshot 1 — Homepage

`[SCREENSHOT — Figure 1.2]`
<img width="1920" height="921" alt="image" src="https://github.com/user-attachments/assets/a11174ba-325b-47ef-8da6-b4ac9c8377b9" />

**URL:** https://www.iiitmanipur.ac.in/index.php
*Capture the full page, then mark the five callouts below.*

**What the page contains (observed 17 Sep 2026):** bilingual masthead · blue navigation bar ending in an amber "Payment Link" · a scrolling admission-update marquee · a 13-slide rotating photo banner · Director's Message · "Quick Link" block · right-hand rail with Announcements, News and Achievements columns · embedded Google map · partner logo strip (Higher Education, DigiLocker, RTI, e-Yantra, Make in India, SWAYAM, Scholarships) · six-column footer mega-menu.

| # | What we observed | Why it matters to a journey |
|---|---|---|
| **1** | "Payment Link" is promoted to the top-level navigation bar, at the same level as "Academic" and "People". | The most visually emphasised action on the site is transactional, not informational. A prospective student who has not yet decided sees a payment call before a "Why study here" call. |
| **2** | The Announcements list mixes audiences: a PhD admission call, three vendor quotation notices, a faculty recruitment advertisement, a student internship opening and a student scholarship — in one undated, unfiltered column. | A student scanning for something relevant must read and reject vendor notices. A parent reads "Quotations invited for water geysers" as the institute's most current news. Items whose deadlines passed weeks ago still carry a "new" flag. |
| **3** | The News column runs roughly forty items back to 2023 with no date grouping, no pagination and no "archive" split. | Recency cannot be judged at a glance, so the homepage stops functioning as a status signal. Both students and parents told us they scroll past it entirely. |
| **4** | Thirteen rotating banner slides occupy the primary visual position; each is a photograph with a caption, not a task entry point. | The most valuable screen real estate carries ceremonial content. Nothing above the fold helps a visitor *do* anything. |
| **5** | "Quick Link" duplicates About-Us items rather than surfacing frequent tasks; results, calendar, syllabi and regulations are absent from it. | The block named for speed does not contain the fast paths. The genuinely frequent destinations sit three clicks deep or in the footer. |

### Snapshot 2 — B.Tech Admission page

`[SCREENSHOT — Figure 1.3]`
<img width="1917" height="929" alt="image" src="https://github.com/user-attachments/assets/49bb35c3-c557-48c8-9704-4d57b9fedcb0" />
**URL:** https://www.iiitmanipur.ac.in/pages/academic/admission.php
*Capture in two or three overlapping screenshots — the page is a single long scroll.*

**What the page contains, in order:** greeting to students who have already been allotted a seat · fee-payment deadline (15 Aug, revised to 17 Aug 2026, both dates shown) · four fee/payment links plus a mandatory Google Form · physical reporting dates 16–17 Aug with document list and two anti-ragging affidavits · dress code · hostel packing note · induction 18–22 Aug and classes from 24 Aug · travel advisory (flights via Kolkata/Guwahati, ILP guidance, airport shuttle, six taxi numbers, ≈₹600 fare) · refund policy · complete fee detail PDFs · scholarship and loan links · programme list with JoSAA/CSAB codes and intake (CSE 4110/110, CSE-AI&DS 410R/110, CSE-Cyber Security 4195/55, CSE-Quantum 413H/55, ECE 4114/110, ECE-VLSI&ES 410M/110; institute code 313) · section-wise contact table of named faculty with personal mobile numbers · cut-off PDFs for five years · four syllabus PDFs · "How to reach" map.

| # | What we observed | Why it matters to a journey |
|---|---|---|
| **6** | The page opens by addressing students who have *already* been allotted a seat ("Congratulations on … having got admission"), and leads with a fee deadline that has been revised once in place. | A student still deciding between institutes lands on a page written for someone past that decision. The comparison information she needs — cut-offs, syllabus, placement record — sits far below the fold, under the joining logistics. |
| **7** | Post-allotment steps are distributed across four PDFs, an external payment gateway, and a Google Form, in prose paragraphs rather than a numbered sequence with statuses. | Neither the student nor the parent can tell how many steps remain or whether a step succeeded. Confirmation arrives later by e-mail, so the site itself never closes the loop. |
| **8** | **[Strength]** The travel advisory is genuinely empathetic: it anticipates the ILP question, the landslide risk on the highway, the airport shuttle, the taxi fare, even the mosquito net and the bucket. | This paragraph proves the institute already understands its users' anxieties. The design problem is that this quality of thinking is applied to one paragraph and not to the structure around it. |
| **9** | Eight personal mobile numbers are the published fallback for fees, hostel, scholarship, placement, student affairs and admission queries, with a 10 a.m.–5 p.m. calling window. | Every gap in the page converts into a phone call to a named faculty member. This is the clearest link between a public-website weakness and an internal administrative cost — picked up again in Part 3. |

### Snapshot 3 — Teaching Staff directory

`[SCREENSHOT — Figure 1.4]`
<img width="1917" height="929" alt="image" src="https://github.com/user-attachments/assets/ee26855d-0e4a-4e20-9b74-60d9827e7be1" />

**URL:** https://www.iiitmanipur.ac.in/pages/people/staffTeaching.php

**What the page contains:** a single alphabetical column of roughly 26 faculty entries, each with photo, name, qualifications, designation and department, research interest area, and an obfuscated e-mail address; some entries carry a "View Profile" link, others do not.

| # | What we observed | Why it matters to a journey |
|---|---|---|
| **10** | Entries are alphabetical by first name, not grouped by department, designation or research area; department is a link inside the free text rather than a filter. | A student looking for a project supervisor in NLP, or a prospective PhD applicant looking for a matching area, must read all twenty-six entries. Departmental pages do not carry their own faculty roster either. |
| **11** | "View Profile" is present on some entries and absent on others; profile pages live at URLs containing spaces (`/pages/FACULTY PROFILE/…`). | Inconsistent depth makes faculty look unevenly active to an outside evaluator, and the spaces in paths break when links are copied into WhatsApp or e-mail — the channels students actually use. |
| **12** | Email addresses are obfuscated as `name[at]iiitmanipur[dot]ac[dot]in`; there is no course-taught field, no office hours, no room number. | A defensible anti-spam choice that nonetheless adds friction for the legitimate user, who must retype rather than click. The absence of "teaches this semester" pushes routine student questions back to the classroom or WhatsApp. |

### Snapshot 4 — Results, calendar and the PDF perimeter

`[SCREENSHOT — Figure 1.5]`
**URLs:** the Academic ▸ Results submenu, and any one of
`http://14.139.202.226/23batchresult/` · `http://14.139.202.226/20batchresult/` · `http://14.139.202.226/resultPortal/`
*Capture the browser's "Not secure" warning in the address bar — it is part of the finding.*

**Results:** three portals split by admission year, addressed by raw IP over plain HTTP, with a separate login screen, no institute branding and no link back to the site. Students must know which of the three matches their admission year.

**The PDF perimeter — answers that are files, not pages:**
`ACADEMIC CALENDER 2026.pdf` · `List of Holidays 2026.pdf` · `ORDINANCES_AND_REGULATIONS_BTECH_2023.pdf` · `hostelrules.pdf` · `Leave-Rules.pdf` · `Ordinance.pdf` · `SyllabiCSE2023.pdf` · `SyllabiCSEAID2023.pdf` · `SyllabiECE2023.pdf` · `SyllabiECEVLSI2023.pdf` · `FeeSstructure2026_27.pdf` · `RankList2024.pdf`

> **Why the PDF perimeter shapes every journey in this report.** Once an answer becomes a PDF it leaves the web: it cannot be searched from the site, it does not respond to a phone screen, it carries no visible "last updated" stamp in the link, and it cannot be deep-linked to the one clause the reader needs. Two links illustrate the resulting drift — the footer "Academic Calendar" points to a 2022 file while the top menu points to the 2026 file. Both links are live, both look authoritative, and nothing on either page tells the reader which one is current.

## 1.3 Heuristic evaluation

Scored against Nielsen's ten heuristics on a 1–5 scale (5 = no issues found). This complements the journey work: heuristics tell us what is wrong with the interface, journeys tell us what it costs a person.

| Heuristic | Score | Finding |
|---|---|---|
| 1. Visibility of system status | **2** | Notices carry a "new" flag long after their deadline; no dates on announcements; admission steps give no progress state; PDFs have no revision stamp. |
| 2. Match with the real world | **3** | Labels follow the institute's org chart ("Center/Cell/Division", "Students' Corner") rather than user goals ("Exams", "Fees", "Apply"). The travel advisory is a strong counter-example, written entirely in the user's language. |
| 3. User control and freedom | **3** | Results portals and tech-fest sites open without breadcrumbs or a return path. The rotating banner cannot be paused. |
| 4. Consistency and standards | **2** | Two navigation systems with different labels; "Academic Calendar" resolves to two different files; some faculty have profile pages, some do not; URLs mix conventions and contain spaces. |
| 5. Error prevention | **3** | "Fill 0 wherever not applicable in the payment gateway" is a correct instruction that exists because the form invites a foreseeable error. The three results portals invite a wrong-portal error by design. |
| 6. Recognition over recall | **2** | Students must recall which batch-portal, which syllabus year, and whether a rule lives in the top menu or the footer. No site search exists to compensate. |
| 7. Flexibility and efficiency | **2** | No role-based landing page, no personalised dashboard, no saved state; the returning student and the first-time visitor follow identical paths. "Quick Link" does not contain the frequent tasks. |
| 8. Aesthetic and minimalist design | **3** | Dense homepage columns and a forty-item news list compete for attention; important items are emphasised with red text, capitals and animated "new" icons simultaneously, which erodes the emphasis. |
| 9. Error recovery | **3** | No custom 404 handling observed; an expired notice simply remains, so the reader must diagnose staleness themselves. |
| 10. Help and documentation | **4** | Genuinely good: contact matrix by topic, detailed travel advisory, explicit document checklists, published refund policy and ordinances. The weakness is findability, not existence. |

> **The pattern in one sentence.** The institute is better at *answering* questions than at *organising* answers — which is exactly the failure mode Design Thinking addresses, because organisation is where the user's mental model, rather than the publisher's, has to win.

---

# PART 1 — The Current Student

*Eight semesters, a phone with patchy data, and a site they visit the way one visits a utility cupboard — quickly, for one thing, usually in a hurry.*

Current students are the site's heaviest users and its least romantic ones. They do not browse; they arrive with a task ("when does the semester end", "where is the ordinance clause on re-examination", "which company is coming next week") and they leave the moment it is done or the moment they conclude the site cannot do it. Their most important behaviour, from a design point of view, is **abandonment to WhatsApp**: when the site fails, the question is asked in a class group, an answer of unknown reliability is received, and the website loses that user for that class of question more or less permanently.

## P1.1 Personas

### Persona 1A — Rohit Meena, "just tell me the date"

**The out-of-state undergraduate · 20 years · 5th semester B.Tech CSE (AI & DS)**

**Background.** From Kota, Rajasthan. Allotted IIIT Manipur in the third JoSAA round; had never travelled east of Kolkata before joining. Lives in the Mantripukhri hostel. Father runs a small electrical-goods shop; Rohit is on a state post-matric scholarship and re-applies every year.

| Digital behaviour | Goals | Frustrations |
|---|---|---|
| Phone-first, ~85% of site visits on mobile data · uses the class WhatsApp group as his real notice board · bookmarks nothing, re-searches Google for "iiit manipur result" each time · screenshots PDFs rather than downloading them | Know exam, registration and vacation dates early enough to book trains home · check results the hour they are declared · keep his scholarship renewal on track · find which companies are visiting and the eligibility CGPA · find a faculty member working on machine learning who might supervise a project | Three results portals; he can never remember whether he is "2023 batch onwards" · the browser warns "Not secure" — he assumes it is a phishing page the first time · the academic calendar is a PDF that renders at thumbnail size on his phone · announcements are full of vendor quotations, so he has stopped reading them · nothing tells him whether a July notice is still in force |

**Needs from the site:** one dated, student-only notice stream; dates as text, not as an image of a table.

> *"I don't go to the website to find out things. I go to confirm what somebody already told me in the group — and half the time I can't even confirm it, so I just believe the senior."*

### Persona 1B — Thoibi Devi, "I'm the one people ask"

**The local student & Gymkhana volunteer · 21 years · 7th semester B.Tech ECE (VLSI & ES)**

**Background.** From Imphal West; a day scholar for two years, now in the hostel. Active in the Gymkhana Council and on the organising team for the annual tech fest. Because she is local and senior, juniors and their parents route questions through her — about hostels, about ILP, about whether classes are running.

| Digital behaviour | Goals | Frustrations |
|---|---|---|
| Laptop for organising work, phone for everything else · keeps a personal folder of institute PDFs because she cannot find them again reliably · shares links, and notices that links with spaces break in WhatsApp | Get fest and club events onto the official site so they look institutional · point juniors at an authoritative page instead of retyping the same answer · show a verifiable record of her extracurricular role when applying for internships · track placement activity for her own final-year planning | Each year's tech fest lives on a different external domain; last year's site is effectively lost · student activity pages are updated rarely, so she cannot cite them · there is no route for a student body to publish anything · answering the same five questions by phone during admission week |

**Needs from the site:** a stable, archived events section; a student-facing FAQ she can send instead of typing.

> *"Every August I become the help desk. If the site answered those questions properly I'd get my evenings back — and the juniors would trust the institute instead of trusting me."*

## P1.2 Empathy map — current students

| SAYS | THINKS |
|---|---|
| "Bhai, calendar ka link bhejo" · "Just screenshot it and put it in the group." · "Check with the CR, he'll know." · "The site has it somewhere, I just can't find it." · "Don't open that on college wifi, it won't load." · "Which sir do I mail for this?" | "Is this notice still valid or is it from last July?" · "Which portal am I — 2023 batch or 2020 batch?" · "If it isn't on WhatsApp it hasn't happened." · "The seniors know this better than the website does." · "I'll ask sir directly, it's faster." · "Is the calendar PDF the 2026 one or the old one?" |
| **DOES** | **FEELS** |
| Googles "iiit manipur result" instead of navigating the menu · screenshots PDF pages and crops the relevant row · keeps a private WhatsApp archive of notices · asks a senior before asking the site · opens the site, scrolls past the banner, scrolls past News · emails a faculty member whose address he retypes by hand | Anxious before results, because the portal is unfamiliar · distrustful of the "Not secure" browser warning · resigned — "that's just how it is here" · slightly embarrassed sharing the site with outside friends · proud when peers' achievements appear on the homepage · frustrated at re-finding the same PDF for the fourth time |

**PAINS** — cannot judge whether information is current · wrong-portal risk at the most emotionally loaded moment · mobile rendering of PDFs · announcements diluted by procurement and recruitment items · no single place that says "you, this semester, must do this" · no site search to recover from a wrong turn.

**GAINS** — results and dates reliably first-hand · a dated student notice stream they can trust and cite · calendar as a readable page with an "add to calendar" file · faculty directory filterable by research area · placement information current enough to plan around · a site they are willing to show to a recruiter or a friend.

## P1.3 Journey map

**Scenario.** Rohit has heard in the class group that end-semester examinations may start a week earlier than expected. He wants to (a) confirm the date from an official source, (b) check the last date of course registration for the next semester, (c) see whether a placement drive clashes, and (d) find a faculty member for his AI project. He has fifteen minutes and 4G on his phone.

**Emotion curve** (−2 … +2)

```
 +2 |                                                                  ●  6. Give up
 +1 |  ● 1. Trigger                      ● 4. Results                 ╱     (relief — from a
  0 |─────────────────────────────────────────────────────────────╱──────   peer, not the site)
 -1 |            ● 2. Arrive                          ● 5. Placement
 -2 |                      ● 3. Hunt  ← lowest point
     1.Trigger   2.Arrive   3.Hunt    4.Results   5.Placement   6.Exit
```

*The curve ends high for the wrong reason: the task is completed **outside** the website, which is precisely how the site loses its authority.*

| Stage | Touchpoint | Action | Thought & emotion | Pain point | Opportunity |
|---|---|---|---|---|---|
| **1. Trigger** — rumour of an earlier exam date | WhatsApp class group (off-site) | Reads an unsourced message; decides to verify | "This is probably true but I'm not booking a ₹3,000 ticket on a rumour." — alert, mildly anxious | The first touchpoint of an academic journey is not the academic website. The site has already lost the initiative. | Push authoritative dates to where students already are: a dated notice page with a stable, shareable URL and an RSS/Telegram mirror. |
| **2. Arrive** — opens the homepage on mobile | `/index.php` | Scrolls past the 13-slide banner; scans Announcements; scans News | "Water geysers… tent and event management… where is the student stuff?" — impatience | Mixed-audience announcement stream; no dates; "new" flags on expired items; no student filter. | Split the stream into *For Students* / *Admissions* / *Recruitment* / *Tenders*, each item dated and auto-expiring. |
| **3. Hunt** — looks for the academic calendar | Academic ▸ Academic Calendar ▸ Academic Year 2026 → PDF | Three menu levels, then a PDF opens in the mobile viewer; pinches to read a dense table | "Why is this a PDF? Is this even 2026? The footer link gave me a 2022 file." — confusion, then distrust | **[Observed]** Duplicate, divergent calendar links between top menu and footer; PDF-only delivery; no last-updated stamp. | Publish the calendar as an HTML page with a semester switcher, a downloadable .ics, and a single canonical link used everywhere. |
| **4. Results** — checks last semester's grade | Academic ▸ Results ▸ "2023 Batch onwards" → `http://14.139.202.226/…` | Guesses which of three portals applies; browser shows "Not secure"; logs in on a differently-styled site | "Is this actually ours?" — suspicion, then mild relief | **[Observed]** Three portals split by admission year; raw IP; no TLS; no branding; no path back. | One portal behind a named subdomain with TLS, institute branding, batch detected from the roll number, and a breadcrumb home. |
| **5. Placement & faculty** | T&P Cell pages; `/pages/people/staffTeaching.php` | Looks for upcoming drives and eligibility; then reads 26 faculty entries hunting for "machine learning" | "I can't tell if this placement page is from this year. And I'm reading every single profile." — fatigue | No dated drive calendar; faculty list unfilterable by area, department or course taught; some profiles missing. | Dated T&P calendar with eligibility fields; faculty directory with filters for department, research area and courses taught this semester. |
| **6. Exit** | Back to WhatsApp | Asks the class representative; gets an answer in four minutes | "Should have just asked first." — relief, and a lesson learned about the website | Abandonment is *rewarded*. Each cycle strengthens the informal channel and weakens the official one. | Design for the CR: give student representatives a one-page "this week" digest they can forward, sourced from the site. |

## P1.4 Pain points, ranked

| ID | Pain point | Evidence | Severity | Frequency | Design consequence |
|---|---|---|---|---|---|
| **S1** | Cannot establish whether information is current (undated notices, expired "new" flags, two different calendar files) | Observed | High | Every visit | Mandatory publication date + review date on every item; automatic expiry; one canonical link per document. |
| **S2** | Results split across three IP-addressed, non-TLS portals with no branding | Observed | High | 2–3× per semester, high stakes | Consolidate to one branded, secure portal; detect batch from roll number. |
| **S3** | Core academic answers are PDFs, unreadable on a phone and invisible to search | Observed | High | Weekly | HTML-first publishing with PDF as the printable companion. |
| **S4** | Student notices diluted by vendor and recruitment notices | Observed | Medium | Every visit | Audience-tagged streams with filters; "For students" as the default view. |
| **S5** | No site-wide search; recovery from a wrong turn means starting over | Observed | High | Every visit | Add search covering pages *and* the text inside PDFs. |
| **S6** | Faculty directory cannot be filtered by area, so project supervision search is linear | Observed | Medium | Once or twice a year, but decisive | Faceted directory; "accepting project students" flag. |
| **S7** | Student activity and tech-fest history scattered across external domains | Observed | Medium | Seasonal | Permanent events archive on the institute domain; student-body submission route. |
| **S8** | Links with spaces in the URL break when shared on messaging apps | Observed | Low | Frequent | URL hygiene: lowercase, hyphenated, no spaces; add "copy link" affordances. |

**How-Might-We statements arising from Part 1**

- **HMW-S1** — How might we let a student tell, in under three seconds and without asking anyone, whether what they are reading still applies?
- **HMW-S2** — How might we make checking a result feel as safe and official as receiving a sealed envelope?
- **HMW-S3** — How might we deliver the academic calendar so that it works on the device a student actually holds?
- **HMW-S5** — How might we let a student who has taken a wrong turn find the right page without returning to the homepage?
- **HMW-S6** — How might we help a student find the right faculty member for their project in one screen rather than twenty-six?

---

# PART 2 — The Prospective Student & the Parent

*Ten days of intense, deadline-driven evaluation, conducted by two people with the same goal and completely different questions — and a website that is the institute's only sales representative.*

This is the highest-stakes journey on the site and the shortest. A JoSAA candidate will visit the institute's website perhaps a dozen times in her life, almost all of them inside a two-week window, while simultaneously comparing five to eight institutes. Her parent will visit the same pages looking for entirely different signals. Neither has any prior relationship with the institute, so every ambiguity is read as a risk, and the competition is one browser tab away. The travel distance amplifies everything: a family in Rajasthan or Andhra Pradesh deciding on Imphal is making a decision about safety, climate, food, connectivity and two-day journeys, not only about a CSE seat.

We model the aspirant and the parent as two personas inside a single journey because they travel it together — usually on the same evening, often on the same screen — and because the site currently serves the aspirant's questions partially and the parent's questions hardly at all.

## P2.1 Personas

### Persona 2A — Ananya Verma, "is this the right choice or just the available one?"

**JEE (Main) qualified aspirant · 18 years · Jaipur, Rajasthan**

**Background.** Her percentile places her in the band where IIIT Manipur CSE and CSE–AI&DS are realistic, alongside a couple of state NITs and a private university closer to home. She is in JoSAA choice-filling week. She has never been to the North-East and knows about Manipur mainly from news headlines.

| Digital behaviour | Goals | Frustrations |
|---|---|---|
| Six tabs open: JoSAA, two institute sites, a YouTube campus tour, a Quora thread, a Telegram counselling channel · judges credibility in seconds from visual polish and recency · trusts student voices over institutional prose | Decide how to order IIIT Manipur among her JoSAA choices · understand what the specialisations (AI&DS, Cyber Security, Quantum Technologies, VLSI&ES) actually contain · see last year's closing ranks for her category · see real placement outcomes — median, not the maximum package · see what the campus and hostel actually look like today | The admission page congratulates her on an admission she has not yet received · cut-offs are scattered across five year-wise PDFs plus an external JoSAA link · syllabus PDFs are named "2023" — she cannot tell whether they are current · the homepage's most recent visible signal is a vendor quotation · two campuses are mentioned; she cannot tell which one she would live on |

> *"I'm not scared of it being far. I'm scared of not being able to find out what it's actually like — and the website keeps showing me photographs of ceremonies instead of answering that."*

### Persona 2B — Mr. Suresh Verma, "will she be safe, and can we afford it?"

**Parent of a prospective student · 49 years · Jaipur · Bank branch manager**

**Background.** Finances the decision and carries the anxiety. Reads English comfortably but is not a fluent web navigator; prefers documents he can print, sign and file. Will call a phone number before he will fill a web form. Has read news about unrest in Manipur and needs to be reassured by facts rather than by silence.

| Digital behaviour | Goals | Frustrations |
|---|---|---|
| Desktop, large text, prints PDFs · verifies claims by telephoning a listed number during office hours · cross-checks the institute against government sites (NIRF, Ministry of Education, scholarship portals) | Total four-year cost including hostel, mess and non-refundable charges · which loans and scholarships apply, and what the institute will certify · hostel arrangement, mess, medical facility, warden contact · travel logistics: how a family reaches Imphal, what an ILP is, how long the journey takes · refund position if the seat is later withdrawn · evidence that academics are running normally | Fee information is split across "Fee structure", "Remaining fee to be paid" and "Payment form" PDFs; he cannot compute a single four-year number · no page is addressed to him; everything speaks to the student · contact is by personal mobile, 10 a.m.–5 p.m., not an office line · no student-welfare, medical or counselling page he can point to |

> *"I don't need marketing. I need one page that tells me the total amount, who my daughter's warden is, and which number I call at eleven at night if something happens."*

## P2.2 Empathy map — the deciding family

| | ASPIRANT | PARENT |
|---|---|---|
| **Thinks & feels** | "Rank 4 or rank 7 in my choice list? I have two days." · "Quantum Technologies sounds impressive — but who teaches it?" · "Everyone quotes the 46 LPA offer. What did the median student get?" · "Is the campus the one in the photos or the one being constructed?" · "There's a testimonials page — is it from this year?" · "If I don't like it, how much money do we lose?" — *urgency, FOMO, self-doubt, fear of a four-year mistake* | "What is the total for four years, all inclusive?" · "Who is responsible for her once she is inside the gate?" · "Two days of travel each way. What if there is an emergency?" · "Is the institute government or private? PPP — what does that mean?" · "Will the SBI or Canara loan actually be sanctioned for this institute?" · "Everyone says call this number — is there an office line?" — *protectiveness, financial caution, need for an authority figure* |
| **Says & does** | Opens the site, then opens two competitor sites in parallel tabs · searches YouTube for a student vlog because the site has no video tour · asks in a Telegram counselling group · downloads four cut-off PDFs and compares them manually · screenshots the fee page and sends it to her father · gives the site roughly ninety seconds before judging it | Prints the fee-structure PDF and the refund policy · telephones the published mobile number during working hours · asks a relative who has been to the North-East · checks the Ministry of Education and scholarship portals separately · asks the aspirant to "find the hostel photos again" · keeps a physical folder of every document downloaded |

**SHARED PAINS — where the site leaves the family without an answer**

- No single "total cost of attendance" figure — three fee PDFs must be reconciled by hand.
- No page addressed to parents at all; no welfare, medical, counselling, warden or emergency-contact page.
- Placement evidence is anecdotal (individual offers, individual congratulations) rather than statistical by branch and year.
- Campus ambiguity: City Campus at Mantripukhri versus the campus under construction at Mayangkhang — never stated plainly on one page.
- Recency signals are weak, so a family already nervous about the region cannot confirm that academics are running normally.
- Every unanswered question converts into a phone call to a personal mobile number, available only 10 a.m.–5 p.m.

## P2.3 Journey map

**Scenario.** Ananya's JoSAA choice filling closes in 48 hours. Over the following three weeks — if she is allotted a seat — the same website must carry her and her father from evaluation through acceptance to physical reporting in Imphal.

**Emotion curves** (aspirant ——, parent - - -)

```
 +2 |                          ●4                                   ●7
 +1 |  ●1                     ╱  ╲                            ●6  ╱
  0 |────╲────────────────────────╲────────────────────────╱─────────
 -1 |     ●2        ╲              ╲        ●5           ╱
 -2 |                ●3 ← lowest: decides on hearsay
     1.Discovery 2.Evaluate 3.Compare 4.Allotment 5.Accept 6.Prepare 7.Report
```

*The parent's curve runs consistently below the aspirant's: the site gives him fewer answers at every stage, and the gap is widest at "Compare".*

| Stage | Touchpoint | Action | Thought & emotion | Pain point | Opportunity |
|---|---|---|---|---|---|
| **1. Discovery** | JoSAA choice list; Google; `/index.php` | Sees the institute name and code 313; opens the homepage to find out what it is | "Institute of National Importance, established 2015 — good. But what is it *like*?" — curious, sceptical | The homepage explains governance and ceremony but does not answer "why study here": no programme overview above the fold, no outcome data, no student voice. | A "Why IIIT Manipur" block above the fold: six programmes, intake, last year's closing ranks, placement summary, campus photos, one student video. |
| **2. Evaluate** | `/pages/academic/admission.php`, `/coursesOffered.php` | Reads the admission page top to bottom; opens cut-off PDFs; opens syllabus PDFs | "This page thinks I've already joined." — disorientation | **[Observed]** One page mixes pre-decision and post-allotment content; the current batch's fee deadline dominates; cut-offs split across five PDFs; syllabi labelled 2023. | Split into *Considering* (programmes, ranks, outcomes, life) and *Admitted* (fees, documents, reporting). One cut-off table, all years, all categories, filterable. |
| **3. Compare** | Placement pages; testimonials; gallery; competitor sites; Telegram | Tries to benchmark outcomes and campus life; fails; asks strangers online | "I'll go with what people in the group say." — anxiety, then resignation | **[Observed]** Placement evidence is anecdotal; no branch-wise median/placement-percentage table; testimonials undated; no parent-facing welfare or safety information; campus ambiguity. | Publish a dated placement statistics table by branch and year; add a student-life section with current photos and dated testimonials; one clear page on the two campuses. |
| **4. Allotment** | JoSAA portal, then the institute site | Receives the provisional allotment; returns to find out what to do next | "Now it's real." — elation followed by urgency | The site does not detect or acknowledge the transition; she must re-read the same long page and extract the steps that now apply to her. | An "I have been allotted a seat" entry point leading to a numbered, dated checklist. |
| **5. Accept** | Fee PDFs → ICICI EazyPay → Google Form → e-mail confirmation | Pays online, fills the mandatory Google Form, uploads documents, waits for an e-mail | "Did that go through? Should I pay the remaining amount now or after?" — acute anxiety | **[Observed]** Three separate fee documents; deadline revised in place with the old date still shown; hand-offs to two external systems; confirmation only by e-mail; the instruction to "fill 0 wherever not applicable" reveals a form that invites error. | One status page per candidate: steps, amounts due, what has been received, what remains. Even without integration, a static checklist with expected timelines removes most of the fear. |
| **6. Prepare** | Travel advisory; document list; hostel note; dress code | Books flights via Kolkata; arranges the ILP question; buys a mosquito net and bedding | "They've actually thought about this." — reassurance **[Strength]** | Excellent content, but buried at the bottom of a long page and not packaged as a printable joining kit. The parent wants it as one signed, filed document. | A single downloadable "Joining Kit": checklist, documents, affidavits, packing list, travel, contacts, campus map, first-week schedule. |
| **7. Report** | Physical campus; volunteers; induction 18–22 Aug; classes from 24 Aug | Arrives on the reporting date; is met by volunteers; attends induction | "It matched what the site said." — relief and belonging | The offline experience is well organised; the website under-claims it. Nothing online shows the induction programme or the first-week timetable in advance. | Publish the induction schedule in advance; close the loop with a "what your first week looks like" page. |

## P2.4 Pain points, ranked

| ID | Pain point | Evidence | Severity | Who feels it | Design consequence |
|---|---|---|---|---|---|
| **P1** | The admission page serves post-allotment logistics to a pre-decision audience | Observed | High | Aspirant | Split "Considering" from "Admitted"; make the first one the default destination in the menu. |
| **P2** | No consolidated cost of attendance; three fee documents plus a payment gateway | Observed | High | Parent | One fee page, one table, four-year projection, refund terms alongside. |
| **P3** | No parent-facing content: welfare, medical, hostel wardens, counselling, emergency contact | Observed | High | Parent | A "Parents" section, linked from the admission page and the footer. |
| **P4** | Placement claims are anecdotal, not statistical or dated | Observed | High | Both | Annual dated placement report: registered, placed, median, branch-wise, recruiters. |
| **P5** | Cut-offs fragmented across five year-wise PDFs and an external link | Observed | Medium | Aspirant | One filterable closing-rank table with a "compare with last year" view. |
| **P6** | Acceptance flow hands off to two external systems with no status feedback | Observed | High | Both | Checklist with expected confirmation timelines; publish "you will receive an e-mail within N days". |
| **P7** | Campus ambiguity between the City Campus and the campus under construction | Inferred | Medium | Both | One page: where you will live and study in your first year, with photographs and a timeline for the new campus. |
| **P8** | Recency cannot be verified, which matters disproportionately for a region in the news | Observed | High | Parent | Dated notices, a visible academic calendar, and a plainly-worded current-status statement. |
| **P9** | Support is personal mobile numbers with a 10 a.m.–5 p.m. window | Observed | Medium | Both | Role-based addresses and an office line; a published FAQ that removes the most common calls. |

**How-Might-We statements arising from Part 2**

- **HMW-P1** — How might we let a candidate who has *not yet decided* feel that the site was written for her?
- **HMW-P2** — How might we show a family the true four-year cost on one screen, with no arithmetic?
- **HMW-P3** — How might we answer a parent's safety and welfare questions before he has to telephone a stranger?
- **HMW-P4** — How might we make outcome evidence verifiable rather than anecdotal?
- **HMW-P6** — How might we make an admitted student certain, at every step, that her acceptance has gone through?

---

# PART 3 — Administration & Faculty

*The people who are simultaneously the site's authors and its most constrained users — and who absorb, in telephone calls, every question the website fails to answer.*

The first two parts looked at people who read the website. This part looks at the people who *are* the website. At an institute of this size there is no dedicated web team; publishing is an additional duty carried by faculty and a small administrative staff alongside teaching, research, admissions and accreditation. That single fact explains most of what the first two parts observed: the undated notices, the divergent calendar links, the profile pages that exist for some faculty and not others, the results portals on an IP address. These are not carelessness. They are the visible residue of a publishing process that has no queue, no template, no expiry and no owner of record.

> **Method note for this part.** We cannot observe internal workflows from outside. The personas below are constructed from what the public site reveals about its own production — the contact matrix that names a faculty member for each category of query, the rolling recruitment advertisement, the vendor quotation notices published alongside student notices, the mixed URL conventions that indicate several hands editing over several years, and the parallel top/footer navigations that suggest edits made in one place and not the other. Every inference is marked **[Inferred]** and paired with the observation that supports it.

## P3.1 Personas

### Persona 3A — Dr. Sanjana Kharibam, "publishing is my seventh job"

**Assistant Professor, CSE · 38 years · also Academic Coordinator and member of the admission contact matrix**

**Background.** Teaches two courses a semester, supervises a funded project, sits on the Board of Studies, and is the named point of contact for academic queries during admissions. Her mobile number is published on a public page, so from June to September her phone rings from unknown numbers all day.

| Context of use | Goals | Frustrations |
|---|---|---|
| Sends notices to whoever maintains the site, usually as a Word file or a scanned PDF, by e-mail · has no ability to publish, correct or withdraw anything herself · cannot see what is currently live without visiting the public page as any visitor would | Get an examination or registration notice in front of students the same day · keep her faculty profile and publication list current so it helps with funding and PhD applicants · attract good research students by making her area visible · reduce the volume of repetitive telephone queries · have accurate, citable academic records for NIRF/NBA and Senate reporting | Round-trip delay between sending a notice and seeing it published; no way to verify it went up correctly · corrections require another round trip, so errors persist (a revised deadline is added *next to* the old one rather than replacing it) · no archive discipline: her notice sits below vendor quotations within a week · her profile page format differs from colleagues'; some have none at all · students say "it wasn't on the website", and she cannot prove otherwise |

> *"I can design a semester-long course but I cannot change one date on a page with my own name on it. So I send a mail, and then I answer forty phone calls while I wait."*

### Persona 3B — Mr. N. Priyokumar Singh, "everything routes through me"

**Administrative officer, Academic Section · 44 years · de-facto website custodian**

**Background.** Handles academic records, admissions correspondence, notices, and — because no one else does — updates to the institute website, alongside procurement paperwork. Comfortable with office software; edits pages through whatever access he was handed, without a content management system, style guide or review workflow.

| Context of use | Goals | Frustrations |
|---|---|---|
| Receives content in many formats from many senders, often with "publish urgently" · publishes by adding to the top of an existing list; removing things is riskier than leaving them · no staging environment, so edits are made live | Get statutory and deadline-bearing notices online quickly and without error · never be the reason a student missed a deadline · keep the admission season survivable: fewer calls, fewer e-mails, fewer WhatsApp forwards to verify · satisfy audit, RTI and transparency obligations — every document must remain reachable | The same document must be linked from three places and he sometimes updates only one **[Inferred — supported by the divergent calendar links]** · no expiry mechanism: closed vendor notices and past deadlines accumulate because deleting feels unsafe for audit · everything competes for the same homepage list, so importance is expressed by capitals, red text and animated "new" icons · the same twenty questions arrive by phone every August |

> *"Deleting something is the dangerous thing. If it stays up, nobody can say I hid it. So the page only ever grows."*

## P3.2 Empathy map — the publishers

| SAYS | THINKS |
|---|---|
| "Send it to me by mail, I will put it up." · "It is already on the website, please check." · "Call between 10 and 5." · "Use the Google form, it is mandatory for all students." · "Keep the old link also, someone may need it." | "If I take it down and someone asks for it later, that is my problem." · "Students will say they never saw it — put it up in capitals." · "There is no time to redesign anything in admission season." · "The website is one duty among nine." · "Whoever set up the results portal has left; nobody touches it." · "A phone call is slower for me but safer for the student." |
| **DOES** | **FEELS** |
| Adds the new item at the top; leaves the old item in place · uploads a PDF instead of writing a page — faster and looks official · marks urgency with red text, capitals and an animated "new" icon · collects admission data through a Google Form outside the site · answers the same twenty questions by telephone, personally · publishes a personal mobile number because there is no service desk | Accountable for anything that goes wrong publicly · overloaded between June and September · protective of the institute's reputation · reluctant to delete — audit and RTI anxiety · unsupported: no CMS, no template, no reviewer, no staging site · proud of the institute's openness about fees, ordinances and rules |

**PAINS** — no CMS, no workflow, no staging, no template, no expiry · round-trip delay and no verification that a notice published correctly · the same document linked from several places, updated in one · personal phone as the institute's help desk for four months a year · publishing competes with teaching, research and audit deadlines.

**GAINS** — publish once and the item appears wherever it is relevant · automatic expiry with an archive, so removal is safe rather than risky · self-service faculty profiles, so nobody is the bottleneck · a public FAQ that absorbs the twenty repeated questions · evidence-ready records for NIRF, NBA, Senate and RTI in one place.

*Note the symmetry with the student empathy map: the student's "I can't tell if it's current" is the mirror image of the publisher's "it is not safe to delete".*

## P3.3 Journey map

**Scenario.** The Senate revises an end-semester date. Dr. Kharibam must get the corrected notice in front of six hundred students today, and must also handle the consequences of the earlier, now-wrong notice that is still live.

**Emotion curve**

```
 +1 |  ●1                                                      ●6
  0 |─────╲──────────────────────────────────────────────╱──────
 -1 |       ●2                                   ●5   ╱
 -2 |              ●3 ← lowest: cannot see, verify   ●4
     1.Decision 2.Draft&send 3.Wait 4.Published 5.Fallout 6.Closed
```

*The publisher's curve and the student's curve bottom out for the same structural reason: nobody owns the state of a notice.*

| Stage | Touchpoint | Action | Thought & emotion | Pain point | Opportunity |
|---|---|---|---|---|---|
| **1. Decision** | Senate / academic section (offline) | Date revised; a notice must follow within hours | "Six hundred students are planning travel around this." — urgency | No pre-approved notice template exists, so drafting starts from a blank page each time. | Notice templates by type (examination, registration, holiday, result) with mandatory fields: effective date, audience, expiry, supersedes. |
| **2. Draft & send** | Word/PDF → e-mail to the custodian | Formats, signs, scans, mails, then telephones to say it is urgent | "Will it go up today?" — dependency, low control | **[Inferred]** from the mixed, ad-hoc formatting of published notices and the absence of any authoring interface. Content arrives in a non-web format, so it is published as a PDF. | Role-based CMS access: the academic coordinator drafts, a reviewer approves, the system publishes. |
| **3. Wait** | None — there is no status to check | Refreshes the public page; answers questions in the meantime | "I have no idea where this is in the queue." — frustration, lowest point | No visibility, no acknowledgement, no queue. | A publishing queue with states (submitted / approved / live) visible to the submitter. |
| **4. Published** | Homepage Announcements list | New notice appears at the top; the superseded one remains further down | "At least it is up. Please let them read the right one." — relief with residual risk | **[Observed]** The site shows a revised admission deadline printed directly beneath the original one — exactly this failure mode, publicly visible. | A "supersedes" relationship that automatically strikes through and dates the older notice instead of leaving two live truths. |
| **5. Fallout** | Personal mobile; e-mail; class representatives | Answers the same question repeatedly; asks CRs to forward the correct notice | "This is the part that takes my afternoon." — fatigue | **[Observed]** Eight personal mobile numbers are the published support channel, with a five-hour daily window. | Role addresses, a service desk, and a student-facing FAQ; publish "last updated" so students can self-verify. |
| **6. Closed** | WhatsApp | The correction propagates informally and the matter ends | "It worked, but not because of the website." — resignation | The official channel is again bypassed, so the next notice will also be distrusted. | Make the site the source that WhatsApp *quotes*: stable URLs, share buttons, a one-line digest format designed to be forwarded. |

## P3.4 Pain points, ranked

| ID | Pain point | Evidence | Severity | Frequency | Design consequence |
|---|---|---|---|---|---|
| **A1** | No content management workflow: authors cannot publish, verify or withdraw their own content | Inferred | High | Continuous | Role-based CMS access with draft → review → publish states. |
| **A2** | Nothing expires; superseded notices remain live beside their replacements | Observed | High | Continuous | Expiry dates and a "supersedes" field; automatic move to a public archive rather than deletion, satisfying the audit concern. |
| **A3** | One document is linked from several places and updated in only one | Observed | High | Continuous | Single source of truth per document; every location references the same record. |
| **A4** | Publishing is an additional duty with no template, style guide or staging environment | Inferred | High | Continuous | Templates per notice type; a two-page style guide; a staging copy for risky edits. |
| **A5** | The public help desk is personal mobile numbers, 10 a.m.–5 p.m., concentrated in admission season | Observed | High | Seasonal, intense | Role addresses, a ticketed desk during admissions, and an FAQ built from the actual call log. |
| **A6** | Faculty profiles are inconsistent and depend on a third party to update | Observed | Medium | Continuous | Self-service profile editing with a fixed schema; a yearly reminder cycle. |
| **A7** | Academic data needed for NIRF, NBA and Senate reporting is scattered across PDFs and pages | Inferred | Medium | Annual, high pressure | Structured data behind the pages so reports are generated, not reassembled. |
| **A8** | Legacy systems (results portals on a raw IP) are unowned and unmaintained | Observed | High | Continuous risk | Assign ownership; migrate behind a named subdomain with TLS; document the handover. |

**How-Might-We statements arising from Part 3**

- **HMW-A1** — How might we let the person who owns a piece of academic information publish it themselves, safely, within minutes?
- **HMW-A2** — How might we make removing an obsolete notice feel *safer* than leaving it up?
- **HMW-A3** — How might we guarantee that updating a document once updates it everywhere?
- **HMW-A5** — How might we let a faculty member reclaim their August by letting the website answer the twenty repeated questions?

---

# Chapter 5 — Synthesis across the three parts

The rubric asks for inter- and intra-component coverage. Each part above is internally complete; this chapter reads them against one another. The central finding is that the three user groups are not experiencing three separate problems. They are experiencing three faces of the same four structural causes.

## 5.1 Affinity clustering

| C1 · No lifecycle for published information | C2 · Publisher-shaped IA | C3 · The PDF perimeter | C4 · People as API |
|---|---|---|---|
| S1 can't tell what is current · S4 mixed-audience notices · P8 recency unverifiable · A2 nothing ever expires · A3 one doc, many links · P6 no status feedback | S5 no site search · S6 unfilterable faculty list · P1 one page, two audiences · P5 cut-offs across 5 PDFs · P3 no parent content · two parallel navigations | S3 PDFs unreadable on phone · S2 three IP results portals · P2 fees split across 3 PDFs · P4 outcomes not structured · A7 no data for NIRF/NBA · A8 unowned legacy systems | P9 personal mobile support · A5 staff as help desk · A1 no self-publishing · A6 profiles via third party · student exit to WhatsApp · Thoibi as informal help desk |
| *Felt by all three groups. Largest cluster in the study.* | *Cheapest to fix, highest immediate visible effect.* | *Blocks search, mobile use and reuse simultaneously.* | *The institute's people are absorbing the design debt.* |

**Inter-component overlap — the same cause, three different costs.** C1 costs the student *trust* (she cannot rely on what she reads), the parent *confidence* (he cannot confirm normal operation), and the administrator *time* (he re-explains by telephone what the page failed to date). C4 is the closing of the loop: every unfixed instance of C1, C2 and C3 is eventually paid for by a human being answering a phone.

**Root-cause chain**

```
No owned publishing process → PDF-first, append-only site → Users cannot self-serve → Staff absorb the load
          ↑                                                                                      │
          └──── leaving no capacity to improve the publishing process — the loop that keeps the site as it is ────┘
```

## 5.2 Prioritisation — impact on users versus implementation effort

**DO FIRST — quick wins (high impact, low effort)**

1. Date every notice; add "last updated"
2. Split notices by audience with tabs
3. Fix the duplicate calendar link
4. Add site-wide search (including PDF text)
5. One "total cost of attendance" page
6. Parents' page: welfare, wardens, medical
7. Split "Considering" vs "Admitted" admission pages
8. Public FAQ built from the actual call log

**PLAN — major projects (high impact, high effort)**

9. Consolidate results into one branded TLS portal
10. CMS with roles, review, expiry, supersedes
11. Role-based homepage entry points
12. HTML-first calendar, syllabi, regulations
13. Student dashboard

**FILL-IN (low impact, low effort)**

14. URL hygiene (no spaces, lowercase) · 15. Pause control on the banner carousel · 16. Faculty directory filters · 17. Permanent tech-fest archive on the domain

**RECONSIDER (low impact, high effort)**

18. Full visual redesign before fixing the content model · 19. Native mobile app

*Items 1–8 need no new platform; they are content and information-architecture decisions that could be made in a single working week.*

## 5.3 The consolidated How-Might-We set

| Cluster | How Might We | Serves |
|---|---|---|
| **C1 · Lifecycle** | How might we give every piece of published academic information a visible birth date, an owner, and an expiry — so that being current is a property of the page rather than a guess by the reader? | All three groups; resolves S1, S4, P8, A2, A3 |
| **C2 · Architecture** | How might we let a visitor start from who they are — student, applicant, parent, faculty, recruiter — instead of from the institute's organisation chart? | All three; resolves P1, P3, S5, S6, the dual-navigation problem |
| **C3 · PDF perimeter** | How might we make the academic calendar, regulations, syllabi, fees and results readable, searchable and linkable on a phone, with the PDF kept as the printable companion rather than the primary artefact? | Students and applicants; resolves S2, S3, P2, P4 |
| **C4 · People as API** | How might we let the website absorb the twenty questions that currently arrive as phone calls, so that faculty time is spent on the twenty-first? | Administration and faculty; resolves A1, A5, A6, P9 |

---

# Chapter 6 — Ideation and proposed redesign

The assignment weights process above outcome, so this chapter is deliberately short and concrete: it shows what the empathy work implies, not a finished visual design. Everything proposed here is traceable to a numbered pain point in Parts 1–3.

## 6.1 Proposed information architecture

```
HOME — one question above the fold: "I am a …" · persistent site search · today's dated notices
│
├── APPLICANT ......... Programmes & specialisations · Closing ranks (one table)
│                       · Placement statistics · Campus & student life · Cost & scholarships
│                       → "I have a seat" checklist
├── PARENT ............ Total cost of attendance · Hostel, mess, wardens · Medical & counselling
│                       · Travel & ILP guidance · Safety & anti-ragging · Who to contact, when
├── STUDENT ........... This semester (dashboard) · Calendar & holidays (HTML) · Results (one portal)
│                       · Regulations & forms · Placement & internships · Clubs, fests, Gymkhana
├── FACULTY & STAFF ... Publish a notice · Edit my profile · Academic forms & leave
│                       · Committees & minutes · Project & IPR support · Recruitment
└── PUBLIC / RECRUITER  About, governance, RTI · Research & collaborations · Recruit our students
                        · Tenders & procurement · News & media   (moved out of student streams)

SHARED SERVICES LAYER — the same content, surfaced wherever it is relevant
  Notice service (audience tag · publish date · effective date · expiry · supersedes · owner)
  Document register (one canonical record per document, many references)
  People register (profiles, courses taught, research areas)
  Search index covering pages and the text inside PDFs
```

**What this fixes, by pain-point number.** Role entry layer → P1, P3, S5, S6 · Notice service → S1, S4, P8, A2, A3, A4 · Document register → S3, P2, P5, A3 · One results portal → S2, A8 · People register → S6, A6 · Search → S5 and C3 generally · Self-service publishing → A1, A5 · Tenders separated from student notices → S4, P8.

*Nothing here requires abandoning the existing PHP pages: the role pages are new entry points that link to sections that already exist.*

## 6.2 Concept wireframes

### Wireframe A — Homepage with a role entry layer

```
┌──────────────────────────────────────────────────────────────────────────────┐
│ ⬤ IIIT Senapati, Manipur          [🔍 Search the whole site, including PDFs]  │
├──────────────────────────────────────────────────────────────────────────────┤
│ I am a …                                                                     │
│ [Prospective student] [Parent] [Current student] [Faculty/staff] [Recruiter]  │
├───────────────────────────────────────────┬──────────────────────────────────┤
│ NOTICES  (Students)(Admissions)(Recruit.) │ AT A GLANCE                      │
│          (Tenders)              Archive ▸ │ Semester in progress · week 12/18 │
│ 15 Sep 2026  End-sem exam schedule        │ Next: end-sem exams from 20 Nov   │
│              Autumn 2026   [valid to 30 Nov]│ Admissions 2026-30: closed       │
│ 12 Sep 2026  Course registration Spring   │ Placement season: 14 companies    │
│              2027 opens    [valid to 05 Jan]│ Last reviewed 17 Sep 2026        │
│ 02 Sep 2026  ~~Earlier exam schedule~~     │                                  │
│                            [superseded]    │                                  │
│ 28 Aug 2026  NOS scholarship (ST)          │                                  │
│                            [closes in 13 d]│                                  │
├───────────────────────────────────────────┴──────────────────────────────────┤
│ FREQUENT TASKS — measured, not assumed                                       │
│ [Academic calendar] [Results] [Fee & scholarships] [Syllabus & ordinances]    │
│ [Find a faculty member] [Contact the right office]                           │
└──────────────────────────────────────────────────────────────────────────────┘
```

*Addresses S1, S4, S5, P1, P3, P8, A2. Note the superseded item struck through and dated rather than removed — this is what makes deletion safe for the administrator.*

### Wireframe B — Applicant hub

```
Considering IIIT Manipur?  ›  Programmes · Ranks · Outcomes · Life · Cost
─────────────────────────────────────────────────────────────────────────
Six B.Tech programmes · JoSAA/CSAB institute code 313
CSE 110 · CSE-AI&DS 110 · CSE-Cyber Security 55 · CSE-Quantum 55
· ECE 110 · ECE-VLSI&ES 110

┌ Closing ranks — one table ────┐ ┌ Placement — dated statistics ──┐
│ Branch ▾  Category ▾  Round ▾ │ │ Registered · placed · % ·      │
│ 2026·2025·2024·2023·2022      │ │ median · highest, by branch    │
│ side by side                  │ │ and year, with recruiter list  │
│ replaces five year-wise PDFs  │ │ "as on 17 Sep 2026" stamp      │
│ → fixes P5                    │ │ → fixes P4                     │
└───────────────────────────────┘ └────────────────────────────────┘

┌ For parents — one page, printable ────────────────────────────────┐
│ Total four-year cost incl. hostel & mess · loans & scholarships   │
│ · refund policy · hostel & warden contacts · medical · counselling│
│ · anti-ragging · travel & ILP · emergency number                  │
└───────────────────────────────────────────────────────────────────┘

► Already allotted a seat? → go to the joining checklist
  (separating this from the evaluation content is the single highest-impact change, P1)
```

### Wireframe C — Joining checklist

```
Your joining checklist — B.Tech 2026-30
✓ 1. Accept your seat on JoSAA / CSAB
     completed on the JoSAA portal · nothing to do here
✓ 2. Pay the institute fee
     ₹ total shown here · gateway opens in a new tab · receipt required at step 4
◷ 3. Submit the personal information form
     mandatory · confirmation e-mail arrives within 2 working days
○ 4. Report physically, 16–17 Aug, 9 am–6 pm
     documents list · both anti-ragging affidavits · dress code
○ 5. Move into the hostel
     packing list: winter clothes, mosquito net, bucket, bed roll, pillows
○ 6. Induction 18–22 Aug · classes begin 24 Aug
     full induction programme published here in advance
```

*Travel & ILP guidance, airport shuttle timings and taxi contacts appear beside step 4, where they are needed — not at the bottom of a 3,000-word page. Each step states what confirms it. Addresses P1, P2, P3, P4, P5, P6.*

## 6.3 Roadmap

| Horizon | Actions | Owner | Pain points closed |
|---|---|---|---|
| **Week 1–2** — content only | Date every notice and add a validity field; separate tenders and recruitment from student announcements; correct the duplicate academic-calendar link; publish a consolidated cost-of-attendance page; publish a parents' page from information that already exists elsewhere on the site; add an FAQ drawn from the questions the contact matrix already reveals. | Academic Section with two student volunteers | S1, S4, P2, P3, P8, partial A5 |
| **Month 1–3** — structure | Add site-wide search including PDF text; split the admission page into "Considering" and "Admitted"; build the joining checklist; publish closing ranks and placement statistics as tables; add filters to the faculty directory; URL hygiene pass. | Web committee + a vendor or a supervised student team | P1, P4, P5, P6, S5, S6, S8 |
| **Month 3–9** — platform | Introduce a CMS with roles, review, expiry and "supersedes"; consolidate the three results portals into one branded TLS portal with batch detection; migrate calendar, regulations and syllabi to HTML-first with PDF companions; self-service faculty profiles. | Institute IT with an external development partner | A1–A4, A6, A8, S2, S3 |
| **Month 9–18** — service | Role-based homepage; student dashboard; structured academic data feeding NIRF/NBA reporting; a ticketed help desk during admission season. | Institute IT + Academic Section | A5, A7, remaining C2 and C4 items |

## Success metrics

| Metric | How it is measured | Why it is the right measure |
|---|---|---|
| Share of academic pages carrying a visible publication and validity date | Manual audit, monthly | Directly measures the largest affinity cluster; moves from near zero to a target of 100% for notices. |
| Calls received on published personal mobile numbers during admission week | Tally sheet kept by the contact-matrix faculty for one week, before and after | Converts a website improvement into a number that the institute's leadership can act on; the most persuasive metric available. |
| Task success and time-on-task for six standard tasks | Moderated test with 8–10 users (4 students, 3 applicants/parents, 2 staff) | The standard usability measure; the tasks are drawn straight from the journey maps. |
| Proportion of student questions in class groups that link to an official page | Sample of class-representative message logs, with consent | Measures whether the site has recovered authority — the real goal behind Part 1. |
| Median time from a notice being approved to it being live | CMS timestamps once a CMS exists; self-reported before that | Measures the publisher's journey directly (Part 3, stage 3). |

## Testing plan — the step beyond this assignment

The personas and journeys in this report are built from observation of the artefact and from conversations with peers. They are hypotheses about people, and hypotheses should be tested. We propose a two-hour, six-task moderated study run in the department laboratory:

1. Find the date the current semester ends.
2. Find last year's closing rank for CSE in your category.
3. Work out the total first-year cost including hostel.
4. Find a faculty member working on natural language processing.
5. Find out what to bring to the hostel.
6. As a staff member, locate every place a revised examination notice would have to be updated.

Each task is scored for success, time, and number of navigation errors, and each participant is asked afterwards what they would have done if the site had failed them. Task 6 in particular will confirm or refute the inferences in Part 3, which are the least evidenced claims in this report.

> **Closing observation.** The most encouraging thing we found is not a weakness but a strength: the travel advisory, the packing list, the dress-code note, the airport shuttle, the published refund policy and the topic-wise contact matrix show an institution that already thinks carefully about what a nervous person needs to be told. Design Thinking is not being introduced to this website from outside — it is already present, in paragraphs. What this report proposes is that the same empathy be applied one level up, to the structure that decides whether anyone finds those paragraphs.

---

# Appendices

## A1 — Evidence log

Every page listed below was opened and read on **17 September 2026**. Starred entries are the ones illustrated in §1.2 — capture screenshots from these URLs and place them at the `[SCREENSHOT]` markers.

| Page | URL | Used in |
|---|---|---|
| Homepage ★ | `www.iiitmanipur.ac.in/index.php` | Fig 1.1, Fig 1.2; S1, S4, S5, P1, P8 |
| B.Tech admission ★ | `/pages/academic/admission.php` | Fig 1.3; all of Part 2 |
| Teaching staff ★ | `/pages/people/staffTeaching.php` | Fig 1.4; S6, A6 |
| Results portals ★ | `http://14.139.202.226/23batchresult/` · `/20batchresult/` · `/resultPortal/` | Fig 1.5; S2, A8 |
| Courses offered | `/pages/academic/coursesOffered.php` | Part 2, stage 2 |
| Departments — CSE / ECE / HBS | `/pages/academic/academicCSE.php` · `academicECE.php` · `academicHBS.php` | §1.1; S6 |
| Academic calendar & holidays | `/snippets/2026/ACADEMIC CALENDER 2026.pdf` · `List of Holidays 2026.pdf` | S1, S3; the duplicate-link finding |
| Footer "Academic Calendar" link | `/snippets/2022.Academic.Calendar.pdf` | S1, A3 — divergent from the menu link |
| Regulations & ordinances | `/snippets/2024/ORDINANCES_AND_REGULATIONS_BTECH_2023.pdf` · `hostelrules.pdf` · `Ordinance.pdf` · `Leave-Rules.pdf` | S3, C3 |
| Syllabi (four PDFs) | `/snippets/SyllabiCSE2023.pdf` · `SyllabiCSEAID2023.pdf` · `SyllabiECE2023.pdf` · `SyllabiECEVLSI2023.pdf` | P1, P5, S3 |
| Cut-offs by year | `/pages/academic/admission2025/RankList2024.pdf` · `/documents/cut_off_rank_2023-24.pdf` · `/snippets/2022-23-Btech-Admission-Cut-off.pdf` | P5 |
| Fee documents | `/pages/academic/admission2026/FeeSstructure2026_27.pdf` · `RemainingFeeToBePaid2026_27.pdf` · `FeePaymentForm_FeeDetails.pdf` | P2, P6 |
| Refund policy | `/snippets/2022-Admission-Cancellation-Fees-Refund-Policy.pdf` | P2 |
| Documents & affidavits for reporting | `/pages/academic/admission2026/List_of_document2026.pdf` · `affidavit_ragging_student.pdf` · `affidavit_ragging_parent.pdf` | Part 2, stages 5–6 |
| Scholarships and loans | `/pages/center/scholarships/scholarships.php` | P2, and Rohit's renewal goal |
| Training & Placement Cell | `/pages/centerTnP/tnp.php` · `/pages/centerTnP/tnpStatus.php` | S5, P4 |
| Students' Corner — Gymkhana, testimonials, activities | `/pages/about/gc.php` · `/pages/Students/testimonials.php` · `/pages/Students/activitiesEvents.php` | S7, P3 |
| Tech fests, three years | `www.ahouba.com` · `/tech_fest/2025_ahouba/index.html` · `ahouba.iiitmanipur.ac.in` | S7 |
| PhD admission | `/pages/academic/2022.06.admission.phd.php` | §1.1, Part 3 |
| Grievance, anti-ragging, POSH, equity | `/pages/center/grievance.php` · `antiRagging.php` · `shc.php` · `eap.php` | P3 (parent-facing content that exists but is not surfaced) |
| Recruitment & tenders | `/pages/recruitment/recruit.php` · `/pages/tender/tender.php` | S4, A2 — audience mixing on the homepage |
| Forms and essentials | `/pages/essentialInfo.php` | §1.1 — footer-only, absent from the top menu |
| Mission & vision, about, director's message | `/pages/about/mission.php` · `about.php` · `directorMessage.php` | Context for §B and Part 2, stage 1 |

## A2 — Templates used

| Artefact | Template | Fields we filled |
|---|---|---|
| Persona (six of them) | Standard Design Thinking persona canvas (name, photo placeholder, demographics, background, context of use, goals, frustrations, behaviours, needs, representative quote) | All fields; the quote is a composite, not an attributed statement by any real person. |
| Empathy map (three) | Gamestorming four-quadrant map (Says / Thinks / Does / Feels), extended with a Pains and Gains band | All six regions; entries traced to observation or to persona reasoning. |
| Journey map (three) | Six-column journey template: Stage → Touchpoint → Action → Thought & emotion → Pain point → Opportunity, with an emotion curve above | All columns for every stage; emotion plotted on a −2…+2 scale. |
| Evaluation | Nielsen's ten usability heuristics, scored 1–5 | §1.3 |
| Synthesis | Affinity clustering; impact/effort prioritisation matrix; How-Might-We reframing | §5.1, §5.2, §5.3 |

## A3 — Group contribution sheet

| Member | Roll number | Primary responsibility | Secondary contribution |
|---|---|---|---|
|  |  | Site audit & information architecture (Ch. 1) |  |
|  |  | Part 1 — current students |  |
|  |  | Part 2 — prospective students & parents |  |
|  |  | Part 3 — administration & faculty |  |
|  |  | Synthesis, wireframes & roadmap (Ch. 5–6) |  |

## A4 — References

- Indian Institute of Information Technology Senapati, Manipur — institute website, all pages listed in Appendix A1, accessed 17 September 2026.
- Hasso Plattner Institute of Design at Stanford (d.school), *An Introduction to Design Thinking: Process Guide* — the five-mode framing used in §C.
- Design Council (UK), *Framework for Innovation* — the double-diamond model adapted in Figure C.1.
- Nielsen, J., *10 Usability Heuristics for User Interface Design* — the evaluation instrument used in §1.3.
- Gray, D., Brown, S. and Macanufo, J., *Gamestorming* — the empathy-map canvas.
- Kalbach, J., *Mapping Experiences* — journey-map structure and the emotion-curve convention.
- Government of India, *Guidelines for Indian Government Websites (GIGW)* — the accessibility and content-lifecycle expectations informing §6.1 and §6.3.
