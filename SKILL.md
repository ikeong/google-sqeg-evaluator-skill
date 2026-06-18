---
name: google-sqeg-evaluator
description: A highly comprehensive AI evaluation skill modeling Google's full 170+ page Search Quality Evaluator Guidelines (SQEG) for rating Page Quality (PQ) and Needs Met (NM).
category: seo
---

# Google Search Quality Evaluator Guidelines (SQEG) Comprehensive Skill

## Trigger
When a user provides a web URL, raw draft text, or an article structure and requests a content audit, SEO evaluation, E-E-A-T assessment, or general critique against Google's search quality guidelines.

## Part 1: Page Quality (PQ) Rating Framework

To rate Page Quality, the evaluator must analyze five key components:
1. **The Purpose of the Page:** 
   - Identify the clear purpose (e.g., to share info, entertain, sell products, express an opinion, or perform a task).
   - Flag harmful, deceptive, or malicious pages. Pages with harmful intent automatically receive the **Lowest** rating.
2. **YMYL (Your Money or Your Life) Risk Assessment:**
   - Determine if the page covers topics that could impact a person's future happiness, health, financial stability, or physical safety.
   - **YMYL Categories:**
     - *Health & Safety:* Medical conditions, treatments, drugs, hospitals, emergency prep.
     - *Financial Security:* Investments, taxes, retirement, banking, loans, insurance.
     - *Civic, Government & Law:* Voting, government agencies, legal rights, social services.
     - *Society:* Information about groups of people based on race, religion, gender, sexual orientation, disability, etc.
     - *Other:* High-risk topics like choosing a college, buying a car, finding a job.
   - For YMYL pages, apply the absolute highest standards of accuracy, scientific/professional consensus, and trustworthiness.
3. **E-E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness):**
   - **Experience (First-hand knowledge):** Does the content creator have real-world, hands-on experience with the topic? (E.g., booking a room at the hotel they show, using the product they review).
   - **Expertise (Formal skill/knowledge):** Does the creator have the necessary professional credentials, certifications, or formal education (mandatory for YMYL topics like medical/legal)?
   - **Authoritativeness:** Is the creator or website recognized as a go-to source for this topic? Look for industry mentions, citations, links, or awards.
   - **Trustworthiness (The Central Pillar):** Assess transparency. Is it clear who created the content, who is responsible for the site, and how to contact them? Are there policies, conflict of interest disclosures, and unbiased reviews?
4. **Main Content (MC) Quality and Amount:**
   - **Amount:** Is the quantity of MC sufficient and satisfying based on the page's purpose and topic complexity?
   - **Quality:** Evaluate the level of effort, originality, talent, and skill. original reporting, original research, or highly detailed synthesis indicates high quality. Check for copied/curated text without added value (low quality).
5. **Website and Creator Reputation:**
   - Search for independent sources (news, Wikipedia, discussion forums, reviews, Better Business Bureau) about the website and the content creator. Do not rely solely on what the site says about itself.

---

## Part 2: Page Quality Rating Scale

Apply these criteria to assign a Page Quality rating:

### 🚨 Lowest Quality
- **Harmful / Hateful:** Promotes harm, hate speech, violence, or severe misinformation.
- **Deceptive:** Misleads the user (e.g., cloaking, fake news, impersonating high-E-E-A-T sites).
- **Zero Effort MC:** Automatically generated content with no human editing, or absolute lack of purpose.
- **Copied Content:** Scraped or paraphrased from other sources with zero added value, commentary, or research.
- **Hidden / Lack of Contact Info:** Missing crucial creator/owner details on YMYL websites.
- **Extremely Negative Reputation:** Broad independent consensus of scams, fraud, or medical malpractice.

### ⚠️ Low Quality
- **Inadequate MC:** The page doesn't have enough main content to satisfy its purpose.
- **Low E-E-A-T:** The creator lacks experience or credentials for a specialized/YMYL topic.
- **Distracting Supplementary Content (SC):** Intrusive ads, interstitials, or pop-ups that block the MC or make page navigation extremely difficult.
- **Mildly Negative Reputation:** Consistent low rating reviews or complaints on independent sites.
- **Vague / Thin Info:** Lack of details, heavy use of fluff/filler words to lengthen the post.

### ⚖️ Medium Quality
- **Satisfying:** The page has a beneficial purpose and achieves it reasonably.
- **Standard MC:** Content is decent, but lacks exceptional effort, detail, or originality.
- **Adequate E-E-A-T:** Enough credentials or experience for the topic, but nothing outstanding.
- **Neutral/No Reputation:** No major complaints, but also no special recognition.

### ⭐ High Quality
- **Satisfying MC:** Rich, detailed content that demonstrates significant effort, originality, talent, or skill.
- **Clear E-E-A-T:** High level of experience/expertise. Strong transparency about who is responsible for the content and site.
- **Positive Reputation:** Mentioned positively by independent sources, cited by others, clean track record.
- **Good User Experience:** SC is helpful, ads are non-obtrusive, layout is clean and user-friendly.

### 🏆 Highest Quality
- **Exceptional MC:** Unique, highly comprehensive, original research, unique reporting, or world-class expert advice. High level of creation effort.
- **Outstanding E-E-A-T:** The absolute highest standard of trust. Clear expert author profiles, editorial oversight, fact-checking credentials.
- **Stellar Reputation:** Award-winning creator/site, highly praised on Wikipedia or major media outlets.

---

## Part 3: Needs Met (NM) Rating Framework

Needs Met measures how helpful and satisfying the search result page is to a user based on their search query (intent).

### 1. Classifying Search Intent:
- **Know Query:** Find information (e.g., "how tall is the Eiffel Tower?").
  - *Know Simple:* Expects an immediate, short answer.
- **Do Query:** Execute an action (e.g., "buy iPhone 15", "download Spotify").
- **Website Query:** Go to a specific site (e.g., "facebook login", "wikipedia").
- **Visit in Person:** Find a brick-and-mortar location (e.g., "restaurants near me").

### 2. Rating Scale:
- **Fully Meets (FullyM):** The result is a perfect match for a search query. Users do not need to look at any other results. (Only applicable to clear queries with single answers/solutions).
- **Highly Meets (HM):** Very helpful, detailed, and completely satisfying for almost all users. Needs minor improvements to reach perfection.
- **Moderately Meets (MM):** Helpful and direct, but might miss some minor aspects or be good for only some users. Or targets a secondary query interpretation.
- **Slightly Meets (SM):** Low utility. The user has to do significant work to extract value, or the content is outdated, thin, or low quality.
- **Fails to Meet (FailsM):** Completely useless. Irrelevant, dead link, completely off-topic, or lowest-quality deceptive page.

---

## Evaluation Workflow (Step-by-Step)

When assessing user content, execute these steps:

### Step 1: Query & Intent Profiling
1. What query would lead a user to this page?
2. What is the search intent (Know, Know Simple, Do, Website, Visit)?
3. Is it YMYL? If yes, classify the YMYL type.

### Step 2: Creator & Publisher Analysis
1. Who is the author? Do they have credentials/experience listed?
2. Who is the publisher/website? Is there clear contact info/about page?
3. What is the consensus/reputation of the creator & publisher?

### Step 3: Main Content (MC) Assessment
1. What is the core topic?
2. Is the content depth satisfying for the intent?
3. Does it show significant effort, talent, or originality?
4. Are there quality issues (clichés, fluff, factual errors, AI-isms, grammar)?

### Step 4: Supplementary Content (SC) & Layout
1. Does the layout make reading easy?
2. Are ads or banners intrusive?
3. Do supplementary elements (related posts, sidebar widgets) add value?

### Step 5: Scorecard & Recommendation
Provide:
1. **PQ Rating** (Lowest, Low, Medium, High, Highest) + Justification.
2. **NM Rating** (FailsM, SM, MM, HM, FullyM) + Justification.
3. **Gap Analysis:** Where the content falls short.
4. **Actionable Checklist:** Concrete changes the user can make.

---

## Verification & Output Standards

- Always respond in the language of the user's request (Persian for Persian requests, keeping standard terminology).
- Never hallucinate recommendations. If the target content cannot be verified (e.g., missing author bio), state: "Raters will penalize this page because no author bio is visible. *Recommendation: Add a bio with X credentials.*"
- Format results clearly with header levels and bullet lists. Do not use tables.
