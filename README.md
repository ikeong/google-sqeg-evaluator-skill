# Google Search Quality Evaluator (AI Skill)

This repository contains a highly comprehensive AI skill prompt designed to evaluate web content or text against **Google's Search Quality Evaluator Guidelines (SQEG)** (a ~170-page document used by Google's human raters).

It instructs AI agents (like Claude, ChatGPT, Gemini, or Hermes Agent) to act as a Google Quality Rater, analyzing your content for Page Quality (PQ) and Needs Met (NM) using Google's official rating scales.

---

## Repository Contents

1. **`prompt.md`**: The complete, detailed English system prompt for AI tools to perform a comprehensive SQEG content audit.
2. **`prompt-fa.md`**: The complete, detailed Persian (فارسی) version of the evaluation system prompt.
3. **`SKILL.md`**: The Hermes Agent package file, enabling you to integrate this skill directly into your Hermes runtime.

---

## Core Evaluation Pillars

The prompts are structured around the actual chapters of Google's SQEG:

1. **Page Purpose Assessment**: Distinguishing high-value beneficial pages from deceptive, spam status, or harmful pages.
2. **YMYL (Your Money or Your Life) Risk Categorization**: Applying extreme validation criteria for medical, financial, legal, civic, and societal topics.
3. **E-E-A-T Framework**: Direct evaluation of:
   * **Experience**: Evidence of first-hand, real-world contact with the topic.
   * **Expertise**: Professional credentials, certifications, and educational authority.
   * **Authoritativeness**: Off-site references, media citations, and institutional trust.
   * **Trustworthiness**: The core pillar—assessed through transparency, editorial clarity, and contact openness.
4. **Main Content (MC) Quality**: Analyzing the depth of research, creator effort, originality, and structure of main content versus supplementary content (SC) or intrusive ads.
5. **Needs Met (NM) Score**: Predicting search intent (Know, Know Simple, Do, Website, Visit) and rating results from *Fails to Meet* to *Fully Meets*.

---

## How to Use

### 1. Copy & Paste (For ChatGPT / Claude / Chat UIs)
Copy the full text of either `prompt.md` (English) or `prompt-fa.md` (Persian) and paste it into your AI assistant, then provide your writing/URL.

### 2. Hermes Agent Integration
Add `SKILL.md` to your local `~/.hermes/skills/google-sqeg-evaluator/SKILL.md` to make it instantly available in your agent CLI or chat interface.
