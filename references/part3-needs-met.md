# Google Search Quality Evaluator Guidelines (SQEG) - Section 12.0: Needs Met Rating Manual

This reference details the instructions in Sections 12.0 through 17.0 of Google's Search Quality Evaluator Guidelines (SQEG) for rating Needs Met (NM).

---

## 1. Classifying Search Intents (The Needs Met Context)

Every search query has a specific user intent. Raters must classify the query into one of these categories before rating the result:

### A. Know Intent (Seeking Information)
* **Goal:** The user wants to learn something.
* **Know Simple:** A sub-category where the user wants a short, factual answer (e.g., weather forecast, conversions, birthdays of famous people).
  - *Example:* "How old is Elon Musk" or "Convert 100 USD to GBP".
  - *Expectation:* Needs an immediate, accurate, and easy-to-read answer.

### B. Do Intent (Executing Action)
* **Goal:** The user wants to perform an action, buy a product, download software, or sign up for a service.
  - *Example:* "Buy cheap flight ticket to Muscat", "Download VLC player", or "Online Photoshop editor".
  - *Expectation:* Requires direct links to functional pages, checkout cards, or interactive web applications.

### C. Website Intent (Brand Navigation)
* **Goal:** The user wants to navigate to a specific website or webpage.
  - *Example:* "YouTube login", "Instagram index", or "Raja passenger portal".
  - *Expectation:* The official landing page or login portal must be the top result.

### D. Visit in Person Intent (Local Search)
* **Goal:** The user wants to find a physical business or point of interest near their current location.
  - *Example:* "Italian restaurant near me", "Emergency pharmacy open now", or "Gas station".
  - *Expectation:* Location maps, operational hours, addresses, and customer reviews.

---

## 2. Needs Met Rating Scale and Decision Tree

The Needs Met rating scale measures how helpful the search result is to a user based on their search query.

```
                  ┌─────────────────────────────────────┐
                  │ Does it solve the query completely? │
                  └──────────────────┬──────────────────┘
                                     │
                     ┌───────────────┴───────────────┐
                    YES                              NO
                     ▼                               ▼
      ┌──────────────────────────────┐ ┌──────────────────────────────┐
      │       Fully Meets (FullyM)   │ │ Does it provide high value?  │
      │   (Immediate answer, no more │ └──────────────┬───────────────┘
      │      searching required)     │                │
      └──────────────────────────────┘        ┌───────┴───────┐
                                             YES              NO
                                              ▼               ▼
                                       ┌───────────┐   ┌─────────────┐
                                       │ HighlyM   │   │ MM/SM/Fails │
                                       └───────────┘   └─────────────┘
```

### 🏆 Fully Meets (FullyM)
* **Definition:** The result completely and immediately answers the query. The user is fully satisfied and does not need to look at any other results.
* **When to apply:** Only for narrow, non-ambiguous queries (e.g., official logins, short calculations, conversions).
* **Exceptions:** Broad queries with multiple interpretations (e.g., "depression treatments" or "best laptops") can never receive a FullyM rating because no single result satisfies all users.

### ⭐ Highly Meets (HM)
* **Definition:** Very helpful, detailed, and completely satisfying. It covers the core intent for almost all users.
* **When to apply:** High-quality articles, secure download interfaces, or comprehensive product reviews by credible authors.

### ⚖️ Moderately Meets (MM)
* **Definition:** Good and helpful, but missing some key details or only satisfies a secondary intent of the query.
* **When to apply:** Decent content that needs more depth, or an article that only addresses a specific part of a broad search topic.

### ⚠️ Slightly Meets (SM)
* **Definition:** Low utility. The user has to do significant reading, filtering, or click through multiple pages to find the answer.
* **When to apply:** Thin content, posts filled with keyword fluff, or generic articles written without real E-E-A-T.

### 🚨 Fails to Meet (FailsM)
* **Definition:** Completely useless.
* **When to apply:** Irrelevant results, dead links, outdated information, deceptive pages, or lowest-quality scam sites.
