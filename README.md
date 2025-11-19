# README — Advanced Evaluation Prompts

This repository collects two high-precision prompts designed to help you **analyze arguments** and **review technical documents** in a structured, reproducible way.

- One prompt is a **logical argument stress-test**, focused on the structure, validity, and soundness of arguments.  
- The other is a **public release readiness checklist** for technical reports and white papers.

The underlying prompt files live in this repo under:  
**`LMM-Prompts/Prompts/`**  
and are also linked directly below.

---

## 📘 Included Prompts

### **1. Structured Logical Argument Test Prompt**  
**File:** [`Structured_Logical_Argument_Test_Prompt.md`](https://github.com/russnida-repo/LMM-Prompts/blob/main/Prompts/Structured_Logical_Argument_Test_Prompt.md)

A comprehensive prompt for **stress‑testing arguments** using a consistent logical rubric. It is designed to help you examine:

- Explicit premises and hidden assumptions  
- Logical form and validity  
- Factual soundness and key term definitions  
- Reasoning methods and overall evaluation  

The prompt bundles an **8‑Step Logical Rubric** and a large set of variant tasks (A–AC), including:

- Scientific and philosophical claim analysis  
- Moral and theological claims  
- Ambiguity, humor, and interpretation  
- Constraint-following and instruction precision  
- Ethics, creativity, quantitative reasoning, and meta‑reflection  

You can use any LLM to **apply this framework to arguments you care about**—policy claims, op‑eds, research statements, or everyday reasoning.

---

### **2. Technical Report / White Paper Public Release Review Prompt**  
**File:** [`Technical_Report_White_Paper_Pre_Publication_Test_Prompt.md`](https://github.com/russnida-repo/LMM-Prompts/blob/main/Prompts/Technical_Report_White_Paper_Pre_Publication_Test_Prompt.md)

A structured evaluation prompt for checking whether a **technical report or white paper** is ready for public release (GitHub, arXiv, SSRN, personal site, etc.).

It guides the model through a full **Release Readiness Assessment**, covering:

- Clarity and honesty of claims  
- Framing and scope vs. evidence  
- Practical utility for practitioners and researchers  
- Transparency and reproducibility  
- Safety, ethics, and potential for harm  
- Technical completeness (figures, methods, references, appendices)  
- Quick fixes, suggested enhancements, and priority action items  

Use this prompt when you want a **neutral, checklist-driven review** before putting technical work in front of a broader audience.

---

## 🎯 Purpose of This Repository

This repo provides two focused tools:

1. A **logical argument evaluation framework** for analyzing claims and reasoning.  
2. A **public-release checklist** for technical reports and white papers.

They are useful for:

- Researchers and analysts testing the strength of arguments  
- Technical writers and engineers preparing reports  
- Prompt designers building consistent evaluation workflows  
- Anyone who wants more disciplined reasoning and clearer documentation

You can of course run these prompts across multiple LLMs to compare how different models handle the **same argument** or **same document**, but their primary purpose is to evaluate the **content**, not the models.

---

## 🧠 How to Use the Prompts

1. Open the prompt file via the links above.  
2. Paste the full prompt into your LLM of choice.  
3. When prompted, provide:
   - An argument or claim set (for the Structured Logical Argument Test), or  
   - A technical report / white paper (for the Release Review Prompt).  
4. Let the model work through the structure the prompt enforces.  
5. Use the output as:
   - A diagnostic on the argument or document, and/or  
   - A way to compare different models’ handling of the same task.

---

## 📄 License

This project is licensed under the terms of the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:

- **Share** — copy and redistribute the material  
- **Adapt** — remix, transform, and build upon the material  

Under the following term:

- **Attribution** — You must give appropriate credit.

License File (in this repo):  
[`LICENSE`](LICENSE)

---

## 📂 File Links

- [`LMM-Prompts/Prompts/Structured_Logical_Argument_Test_Prompt.md`](https://github.com/russnida-repo/LMM-Prompts/blob/main/Prompts/Structured_Logical_Argument_Test_Prompt.md)  
- [`LMM-Prompts/Prompts/Technical_Report_White_Paper_Pre_Publication_Test_Prompt.md`](https://github.com/russnida-repo/LMM-Prompts/blob/main/Prompts/Technical_Report_White_Paper_Pre_Publication_Test_Prompt.md)

---

If you’d like, I can also:

- Draft a short **“How to interpret results”** section for each prompt  
- Add suggested **versioning and changelog** language  
- Prepare a **one-paragraph summary** suitable for r/promptengineering or similar forums.
