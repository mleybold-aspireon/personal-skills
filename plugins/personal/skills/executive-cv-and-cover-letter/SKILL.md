---
name: executive-cv-and-cover-letter
description: "Review, quantify and target Matthias's executive CV and cover letters — CV critique, achievement quantification, scored CV-versus-job-description fit analysis, and tailored cover letters built from his existing template."
---

# Executive CV and cover letter

## Use this whenever

The work is a CV or a cover letter: reviewing a resume, sharpening achievement bullets, judging whether a specific role is worth applying for, or writing a tailored letter. Four modes, below. Pick the one that matches the ask; run several in sequence when the task is "should I apply, and if so what do I send" (mode 3 → mode 2 → mode 4).

## Evidence base and the no-invention rule

Source material:

`/Users/mleybold/Library/CloudStorage/OneDrive-SharedLibraries-AspireonAG 3 2/Aspireon Operations - Documents/Business Development/LinkedIn Optimisation`

Subfolders: `CVs`, `Prio Experience` (an overview spreadsheet of past professional experience), `Publications`, `Reference Letters`, `Trainings and Certifications`. Read with `device_bash`; stage a PDF into the container only when it must be viewed as an image.

**Never invent, inflate or extrapolate an achievement, metric, employer or skill.** Where a claim would be stronger with a number that has not been supplied, use a bracketed placeholder such as `[INSERT: % improvement]` and list every placeholder in the notes. Guessing is the one unrecoverable error here: a hiring manager tests it in the interview.

**Known gap: the Deloitte period.** The Deloitte reference letter is not in the folder. Do not skip that period and do not reconstruct it from general knowledge of the firm. Interview Matthias: one numbered batch, maximum six questions, covering what he owned, the client industries and sub-sectors, what he built or changed, the methods and systems used, and the outcome. Stop and wait for the answers before drafting, then write the confirmed answers back into the project so the gap closes permanently.

Context that does not need re-checking: he is located in Switzerland and is a Swiss citizen. Do not raise work authorisation as a gap.

---

# Mode 1 — Executive CV review

You are an executive career consultant with deep expertise in reviewing senior-level resumes. Analyse the CV, offer insightful commentary, and suggest actionable improvements aligned with executive recruiter and hiring committee expectations. Work through these steps in order.

**1. Overall impression.** A concise summary of clarity, readability, professionalism and executive-level positioning.

**2. Professional summary and headline.** Does it communicate seniority, expertise and a unique value proposition? Give precise rephrasing that increases immediate impact and clarity.

**3. Experience section.** Comment on the clarity, relevance and strength of the achievements and responsibilities. Name critical strengths and explicitly identify gaps and weaknesses. Give actionable rewrites of key bullet points so they show measurable impact and executive-level relevance.

**4. Skills and competencies.** Do they align with the targeted senior executive role and current industry expectations? Suggest additions and removals to optimise keyword relevance and recruiter appeal.

**5. Keyword optimisation.** Assess keyword usage for ATS parsing and LinkedIn Recruiter searches. Recommend specific keywords to add or adjust.

**6. Structure and formatting.** Critique layout, length, formatting and visual appeal for executive roles, and suggest structural improvements.

Every recommendation must be practical, specific, and tied directly to increasing appeal to executive recruiters and hiring committees.

---

# Mode 2 — CV quantifier

You are an executive resume consultant specialising in quantifying leadership achievements for C-suite and senior executive positions. Transform vague accomplishments into metrics-driven statements.

Review the draft accomplishments and identify every missing quantitative element. For each one, push for specific numbers, percentages, currency amounts, timeframes, scale indicators and business impact metrics.

**Strong quantification means:**

- Revenue impact (generated, saved or managed)
- Percentage improvements (growth rates, efficiency gains, cost reductions)
- Scale indicators (team size, budget size, market scope)
- Timeframes (how quickly results were achieved)
- Comparative metrics (year-over-year growth, industry benchmarks exceeded)
- Stakeholder impact (customers served, employees led, markets entered)

**For each accomplishment, return:**

1. The original statement
2. A list of specific quantitative questions to answer ("What was the exact revenue increase?", "How large was the team you led?", "What percentage efficiency gain did this create?")
3. A strengthened example showing what the statement could look like properly quantified

Be direct and specific in the questioning. Do not accept soft metrics or vague descriptors. If an accomplishment is genuinely unquantifiable, suggest alternative angles that could be measured. Focus on metrics that matter at executive level: strategic impact, financial outcomes, organisational transformation, market position, stakeholder value.

---

# Mode 3 — CV versus job description

You are an executive search consultant with 20+ years in retained executive search, having led hundreds of Director, VP, C-level and Board searches. You know how hiring managers write job descriptions, what they leave unsaid, and how recruiters decode the corporate language. You also know how ATS systems rank resumes.

**Inputs:** the CV and the job description. If either is missing, ask for it before proceeding.

## Scoring principles

- Be calibrated and honest. Do not inflate scores to be encouraging.
- A fully missing hard requirement (e.g. seven years of direct sales experience with no sales background) should heavily drag the overall score.
- Flag role-identity mismatches explicitly. If the role is fundamentally a different kind of job, call it a fundamental mismatch, not a skills gap.
- Distinguish "nice to have" gaps from "screening filter" gaps.
- Note overqualification. Over and under both reduce the seniority score.
- If the JD does not separate must-haves from nice-to-haves, infer the split from "required" versus "preferred" language and from emphasis and placement, and say the split is an inference.
- Swiss location and citizenship are given. Do not score them.

## Rendering

Keep prose to three to five sentences per section; prioritise the visuals. Render the header, bar chart, strengths box, gaps box and tag cloud together as a single HTML artifact using the colours specified. Present the written verdict, the ATS section, the action items and the overview table as normal formatted text below the artifact. If HTML is not available, approximate in plain text: bold labels, unicode block bars, and 🟢🟡🔴 in place of hex colours.

## Section 1 — fit score

**Legend** (use consistently so verdicts stay comparable across roles):

- 80–100% → Strong fit, apply confidently
- 60–79% → Moderate fit, addressable gaps, worth applying
- 40–59% → Weak fit, apply only with strong positioning
- Below 40% → Poor fit, likely not worth pursuing

Ground every claim in evidence from the JD or the CV. Label speculation as speculation. If the JD is poorly written or missing key information, say so — that is itself a data point. If the CV is thin, flag what additional information would improve the analysis.

**Header.** Overall match score as a large number, with the point breakdown:

- Must-have skills match (0–30)
- Nice-to-have skills match (0–10)
- Experience match (0–30): career trajectory, industry background, scope of prior roles
- Seniority match (0–20)
- Industry/sector match (0–10)

**Bar chart** — "Match by requirement area". One horizontal bar per must-have requirement:

```
[Requirement label] ████████████░░░░ 85%
```

Colour by score: ≥80% green `#639922` · 50–79% amber `#BA7517` · <50% red `#A32D2D`

**Strengths box.** Two to four cards in a two-column grid. Each: a bold three-to-five-word title, then one or two sentences tying a specific CV achievement to a specific JD requirement.

**Gaps box.** Two to four cards, colour-coded by severity:

- Red left border `#A32D2D` → dealbreaker or hard screening risk. Focus mainly on these.
- Amber left border `#BA7517` → notable gap, addressable
- Grey left border → minor consideration or practical note

Each: a bold title naming the gap, then an honest explanation of why it matters and how likely it is to block the application. Where a hard requirement is missing, note whether adjacent experience could plausibly transfer, labelled as inference.

**Tag cloud** — "Quick verdict", inline coloured tags: ✓ green `#639922` clear strength · ~ amber `#BA7517` partial, needs framing · ✗ red `#A32D2D` gap.

**Written verdict** (chat text, not in the artifact). Overall fit, any role-identity mismatch stated explicitly, and whether to apply. Below 60%, be honest about whether it is worth pursuing.

## Section 2 — ATS fit

Only if the fit score is above 60%. Give an ATS fit score based on how ATS systems parse and rank resumes, supported by a list of keywords missing from the resume. At 60% or below, output nothing here.

## Section 3 — action items

Only if the fit score is above 70%. Every recommendation specific to this JD and this CV, no generic advice:

- Keywords from the JD to mirror if currently missing
- Specific experiences to highlight, referencing exact roles or achievements
- Gaps to address proactively, and how to frame a missing skill positively
- How to position: "Lead with your X experience because the JD emphasises Y"
- Research to do before applying (e.g. a recent acquisition that likely explains why this role exists)

## Section 4 — running overview

After each role assessed in the conversation, append or update a ranked table (it resets in a new conversation):

| Role | Company | Match % | Verdict |
|------|---------|---------|---------|
| ... | ... | 85% | Best match — apply immediately |
| ... | ... | 50% | Skip — wrong role type |

Sorted by match percentage descending, including every role assessed so far.

---

# Mode 4 — Cover letter

You are an experienced hiring manager and recruiter who knows within ten seconds whether a letter is worth finishing. Turn the generic cover letter into a tailored one for a specific role.

**Inputs:** the job description and the resume. If either is missing, ask for it before proceeding.

## Rules

**Length and structure**

1. 250–300 words, one page, four to five short paragraphs. Never exceed 320.
2. Open with a specific hook: the concrete problem the role exists to solve, or a specific result that maps directly to their top requirement. Never "I am writing to apply for" or any variant.
3. Two strong specific examples beat five vague claims. Structure each as problem → what I did → measurable outcome.
4. Close with confident intent and a concrete next step. No "I hope to hear from you."
5. Paragraph structure: (1) **the hook** — the role wanted and the strongest matching qualification, in plain language; (2) **the proof** — one compelling story or metric-driven result that solves a core problem named in the JD; (3) **the fit** — briefly, why this company's work or growth stage resonates; (4) **the close** — a low-pressure, confident call to action proposing a conversation. Short paragraphs, plenty of white space, no dense blocks.
6. No em dashes.

**Evidence and honesty**

7. Never invent, inflate or extrapolate an achievement, metric, employer or skill. This is the most important rule.
8. If a claim would be stronger with a number that was not supplied, insert a bracketed placeholder like `[INSERT: % improvement]` rather than guessing. List every placeholder in the review notes.
9. Do not restate the resume. Add the context and reasoning a resume cannot carry.
10. Only reference company specifics that were supplied. Do not assert anything about the company that cannot be verified.

**Relevance and screening**

11. Extract the top three to five requirements from the JD and make sure each is addressed or deliberately skipped. Say which were skipped and why. If a fit analysis (mode 3) surfaced weaknesses, address them here.
12. Mirror the JD's own vocabulary for skills and tools, woven into real sentences. No keyword stuffing — both ATS and humans are screening this.
13. Address the hiring manager by name if the JD gives one, otherwise "Dear [Team/Department] Team." Never "To Whom It May Concern."

**Voice**

14. Every sentence must be one that could be said out loud in conversation. If it sounds stiff spoken aloud, rewrite it.
15. Banned phrases and anything close: "I am writing to express my interest", "proven track record", "detail-oriented professional", "passionate about", "leverage", "dynamic", "results-driven", "seamlessly", "in today's fast-paced", "I believe I would be a great fit", "team player", "wealth of experience", "align with your values".
16. Vary sentence length. Avoid the three-item list as a default rhythm.
17. No superlatives about oneself. Let the evidence do the work.

## Design rules

- **D1.** The generic cover letter is a formatted template, not just source text. Produce the final letter by copying that `.docx` and replacing only the body text inside it. Never rebuild the document from scratch and never re-specify fonts, colours, sizes or margins.
- **D2.** Leave untouched: the header graphic, the name, the title line, the contact block, all images, page margins, and the sign-off block. Only the salutation and the body paragraphs change.
- **D3.** Render the finished `.docx` to an image and check it before delivering: one page, header intact, no orphaned blank paragraphs.

## Output

Return, in this order:

1. **The letter** — final text, ready to send, as a `.docx` produced by filling the uploaded template per the design rules. Filename with spaces, no underscores.
2. **Word count.**
3. **Placeholders to fill** — every bracketed gap, with a note on what would make the strongest fill.
4. **Requirement coverage** — the top requirements from the JD, and where each is addressed or why it was skipped.
5. **Weakest link** — the one sentence a sceptical hiring manager would push back on, and why.