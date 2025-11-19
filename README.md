# Structured Argument Analysis & Technical Document Review Prompts

This repository contains two high-precision prompts designed to support **rigorous reasoning, argument analysis, and technical document evaluation**. These prompts are intended for anyone who wants structured, repeatable methods for evaluating claims, arguments, or pre-publication documents.

The prompt files live in:

**`LMM-Prompts/Prompts/`**

---

## 📘 Included Prompts

---

## 1. Structured Logical Argument Test Prompt
**File:**  
https://github.com/russnida-repo/LMM-Prompts/blob/main/Prompts/Structured_Logical_Argument_Test_Prompt.md

This prompt is a **complete, end-to-end framework for analyzing arguments**.  

It provides a formal, multi-stage method for breaking down and stress-testing any argument, including:

### What it does
- Identifies **explicit premises**, **hidden assumptions**, and **formal logical structure**
- Tests **validity** (does the conclusion follow?) and **soundness** (are the premises true?)
- Analyzes:
  - Key terms  
  - Methods of reasoning  
  - Ambiguities  
  - Interpretive assumptions  
- Applies multiple forms of stress-testing:
  - Counterarguments  
  - Alternative interpretations  
  - Generalization tests  
  - Changing assumptions  
- Detects logical fallacies and explains why they matter  
- Steelmans (strengthens) the argument while preserving intent  
- Produces a fully structured, labeled **formal proof**
- Provides:
  - A summary assessment  
  - A final verdict (Pass / Partial / Fail)  
  - Requirements for the argument to pass  

### Best for
- Philosophical arguments  
- Historical claims  
- Policy debates  
- Op-eds, essays, political arguments  
- Any structured reasoning that needs formal evaluation  

---

## 2. Technical Report / White Paper Public Release Review Prompt
**File:**  
https://github.com/russnida-repo/LMM-Prompts/blob/main/Prompts/Technical_Report_White_Paper_Pre_Publication_Test_Prompt.md

This prompt evaluates whether a **technical report, white paper, or research document** is ready for public release.

It guides an LLM through a complete **Release Readiness Assessment**, covering:

- **Critical issues** that would block responsible release  
- Claim framing, scope, and methodological transparency  
- Reproducibility of methods  
- Practical utility for intended audiences  
- Technical completeness (methods, figures, tables, appendices)  
- Safety, ethics, risks, and potential harm  
- Quick improvements and priority actions  

### Best for
- Technical reports  
- White papers  
- Research summaries  
- GitHub documentation  
- Preprints (arXiv, SSRN, OSF)  

---

## 🎯 Purpose of This Repository

These two prompts are intended to give users **structured, repeatable tools** for:

- Evaluating arguments with formal logical rigor  
- Assessing the publication-readiness of technical documents  

They provide **process**, not judgment—making them useful regardless of which LLM is used to carry them out.

---

## 🧠 How to Use

1. Open one of the prompt files using the links above.  
2. Paste the entire prompt into your model of choice.  
3. Provide the argument or document when requested.  
4. The model will follow the structured evaluation process.  

Both prompts work well across ChatGPT, Claude, DeepSeek, Grok, Gemini, and others.

---

## 📄 License

This project is licensed under the  
**Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to share and adapt the material with proper attribution.

License file:  
[`LICENSE`](LICENSE)


