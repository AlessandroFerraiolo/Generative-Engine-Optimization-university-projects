# Generative Engine Optimization (GEO) Research Suite

This repository collects three distinct academic projects investigating **Generative Engine Optimization (GEO)**, the emerging practice of optimizing brand visibility within Generative AI search results (e.g., ChatGPT, Gemini, Perplexity).

All three projects were conducted as three different coursework to explore different facets of the topic central to my startup, **Refinea**, and my ongoing Bachelor's thesis. Each module analyzes a simplified slice of the broader research, tackling GEO from Economic, Strategic, and Analytical perspectives.

---

## 📂 Projects Overview

### 1. Economic Research Proposal
**Context:** Microeconomics / Information Economics
**Folder:** `Economic_Research_Proposal`
**File:** `AI_Consumer_Choice_Research_Proposal.pdf`

* **Objective:** Investigates "AI Intermediaries and Consumer Choice", proposing a theoretical framework to determine if LLMs act as rational economic agents.
* **Key Question:** Do AI recommendations follow traditional market signals (price, quality) or are they driven by "frictions" like technical accessibility and information density?.
* **Contribution:** Attempts to apply standard microeconomic frameworks (e.g., Akerlof, Stigler) to opaque neural networks.

### 2. Marketing Research Proposal
**Context:** Strategic Marketing
**Folder:** `Marketing_Research_Proposal`
**File:** `Report_Optimizing_Brand_Visibility_in_AI_Search`

* **Objective:** Defines a strategic roadmap for GEO to conquer AI chatbots a new marketing channel. The proposal outlines how brands can shift budget from traditional SEO/SEM to AI-focused strategies.
* **Hypotheses:** Tests the impact of "Social Buzz," technical readiness (e.g., `llms.txt`), and third-party authority on AI citations.
* **Goal:** To create a repeatable managerial playbook for increasing Share of Voice in AI answers.

### 3. Applied Marketing Analytics Report (Stata & Python)
**Context:** Marketing Analytics / Econometrics
**Folder:** `Applied_Marketing_Analytics_Report_Stata_Python`
**File:** `Report_Applied_Marketing_Analytics_Report_Stata_Python` 
(all stata and python scripts included in the folder)

* **Objective:** A hands-on empirical execution of GEO concepts using the global **Password Manager** industry as a case study.
* **Methodology:**
    * **Data Collection:** Custom Python pipeline querying ChatGPT (gpt-4o-mini) and Gemini (gemini-2.5-flash).
    * **Analysis:** Conditional Logistic Regression (Fixed Effects Logit) performed in Stata.
* **Key Findings:**
    * **Community is King:** "Social Buzz" (Reddit, YouTube, LinkedIn) was the strongest predictor of mentions (Odds Ratio ~11).
    * **The "Gatekeeper" Effect:** Gemini was found to be ~60% less likely to mention brands compared to ChatGPT, acting as a stricter filter.
    * **Review Saturation:** High review ratings were a baseline requirement but not a statistically significant differentiator for top-tier brands.

---

## 🚀 Context: Refinea & Bachelor Thesis

While these projects were submitted individually for different university courses, they serve as modular validation for the core technology and philosophy behind **Refinea**.

* **The Thesis:** My upcoming Bachelor's thesis integrates these distinct pillars—economic theory, strategic application, and quantitative proof—into a comprehensive model of how Generative Engines reconstruct consumer markets.
* **The Startup:** These findings directly inform the R&D for Refinea, moving beyond "keyword stuffing" to optimizing for the semantic and social signals that actually drive AI recommendations.

---

## 🛠️ Technologies & Tools
* **Languages:** Python (Data Collection & API Interaction), Stata (Econometric Modeling).
* **APIs:** OpenAI (ChatGPT), Google (Gemini).
* **Methods:** Experimental Design, Prompt Engineering, Regex Mention Extraction, Fixed Effects Logistic Regression.

---

*Disclaimer: These documents are academic coursework submitted between 2024-2025. They represent snapshots of the rapidly evolving GEO landscape.*
