# SKILL: Vulture Nest Gap Discovery

## Objective
Identify underserved niches in the Google Workspace and MS Office ecosystems.

## Execution Steps
1. **Deep Research:** Use Gemini 3.1 Pro to scan Reddit, Stack Overflow, and niche forums for "How do I..." or "Why doesn't [App] do X?"
2. **Competitive Gap Analysis:** Cross-reference complaints with current top-rated store listings.
3. **Profitability Score:** Assign a score (1-10) based on pain intensity and technical feasibility.
4. **Output:** Generate a `research/gap_report.json` with the top 3 opportunities for CEO approval.

## Triggers
- Triggered by `/vulture-scan` command or weekly cron job.
