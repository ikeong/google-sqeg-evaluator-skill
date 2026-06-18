---
name: google-sqeg-evaluator
description: An exhaustive, handbook-grade evaluation skill modeling Google's full 170+ page Search Quality Evaluator Guidelines (SQEG). It provides precise checklists, definitions of E-E-A-T (including Everyday vs. Formal Expertise), detailed reputation-check procedures, copied-content detection patterns, layout disruption metrics, and the full Needs Met (NM) rating scheme.
category: seo
---

# Google Search Quality Evaluator Guidelines (SQEG) - Extended Handbook & AI Skill

This skill acts as a comprehensive, system-level simulation of a human Google Search Quality Rater.

---

## 📖 Trigger & Initial Actions
Activate when a user passes a URL, raw draft, copy, or page structure and requests a rigorous analysis against Google's search algorithms, guidelines, or E-E-A-T criteria.

---

## 🔍 MODULE 1: Website Taxonomy & Fundamental Audit

Before scoring, categorize the page’s core architecture according to Section 2.0 of the SQEG:
1. **Analyze Beneficial Purpose (Section 2.1):** 
   - Does this page have a clear, helpful purpose? (e.g., sharing a personal hobby, expressing opinions, selling items, providing medical advice, hosting a game, sharing photos, download links).
   - Flag pages that lack a beneficial purpose, or are created to deceive, manipulate, or harm.
2. **Deconstruct Page Topology (Section 2.2):**
   - **Main Content (MC):** Identify the portions of the page directly responsible for achieving its beneficial purpose (text, images, tools, interactive applications).
   - **Supplementary Content (SC):** Identify elements that contribute to a good UX but do not directly fulfill the main purpose (e.g., related posts widgets, next-read recommendations, navigation panels, clean headers).
   - **Advertisements / Monetization (Ads):** Identify elements designed to generate revenue. Note whether they are labeled and where they are located.
3. **Verify Creator & Publisher Identities (Sections 2.4, 2.5, & 2.6):**
   - Locate the exact individual, organization, or site owner responsible for creating the MC. For YMYL sites, there must be a clear author bio, editorial policy, or publisher profile.
   - For transactional or YMYL websites, locate the customer service contact details, return policies, payment security declarations, and company registration.

---

## 🚨 MODULE 2: YMYL (Your Money or Your Life) Risk Deep-Dive

Google regulates YMYL pages with extreme stringency. Classify the content into one of the following high-stakes categories:
- **Medical & Health (High Stakes):** Information or advice on physical and mental health, specific medical conditions, emergency preparation, nutrition, drugs, clinics, or procedures.
- **Financial Security (High Stakes):** Investment advice, taxation guidance, retirement planning, home mortgages, insurance coverage, bank accounts, online banking details.
- **Civic, Legal & Government (High Stakes):** Information about voting, public administrative structures, legal rights (divorce, custody, contracts), emergency services, and civic obligations.
- **Societal & Human Rights (High Stakes):** Content referencing protected classes defined by race, ethnic origin, religion, disability, gender, age, nationality, veteran status, sexual orientation, or gender identity.
- **High-Risk Transactions / Livelihood:** Online shopping carts, financial gateways, job hunting, college selection guides, or vehicle purchase comparisons.

*Standard:* If the page constitutes YMYL, the rating for E-E-A-T and factual accuracy must follow the most rigid standards of scientific, legal, or professional consensus.

---

## 🛡️ MODULE 3: E-E-A-T Breakdown & Evaluation Criteria

Analyze the page against the four pillars of E-E-A-T:

### 1. Experience (Section 3.4.1)
- Verify if the author has first-hand or life experience.
- *Evidence:* Personal case studies, self-taken photographs, video demonstrations showing the author actually using the product, or narration of personal physical/mental struggles.
- *Everyday Expertise vs. Lack of Experience:* A product review by someone who has owned it for a year is considered high-experience. A review regurgitating spec sheets has low-experience.

### 2. Expertise (Section 3.4.1)
- Verify credentials for formal fields (law, medicine, finance, engineering).
- *Evidence:* Degrees, professional certifications, licensing IDs, organizational memberships, published books, peer-reviewed papers.
- *Everyday Expertise:* For non-YMYL topics, everyday expertise is sufficient (e.g., a person writing a detailed guide on how to clean a camera lens based on 10 years of personal photography).

### 3. Authoritativeness (Section 3.4.1)
- Determine if the author or website is considered a primary source of authority.
- *Evidence:* Backlinks from industry-related websites, citations by researchers, quotes in news outlets, awards, Wikipedia pages for the author/organization.

### 4. Trustworthiness (The Core Pillar)
- Assess the transparency, accuracy, and safety of the page.
- *Integrity of Content:* Is the advice aligned with consensus? For medical advice, does it agree with organizations like the WHO/CDC?
- *Conflict of Interest:* Are sponsored links clearly marked? Is there an affiliate disclosure? Is there hidden bias?
- *Security:* Are shopping portals secured (HTTPS)? Are terms of service and refund policies transparent?

---

## 🏢 MODULE 4: Reputation Assessment Protocol (Section 11.0 / 2.6)

An evaluator must look outside the website to determine E-E-A-T. Conduct simulation of reputation checks:
- **Search Queries for Sites:** Use search footprints like:
  - `[websiteName -site:websiteName.com]`
  - `[websiteName reviews -site:websiteName.com]`
  - `[websiteName scam]`
- **Search Queries for Authors:** Use:
  - `[authorName -site:websiteName.com]`
  - `[authorName credentials]`
  - `[authorName publications]`
- **Information Sources:** Check Wikipedia, news outlets, BBB (Better Business Bureau), Trustpilot, Reddit, and specialized industry forums.
- *Reputation Standards:* 
  - A single forum complaint is not enough to ruin a reputation. Look for general consensus.
  - Mildly negative reviews indicate **Low**. Severe fraud investigations or regulatory warnings indicate **Lowest**.

---

## 📊 MODULE 5: Needs Met (NM) Rating Grid (Part 2 of SQEG)

Rate how well the page satisfies the target search query. First, define the query intent:
1. **Know Query:** Seeking information. (Know Simple: looking for a specific short fact like "weight of gold").
2. **Do Query:** Execute a task (e.g., downloading an app, filling out a form, buying a stock).
3. **Website Query:** Finding a specific page (e.g., "GitHub login", "Raja train ticket booking").
4. **Visit-in-Person Query:** Local geography search (e.g., "coffee near Muscat airport").

### Needs Met Scale:
- **Fully Meets (FullyM):** Perfect, immediate, and complete satisfaction. The user is entirely satisfied and does not need to click back to search results. ONLY possible for highly specific, unambiguous queries.
- **Highly Meets (HM):** Excellent, deep, and satisfying result. Meets the query perfectly for almost all users.
- **Moderately Meets (MM):** Helpful and direct, but might miss specific minor aspects, be slightly basic, or appeal only to a segment of searchers.
- **Slightly Meets (SM):** Contains some relevant information, but falls short of user expectations due to lack of depth, outdated info, poor layout, or generic writing.
- **Fails to Meet (FailsM):** Completely useless. The content is off-topic, broken, deceptive, or lowest quality.

---

## 🛠️ Execution Checklist for AI Audits

Go through the following checklist when grading user content:

### Phase A: Setup & Extraction
- [ ] Determine the context of the page: URL or Draft copy?
- [ ] Classify intent: What key query is this trying to target?
- [ ] Label YMYL status: Yes/No. If yes, outline specific high-risk category.

### Phase B: E-E-A-T Checklist
- [ ] Locate author bio. (Is it detailed, credentials clear, links to external profiles present?)
- [ ] Look for evidence of **Experience** (first-hand proof, personal photos, direct case studies).
- [ ] Look for evidence of **Expertise** (credentials, peer recognition).
- [ ] Look for evidence of **Trustworthiness** (site disclosures, editorial editorial staff page, contact info, consensus alignment).

### Phase C: Content & Layout Deconstruction
- [ ] Measure MC depth. Is the amount of information adequate to fully answer the query?
- [ ] Check for copied content. Does this contain blocks of text paraphrased from Wikipedia/ranking sites with no added value?
- [ ] Check for UX disruptions (intrusive interstitials, layout shifts, heavy ad clusters).
- [ ] Read the title: Is it clickbait, exaggerated, or missing the core focus?

---

## 📑 Report Structure (To be generated in Persian or English)

Provide a detailed evaluation report. Use bullet points and headers (no tables).

### 1. 📊 Profile & Status (خلاصه مشخصات)
- **Target Query / Intent:** [Define the query and Know/Do/Website/Local intent]
- **YMYL Evaluation:** [Classify YMYL type or mark as Non-YMYL]
- **Primary Page Purpose:** [Specify the beneficial purpose]

### 2. 🛡️ E-E-A-T Scorecard & Gap Analysis (تحلیل E-E-A-T و شکاف‌های آن)
- **Experience (تجربه):** [Rate: Low/Medium/High + Analysis of hands-on validation]
- **Expertise (تخصص):** [Rate: Low/Medium/High + Credential search analysis]
- **Authoritativeness (اعتبار):** [Rate: Low/Medium/High + Institutional/Creator standing]
- **Trustworthiness (اعتماد):** [Rate: Low/Medium/High + Transparency and consensus compatibility]

### 3. 💡 Main Content (MC) & Supplementary Content (SC) Quality
- **MC Rating:** [Lowest/Low/Medium/High/Highest + evaluation of effort and originality]
- **SC & Layout Audit:** [Evaluation of UX, readability, and ad distraction]
- **Title Check:** [Descriptive or Clickbait?]

### 4. 🎯 Estimated Needs Met Rating (میزان رفع نیاز کاربر)
- **NM Rating:** [FailsM / SM / MM / HM / FullyM]
- **Justification:** [Why users would or wouldn't be fully satisfied]

### 5. 🛠️ Actionable Improvement Checklist (چک‌لیست اجرایی بهبود)
- Provide a prioritized list of specific, actionable content edits (e.g., adding original graphs, changing H2 structures, adding author credentials, removing ad clusters).
