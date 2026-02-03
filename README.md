# Censorship Patterns Across Decades  
**Independent Research Project | Data Analysis & Statistical Methods**

## Overview
This project analyzes historical and contemporary patterns in literary censorship using an original, research-grade dataset of 119 documented book bans spanning from antiquity to the early 2020s. The study examines how the *frequency*, *motivation*, and *institutional level* of censorship have evolved across decades, regions, and political regimes.

The goal was not to catalog banned books exhaustively, but to construct a defensible dataset suitable for statistical analysis, cross-regional comparison, and hypothesis testing.



---

## Data & Methods
- **Dataset:** 119 censorship events across multiple centuries and regions  
- **Sources:** American Library Association, PEN America, Index on Censorship, UNESCO, national archives, Encyclopaedia Britannica  
- **Variables:** publication year, ban year, time-to-ban, region, regime type, ban level, censorship reason, repeat bans  
- **Approach:**  
  - Programmatic data validation (temporal logic, category integrity, relational checks)  
  - Exploratory data analysis with explicit aggregations  
  - Non-parametric statistics due to skewed distributions  
  - Chi-square tests and Kruskal–Wallis tests for inference  

All categorical variables were locked prior to dataset expansion to prevent classification drift.

---

## Key Findings

### 1. Censorship Motivations Shift Over Time  
Early censorship is dominated by **religious and moral objections**, while late 20th- and early 21st-century bans are primarily driven by **sexuality, race, and violence**. This suggests that censorship reflects changing social anxieties rather than a constant set of norms.

### 2. Governance Structure Shapes *Why* Books Are Banned  
A statistically significant association exists between **political regime type and censorship reason** (χ² = 46.86, p < 0.01). Democracies, hybrid regimes, and authoritarian systems restrict different types of content, indicating that censorship motivations are linked to governance rather than culture alone.

### 3. Modern Censorship Is Institutional and Localized  
The majority of contemporary bans occur at the **school level**, rather than through national prohibitions. This points to a decentralization of censorship authority, with local educational institutions acting as primary enforcement points.

### 4. Censorship Targets Authors, Not Just Books  
Authors associated with repeat bans show substantially higher average ban frequencies, suggesting systematic scrutiny of certain voices rather than isolated reactions to individual works.

### 5. Speed of Censorship Does Not Vary Significantly by Regime  
While motivations differ by regime type, the **time between publication and ban does not**, indicating that regimes vary more in *what* they censor than *how quickly* they act.

---

## Limitations
The dataset is curated rather than exhaustive, with uneven historical documentation across regions and time periods. Some contextual variables contain missing data due to archival constraints, and repeat entries for the same work reflect distinct institutional or jurisdictional actions. All conclusions are framed conservatively to reflect these constraints.

---

## Why This Project Matters
This project demonstrates end-to-end research capability: data construction, validation, exploratory analysis, statistical testing, and disciplined interpretation. It illustrates how social, political, and institutional factors shape information access—and how those patterns can be studied rigorously using data.

**Skills demonstrated:**  
Data curation • statistical analysis • research design • validation pipelines • data storytelling • policy-relevant insight

---
Visuals: 

<img width="628" height="470" alt="image" src="https://github.com/user-attachments/assets/c811c41b-5e62-4601-83bf-f23a00c8b16f" />


Image 1: The primary reasons for literary censorship shift over time, from religious and moral objections in earlier periods to sexuality-, race-, and violence-related concerns in recent decades.
