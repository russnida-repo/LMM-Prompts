Academic Paper Review Prompt 

C - Context
You are performing a technical peer review of a research paper. The paper is provided below in its entirety. Your role is to act as an anonymous referee evaluating the work for potential publication in a peer-reviewed venue (journal or conference).
Critical constraint: Base your review ONLY on content explicitly present in the provided paper. Do not assume knowledge of external benchmarks, datasets, or prior work unless they are cited and described in the paper itself.
G - Goal
Produce a structured, actionable peer review that:
1.	Identifies specific scientific, methodological, or presentation issues with exact locations
2.	Provides concrete suggestions for improvement
3.	Delivers a justified publication recommendation
Success criteria: Every critique must be traceable to specific paper content (quote + location). Avoid general statements without evidence.
A - Action
Perform a systematic evaluation following this sequence:
Step 1: Document Structure Scan
•	Note the paper's stated contributions (usually in introduction/abstract)
•	Identify what claims require verification (experiments, proofs, comparisons)
Step 2: Core Technical Review For each major claim in the paper:
•	Quote the exact claim (with section/page/line number)
•	Assess supporting evidence: Is it present? Sufficient? Correctly interpreted?
•	Check internal consistency: Do results/methods align with claims?
Step 3: Methodology Review
•	Experimental design: Are baselines described? Controls present? Statistical tests mentioned?
•	Reproducibility: Are hyperparameters, architectures, datasets specified?
•	Flag missing information rather than assuming it exists
Step 4: Presentation Review
•	Clarity: Are figures/tables labeled and referenced? Is notation consistent?
•	Structure: Does the flow support the narrative?
Step 5: Identify Gaps
•	What information is referenced but not provided (code, data, appendices)?
•	What external knowledge would be needed to fully validate claims?
F - Format
Structure your review using this exact template:
markdown
1. Summary (150-200 words max)
[2-3 sentences on main contribution]
[2-3 sentences on key strengths]
[1-2 sentences on primary concerns]

2. Major Issues
[For each issue, use this structure:]

#Issue #[N]: [Brief title]
Location: [Section X.Y, Page Z, Line W / Figure N / Table M]  
Quote/Reference: "[exact text]" OR [describe figure/equation]  
Problem: [Detailed explanation of the flaw - what's wrong and why it matters]  
Suggested Fix: [Concrete, actionable revision]  
Confidence: [High/Medium/Low] - [briefly explain uncertainty if Medium/Low]

3. Minor Issues & Suggestions
- [Issue with location reference]
- [Issue with location reference]
[Keep each under 2 sentences]

4. Questions for Authors
[List information that is unclear or missing - frame as questions rather than assumptions]
- "Section 3.2 mentions 'standard hyperparameters' - can you specify these values?"
- "Figure 4 shows improvement over baseline - which baseline is this?"

5. Recommendation
Score: [1-5] (1=Strong Reject, 2=Reject, 3=Borderline, 4=Accept, 5=Strong Accept)

Justification (1 paragraph, 100-150 words):
[Connect score to venue standards, cite specific Major Issues if rejecting, or specific strengths if accepting]

Estimated revision scope: [Minor/Major/Fundamental restructuring needed]
Length constraint: Entire review should be 1000-1500 words.
R - Review (Self-Check & Verification)
After completing your review, add this mandatory section:
markdown
Verification & Confidence Assessment

#Claims Requiring External Verification
[List any statements in YOUR review that reference external knowledge]
- "This approach differs from [Method X]" ← Would need to verify against original paper
- "Standard practice in [field] is..." ← Assumption based on general knowledge

#Limited Verification Due to Missing Materials
[List what prevented full assessment]
- "Code not provided - cannot verify implementation details"
- "Dataset described but not accessible - cannot assess data quality"
- "Appendix referenced but not included in submission"

#Low-Confidence Critiques (Require Author Response)
[List issues where paper ambiguity prevents definitive assessment]
- "Section 4 states '[quote]' - this could mean [interpretation A] or [interpretation B]"
- "Unclear if [specific technical choice] was intentional or oversight"

#Assumptions Made in This Review
[List any assumptions about venue, field norms, or standards]
- "Assumed target venue has [specific requirement]"
- "Evaluated statistical rigor by [specific standard]"
________________________________________
Instructions for Use:
1.	Paste the complete paper text after this prompt
2.	If available, specify: "Target venue: [conference/journal name]" to calibrate standards
3.	The LMM will generate the structured review
4.	You must manually verify: 
o	Any external references the LMM mentions
o	Mathematical/statistical claims in Major Issues
o	That all quotes actually appear in the paper
Risk Tier: YELLOW - This is a professional critique that requires fact-checking before sharing with authors or using for decisions.

