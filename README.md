Perfect — your **jobhunt** project is essentially a personal ATS‑powered job‑search agent. For your **PWP (Personal Work Project)** write‑up, you want something that feels professional, concise, and clearly related to the project. Here’s a draft you can adapt directly:

---

## 📌 Personal Work Project (PWP) – _Jobhunt: AI‑Powered Job Search Agent_

**Overview:**  
Jobhunt is a Python‑based automation tool designed to streamline the job‑search process. It integrates with public ATS APIs (Greenhouse, Lever, Ashby) to fetch postings daily, applies deterministic filters (title, location, freshness), and then uses LLMs to screen and draft application kits. The system ensures candidates only see highly relevant opportunities without wasting time on unsuitable roles.

**Key Features:**

- 🔍 **Automated Fetching:** Reads 2,000+ postings daily from ATS boards.
- ⚙️ **Prefiltering:** Regex‑based title/location filters reduce noise before any LLM call.
- 🤖 **LLM Screening:** Scores jobs against the candidate’s resume profile.
- 📝 **Drafting:** Generates tailored cover notes and application kits.
- 📧 **Digest Delivery:** Sends a daily HTML digest with top 5 opportunities.
- 🛡️ **Safe by Design:** Never auto‑submits applications; user reviews and submits manually.

**Tech Stack:**

- Python, FastAPI (CLI + backend)
- Anthropic Claude / Gemini / Groq (LLM providers)
- YAML‑based configuration for filters and companies
- SMTP for digest mailing
- GitHub Actions for daily scheduling

**Impact:**

- Reduced 2,000+ postings → ~40 candidates → 5 curated roles daily.
- Saves hours of manual searching and ensures focus on high‑fit opportunities.
- Cost‑efficient: deterministic filters keep LLM usage minimal (pennies per day).

**Learning Outcomes:**

- Practical experience with ATS APIs and JSON parsing quirks.
- Building modular pipelines (fetch → prefilter → screen → draft → digest).
- Hands‑on with LLM integration, prompt engineering, and cost optimization.
- End‑to‑end automation with GitHub Actions and secure secrets management.

---

👉 This PWP description positions your project as **applied AI + automation for career workflows**. It shows technical depth (Python, ATS APIs, LLMs) and practical impact (time savings, cost efficiency).

Would you like me to also **condense this into a 3–4 line resume bullet** so it fits neatly under your _Projects_ section?
"# Job-Hunt" 
