**Faculty of Information Technology (FIT) – Ho Chi Minh City University of Science (HCMUS)**

**CS423 / CSC13003 – Software Testing (AI-augmented · 2026\)**

**AI POLICY · TEMPLATES — 2026 v1.0**

# **AI Audit Report — 5-section Template per Artifact**

*Mandatory appendix for every AI-assisted homework (HW\#01–HW\#06, and Seminar).*

*Adapted from Med Kharbach, PhD (2026) — AI Use Policy Templates for Higher Education. CC BY-NC-SA 4.0. This adaptation is prepared for FIT@HCMUS – CS423 / CSC15003 Software Testing course.*

## **1\. Student Information**

| Field | Value |
| :---- | :---- |
| **Student name (printed):** | Nguyen Thanh Gia Bao  |
| **Student ID:** | 23127158  |
| **Class / Cohort:** | 23KTPM3  |
| **Assignment ID (e.g., HW\#00, HW\#02):** | HW#01  |
| **Assignment date:** | 07/06/2026  |
| **AI tool(s) used:** |  Chat GPT, Claude Sonnet 4.6 |
| **AI tool(s) used:** | \[x\] Yes  \[ \] No |

## **2\. Instructions (read before filling)**

* Add one row per AI-generated artifact (test case, script, checklist, OpenAPI spec, JMeter plan, etc.).  
* Paste the verbatim prompt — DO NOT paraphrase.  
* Paste the verbatim AI output (or include a labelled screenshot in the report).  
* Tag the verdict: VALID / INVALID / INCOMPLETE.  
* Reasoning must cite a course slide, ISTQB section, or technical RFC.  
* Show the corrected artifact with the change highlighted.  
* Sample rows are in italic — replace them before submission.

## **3\. Audit Table — one row per artifact**

| (1) Prompt \+ Tool | (2) AI Output | (3) Verdict | (4) Reasoning (ISTQB) | (5) Student Fix |
| :---- | :---- | :---- | :---- | :---- |
| Tool: ChatGPT  Time: 14:40 05/06/2026 Prompt: "Thiết kế cho tôi 15 test case cho quạt máy bàn theo dạng bảng có Test Case ID, Objective, Precondition, Input, Steps, Expected Result, Actual Result, Verdict"| [AI_OUTPUT_01](./Artifact/artifact_01/AI_Output_01.png) [AI_OUTPUT_02](./Artifact/artifact_01/AI_Output_02.png) |INCOMPLETE | The generated test cases covered normal functional scenarios such as power on/off, speed selection, and oscillation. However, the output did not include sufficient edge case testing. According to ISTQB Foundation Level, test design should consider both valid and invalid conditions, including boundary and exceptional situations. A complete test suite should verify system behavior under unusual operating conditions, not only expected user actions. The AI-generated artifact missed several important edge cases related to fan operation limits and abnormal usage conditions.| Added three edge test cases to improve coverage: TC03, TC04, TC05|
| Tool: ChatGPT Time: 16:27 04/06/2026 Prompt: "Vẽ QA/QC mindmap dưới dạng mermaid" |[AI_OUTPUT](./Artifact/artifact_02/AI_Output.png)  | INCOMPLETE |The generated mind map included the basic concepts of QA and QC but omitted several important quality assurance and quality control activities. According to ISTQB, quality management should cover process monitoring, verification activities, and continuous improvement practices such as root cause analysis. These missing elements make the artifact incomplete and reduce its educational value.|Added the missing concepts to the mind map: Verification under QC activities; Process Monitoring under QA activities; Root Cause Analysis under QA continuous improvement activities. |
| Tool: Claude Sonnet 4.6 Time: 1:19 07/06/2026 Prompt: "Requirement 2 – 20 Software Defects 2022–2026 (20 pts) Find 20 software defects publicized between 2022 and 2026. Mandatory: ≥ 5 defects related to AI/LLM (hallucination, prompt injection, bias). Each defect: source link, description, severity, consequences, solution. Thực hiện requirement 2 với các yêu cầu trên. Sau khi tìm xong hãy cho tôi một file md bằng tiếng việt chứa 20 defects."|[AI_OUTPUT](./Artifact/artifact_03/AI_Output.png) [File_Generated_By_AI](./Artifact/artifact_03/20_software_defects_2022_2026.md)  | INCOMPLETE | Some defects in Requirement 2 were reported without proper source links, reducing traceability and verifiability of the information. In addition, a number of descriptions show signs of AI hallucination and potential bias, where details were inferred or interpreted without sufficient evidence from authoritative sources. | Re-check all 20 defects and add valid, authoritative source links for each entry. Highlight any descriptions that are not directly supported by sources to clearly indicate potential hallucination or bias instead of removing them.|


## **4\. Summary of AI Accuracy**

Aggregate the verdicts from Section 3 and complete the table below.

| Metric                                   | Count | Percentage |
| :--------------------------------------- | :---- | :--------- |
| **Total AI-generated artifacts audited** | 3     | 100%       |
| **VALID (correct, accepted as-is)**      | 0     | 0%         |
| **INVALID (wrong; rejected)**            | 0     | 0%         |
| **INCOMPLETE (acceptable after edits)**  | 3     | 100%       |

## **5\. Conclusion — When should AI be used (or not)?**

AI is very effective in providing a strong foundation for requirements such as test case design. For example, when designing 15 test cases, AI can quickly generate a complete initial set, helping to significantly reduce the time and effort compared to manually creating everything from scratch. This makes it useful for improving productivity and ensuring basic coverage at an early stage.

However, AI cannot guarantee full accuracy or completeness. It may miss important edge cases or scenarios that only become visible when testing the actual product in real conditions. Therefore, every AI-generated output must be carefully reviewed, validated, and refined by humans before being used in final reports or testing activities.


## **6\. Mandatory Disclosure (paste verbatim)**

Test cases / mindmap / report was initially generated by ChatGPT and Claude Sonnet 4.6; I reviewed and modified the test cases by adding 3 additional edge cases. I also reviewed and updated the QA/QC mindmap by adding missing activities related to QA/QC processes. In the report, I reviewed Requirements 1 to 3 and corrected sections that were not reasonable or inconsistent. Section 5 was written entirely by me. The detailed AI Audit Report is attached as Appendix A. I confirm I did not use AI to generate any artifact listed in the prohibited category.


## **Signature**

| Student name (printed): | Nguyen Thanh Gia Bao  |
| :---- | :---- |
| **Student ID:** | 23127158  |
| **Class / Cohort:** | 23KTPM3 |
| **Course:** | CS423 / CSC13003 – Software Testing |
| **Instructor:** | Dr. Lam Quang Vu / Dr. Tran Duy Hoang / MSc. Tran Thi Bich Hanh / MSc. Truong Phuoc Loc / MSc. Ho Tuan Thanh  |
| **Date:** | 07/06/2026 |
| **Signature:** | ![](./signature.png) |

## **References**

* Kharbach, M. (2026). AI Use Policy Templates for Higher Education. CC BY-NC-SA 4.0.  
* ISTQB Foundation Level Syllabus (latest version).  
* Hardman, P. (2025). A Post-AI Learning Taxonomy.  
* Fuster Rabella, M. (2025). OECD Education Working Paper No. 338\.  
* Perkins, M., Roe, J., & Furze, L. (2025). AI Assessment Scale.  
* Anthropic (2025). Building reliable AI test agents — engineering blog.  
* DeepEval & Promptfoo documentation — testing frameworks for LLM systems.