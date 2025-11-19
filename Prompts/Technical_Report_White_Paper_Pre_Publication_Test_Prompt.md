© 2025 Russell Nida This work is licensed under the Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International License (CC BY-NC-SA 4.0).

**Instructions for Use**
1. Add the document you want evaluated to your LMM of choice.
2. After attaching your document, copy everything starting from the line that begins with “Evaluate” down to the end of the document.
3. Paste that content into the LMM.

Evaluate the attached document using the following instructions:

## Context

You are reviewing a technical report or white paper intended for **public release** (website, arXiv, GitHub, SSRN, etc.) rather than peer-reviewed journal publication. The standards are different:

- **Goal**: Useful, transparent, reproducible technical documentation
- **Audience**: Practitioners, researchers, technical professionals
- **Standard**: "Fit for public consumption" not "meets peer-review bar"

## Your Role

Assess whether this document is **ready for public release** by checking:
1. **Clarity**: Can readers understand what was done and why?
2. **Honesty**: Are claims appropriately scoped to the evidence?
3. **Utility**: Will practitioners find this useful?
4. **Reproducibility**: Could others replicate or build on this work?
5. **Safety**: Are there misleading claims that could cause harm?

## Review Structure

Use this **exact format** for your review:

---

### RELEASE READINESS ASSESSMENT

**Overall Recommendation**: [Ready for Release / Minor Revisions Needed / Major Revisions Needed / Not Suitable for Release]

**Estimated Revision Time**: [X hours/days if revisions needed]

**Target Release Venue**: [Suggest: personal website / arXiv / SSRN / GitHub / other]

---

### 1. CRITICAL ISSUES (Release Blockers)

For each issue that would **prevent responsible public release**, provide:

**Issue #[N]: [Short title]**
- **Location**: [Section, page, or "Throughout"]
- **Problem**: [What's wrong - focus on: misleading claims, safety concerns, major unclear sections, missing essential information]
- **Why This Blocks Release**: [Explain potential harm or confusion]
- **Fix Required**: [Specific action needed]
- **Time Estimate**: [Hours to fix]

*If no critical issues*: State "✅ No release-blocking issues identified"

---

### 2. FRAMING & CLAIMS ASSESSMENT

Evaluate how the document frames its contributions and limitations:

**Current Framing**:
- What does the document claim to demonstrate/prove/show?
- What methodology was used?
- What limitations are acknowledged?

**Appropriateness Check**:
- [ ] Claims match the evidence provided
- [ ] Methodology limitations are disclosed
- [ ] Appropriate qualifiers used ("suggests" vs "proves")
- [ ] Scope is clearly defined

**Recommended Framing Adjustments** (if needed):
[List specific changes to better align claims with evidence level]

---

### 3. TRANSPARENCY & REPRODUCIBILITY

Check documentation quality:

**✅ What's Well-Documented**:
- [List strengths: clear methods, available data, documented process, etc.]

**⚠️ What Needs Clarification**:
- [List: missing details, ambiguous procedures, unclear terminology]

**🔧 Suggested Additions**:
- [Specific sections/info to add for reproducibility]

---

### 4. PRACTICAL UTILITY ASSESSMENT

**Who Will Find This Useful?**
- [Target audience: practitioners / researchers / specific domain]

**What Value Does It Provide?**
- [Novel framework / practical guidance / reproducible methodology / new data]

**How Could Users Apply This?**
- [Concrete use cases]

**What Cautions Should Users Know?**
- [Important limitations for practical application]

---

### 5. TECHNICAL COMPLETENESS

Check for missing elements:

**Content Gaps**:
- [ ] Abstract/Executive Summary present and clear
- [ ] Methods section complete
- [ ] Results/findings clearly presented  
- [ ] Figures/tables complete (no placeholders)
- [ ] References/citations complete
- [ ] Appendices complete (if referenced)

**Issues Found**:
[List missing figures, incomplete sections, broken references, etc.]

---

### 6. SAFETY & ETHICS CHECK

Scan for potential harm from public release:

**⚠️ Check for**:
- Misleading medical/legal/financial advice presented as validated
- Claims that could cause harm if taken as authoritative
- Missing warnings about known failure modes
- Insufficient disclosure of conflicts of interest or funding
- Privacy violations (PII, confidential data exposure)

**Assessment**: [Safe for release / Needs warnings added / Has serious concerns]

**Required Warnings/Disclaimers** (if any):
[Specific text to add]

---

### 7. QUICK FIXES (Low-Hanging Fruit)

List easy improvements (≤30 min each):

1. [e.g., "Fix Figure 3 placeholder"]
2. [e.g., "Add DOI placeholder for citation"]
3. [e.g., "Clarify abbreviation on first use"]

---

### 8. SUGGESTED ENHANCEMENTS (Optional)

Non-essential improvements that would increase value:

**For Practitioners**:
- [e.g., "Add one-page quick reference guide"]

**For Researchers**:
- [e.g., "Add comparison table to related work"]

**For Reproducibility**:
- [e.g., "Publish prompts in separate GitHub repo"]

---

### 9. VERIFICATION CHECKLIST

Document what you could and couldn't verify:

**✅ Verified Claims**:
- [Claims you can confirm from document content]

**❓ Unverifiable (But Not Necessarily Wrong)**:
- [Claims that reference external info, future work, or unavailable data]

**⚠️ Potential Inaccuracies**:
- [Specific claims that seem questionable - cite location and concern]

---

### 10. RELEASE RECOMMENDATIONS

**Suggested Release Format**:
- **Document Type**: [Technical Report / White Paper / Working Paper / Preprint]
- **License**: [Recommend CC BY / CC BY-NC-SA / other]
- **Version Label**: [e.g., "Version 1.0" or "Draft for Community Feedback"]

**Suggested Front Matter Additions**:
```
[Draft text for disclaimers, version info, citation format, etc.]
```

**Post-Release Strategy**:
- [Suggestions for gathering feedback, updates, companion materials]

---

### 11. PRIORITY ACTION ITEMS

Rank tasks by importance and estimated time:

**Must-Do Before Release** (Total time: X hours):
1. [Critical fix #1] (X hours)
2. [Critical fix #2] (X hours)

**Should-Do for Quality** (Total time: X hours):
1. [Important improvement #1] (X hours)
2. [Important improvement #2] (X hours)

**Nice-to-Have Enhancements** (Total time: X hours):
1. [Optional addition #1] (X hours)

---

## SPECIAL INSTRUCTIONS

### What to Focus On

**DO prioritize**:
- Whether claims are honestly framed for the evidence level
- Whether users can understand and reproduce the work
- Whether there are safety/harm concerns
- Whether essential information is present and clear

**DON'T worry about**:
- Whether methodology would pass peer review
- Whether sample size is "large enough" for publication
- Whether related work section is comprehensive
- Minor formatting inconsistencies

### Tone Guidelines

- **Be constructive**: Frame as "to strengthen for public release" not "this is wrong"
- **Be specific**: Give actionable fixes, not vague suggestions
- **Be realistic**: Estimate actual time needed, don't demand perfection
- **Be honest**: Flag real problems clearly, but don't invent issues

### Critical Principle

**The question is not "Is this perfect?" but "Is this honest, useful, and safe to share publicly?"**

A technical report can be valuable and release-ready even with limitations, as long as those limitations are clearly disclosed.

---

## Example Framing Fixes

### ❌ Overclaims (Needs Revision)
"This study **demonstrates** that Model A is superior to Model B for technical writing tasks."

### ✅ Appropriate Framing
"Based on systematic evaluation across 20 test prompts, Model A showed higher consistency in technical writing tasks than Model B. These findings are based on [author's evaluation / single-rater scoring / specific rubric] and should be validated in users' specific contexts."

### ❌ Missing Context
"Our four-model pipeline achieves 95% accuracy."

### ✅ With Context  
"In our test set of 100 policy documents, the four-model pipeline produced outputs rated as 'acceptable or better' by [the author / expert reviewers / automated metrics] in 95% of cases. Accuracy may vary significantly based on domain and task type."

---

## OUTPUT EXAMPLE

[Review should be structured exactly as outlined above, filling in each section based on the actual document content]