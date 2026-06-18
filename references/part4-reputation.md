# Google Search Quality Evaluator Guidelines (SQEG) - Section 11.0: Reputation Audit Engine

This reference details the instructions in Section 11.0 of the SQEG for investigating the reputation of a website and its individual content creators.

---

## 1. Why Third-Party Reputation is Critical

Google's guidelines warn raters that **a website cannot be trusted to rate itself**. The content on "About Us" or "Press" pages is often self-promotional. Therefore, a rater's rating must be based on **independent, third-party research**.

---

## 2. Reputation Footprint Search Commands
To audit a site's reputation, construct search strings that exclude the brand's own domain. This isolates external reviews and commentary.

### A. Domain Reputation Scans
* **Excluding Self-References:** Set up search queries using the `-site:` operator.
  `[brandName -site:brandDomain.com]`
* **Scanning for Negative Consensus:** Search for complaints, scams, or fraud reports.
  `[brandName reviews -site:brandDomain.com]`
  `[brandName scam -site:brandDomain.com]`
  `[brandName lawsuit -site:brandDomain.com]`
  `[brandName fraud -site:brandDomain.com]`

### B. Creator / Author Scans
* **Verifying Author Authority:** Search for the writer's name to see their credentials, other publications, and professional standing.
  `[authorName -site:brandDomain.com]`
  `[authorName credentials]`
  `[authorName publications]`

---

## 3. High-Quality Third-Party Sources

Raters look for reputation consensus on these platforms:

1. **Wikipedia:**
   * Wikipedia articles are highly valued by Google because of their strict editing standards and verified sources.
   * If a site or author has a neutral or positive Wikipedia page, it is a strong signal of high authority.
2. **Professional & Regulatory Organizations:**
   * Better Business Bureau (BBB) for commercial websites (look for A+ ratings, complaints, and resolution history).
   * Government registries (SEC, FDA license status, medical boards).
   * Academic search systems like Google Scholar to verify research publications.
3. **Consumer Review Platforms (Aggregated Consensuses):**
   * Trustpilot, TripAdvisor, Yelp, or industry-specific review forums.
   * *Rule:* Do not judge a brand based on a single negative review. Look for systemic patterns, volume of complaints, and how the company handles disputes.
4. **Independent News & Media:**
   * Independent articles in recognized newspapers (e.g., The New York Times, BBC, specialized industry journals).

---

## 4. Rating Classifications Based on Reputation

| Reputation Level | Specific Audit Observations | PQ Score Impact |
| :--- | :--- | :--- |
| **Stellar Reputation** | Recognized by national or international awards, positive Wikipedia pages, and citations from top industry organizations. | High / Highest PQ |
| **Neutral / No Reputation** | No mentions in external reviews, no complaints. Common for small personal blogs. | Medium PQ (No penalty unless YMYL) |
| **Inadequate Trust** | Outdated info, lack of author credentials on YMYL, missing contact details. | Low PQ |
| **Poor Reputation** | Frequent consumer complaints on independent sites, low rating on BBB/TrustPilot, lack of customer service response. | Low PQ |
| **Extremely Negative** | Fraud warnings, scams, criminal charges, or offering dangerous medical advice that contradicts consensus. | Lowest PQ |
