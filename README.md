# Primo ATS: AI-Driven Career Strategy Orchestrator 🚀

**Live Demo:** [Primo ATS on AWS PartyRock](https://partyrock.aws/u/primo21/1u-WgjQ7Z/Primo-ATS) 

## 📖 Project Overview
**Primo ATS** is an end-to-end career transition engine designed to bridge the gap between a candidate's existing technical background and the specific requirements of high-level Cloud and IT roles. 

Built on **AWS PartyRock**, this application uses advanced prompt engineering to provide more than just a resume—it delivers a 360-degree career roadmap including technical gap analysis, automated STAR interview stories, and strategic business insight.

---

## 📸 Application Gallery
<table>
  <tr>
    <td><img src="screenshots/1_welcome.png" width="300pt" /><br><sub>1. Welcome & UX</sub></td>
    <td><img src="screenshots/2_job_input.png" width="300pt" /><br><sub>2. Universal Input</sub></td>
    <td><img src="screenshots/3_resume_top.png" width="300pt" /><br><sub>3. Optimized CV (Top)</sub></td>
  </tr>
  <tr>
    <td><img src="screenshots/4_resume_bottom.png" width="300pt" /><br><sub>4. Optimized CV (Bottom)</sub></td>
    <td><img src="screenshots/5_cover_letter.png" width="300pt" /><br><sub>5. Tailored Cover Letter</sub></td>
    <td><img src="screenshots/6_career_bridge.png" width="300pt" /><br><sub>6. Translatable Skills</sub></td>
  </tr>
    <tr>
    <td><img src="screenshots/7_gap_analysis.png" width="300pt" /><br><sub>7. Technical Gaps</sub></td>
    <td><img src="screenshots/8_star_interview.png" width="300pt" /><br><sub>8. STAR Interviewing</sub></td>
    <td><img src="screenshots/9_strategy_salary.png" width="300pt" /><br><sub>9. Strategic Acumen</sub></td>
  </tr>
  <tr>
    <td colspan="3" align="center"><img src="screenshots/10_career_pivot.png" width="500pt" /><br><sub>10. Alternative Career Pivot Logic</sub></td>
  </tr>
</table>

---

## 🛠️ Key Technical Features
* **Universal Prompt Engineering:** Developed dynamic extraction logic that identifies company identity and industry challenges from any raw Job Description, ensuring the tool is vendor-agnostic.
* **Logic-First Architecture:** Refactored the application backend to move from dual-input dependency to a streamlined **Single Source of Truth (File Upload)**, resolving variable conflicts and improving User Experience (UX).
* **The "Uno Reverse" Strategy:** Built a custom logic gate that extracts core business challenges a hiring company is facing and generates strategic questions for the candidate to ask, demonstrating high-level business acumen.
* **Alternative Career Pathing:** Integrated a fail-safe career pivot logic that automatically suggests alternative job roles based on a real-time gap analysis between the CV and the target role.

## 🧰 AWS & AI Technologies
* **Generative AI:** Claude 3 (via Amazon Bedrock / PartyRock)
* **Prompt Engineering:** Multi-modal data ingestion and conditional logic gating.
* **Cloud Infrastructure:** Prototyped using AWS PartyRock's low-code environment.

---
*Developed as part of the AWS re/Start program to demonstrate the practical application of Generative AI in career development.*
