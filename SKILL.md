---
name: google-sqeg-evaluator
description: Evaluates web pages and content against Google's Search Quality Evaluator Guidelines (SQEG) focusing on E-E-A-T, Page Quality, and Needs Met.
category: seo
---

# Google Search Quality Evaluator Skill

## Trigger
When the user provides a URL or text and asks for a content quality evaluation, SEO review, or checking against Google's guidelines (SQEG).

## Context
Google's Search Quality Evaluator Guidelines (SQEG) provide a framework for assessing Page Quality (PQ) and Needs Met (NM). The core pillars are:
- **E-E-A-T:** Experience, Expertise, Authoritativeness, Trustworthiness.
- **Main Content (MC):** Effort, originality, talent, and skill.
- **Supplementary Content (SC):** Does it help or distract?
- **Page Purpose:** Is it helpful and harmless?
- **Needs Met Rating:** How well does it satisfy the user intent?

## Workflow
1. **Content Ingestion:**
   - If given a URL, use tools (like `browser_navigate` + `browser_snapshot` or `curl`/fetch tools) to extract the Main Content (MC).
   - If given text, proceed directly to analysis.
2. **Analysis Process:**
   Evaluate the content strictly through the lens of a Google Quality Rater:
   - **Purpose & Intent:** What is the page trying to achieve? What would a user searching for this expect?
   - **E-E-A-T Check:** Are the author's credentials visible? Is the information accurate and backed by consensus? (If YMYL - Your Money or Your Life, apply the highest standards).
   - **Content Quality:** Is the MC comprehensive, clear, and well-structured? Are there grammatical issues or fluff?
   - **UX/Structure Check:** Are headings logical? Are there intrusive elements (interstitials, excessive ads)?
3. **Reporting Format (Respond in the language of the user's request):**
   Structure your response as follows:
   - **📊 Overview (خلاصه وضعیت):** Brief summary of the content's current state.
   - **🎯 Page Quality & E-E-A-T (کیفیت صفحه و E-E-A-T):** Strengths and weaknesses regarding Experience, Expertise, Authority, and Trust.
   - **💡 Main Content Assessment (بررسی محتوای اصلی):** Depth, clarity, originality, and formatting.
   - **🎨 Structure & UX (ساختار و تجربه کاربری):** Readability, heading hierarchy, user experience factors.
   - **🛠️ Actionable Recommendations (پیشنهادات اجرایی):** Prioritized list of specific changes to improve the page.

## Pitfalls
- Do not give generic SEO advice (like "add more keywords" or "fix meta tags"). Focus strictly on *Content Quality*, *E-E-A-T*, and *User Intent* as defined in the 170+ page SQEG document.
- For YMYL (Your Money or Your Life) topics (health, finance, news), apply the highest standard of Trust and Expertise. Mention explicitly if the topic is YMYL.
- Distinguish between the Creator of the content and the Website itself if they are different.